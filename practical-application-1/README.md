# Will the Customer Accept the Coupon?

## Project Overview

This project is part of the UC Berkeley Professional Certificate in Machine Learning and Artificial Intelligence.

The goal was to explore what factors might influence whether a driver accepts a coupon while driving. I used Python, pandas, and Seaborn to look at the data, compare different groups of drivers, and see what patterns I could find.

## Dataset

The dataset comes from the UCI Machine Learning Repository and contains 12,684 observations.

I checked for missing values and removed the `car` column because almost all its values were missing. I kept the other columns and worked with the available data for each comparison.

Overall, 56.84% of the coupons were accepted.

## What I Explored

I started by looking at the overall coupon acceptance rate, the types of coupons offered, and the temperature distribution.

I then looked more closely at Bar coupons to see whether visiting habits and other driver characteristics made a difference.

For my independent investigation, I chose Coffee House coupons. I wanted to see whether acceptance rates differed based on how often drivers visit coffee shops, their age, and whether they were traveling alone or with passengers.

## What I Found

For Bar coupons, drivers who visited bars more than three times a month had a 76.88% acceptance rate, compared with 37.06% for those who visited three or fewer times.

I noticed a similar pattern with Coffee House coupons. Drivers who visited coffee shops 4–8 times a month had a 68.59% acceptance rate, compared with 18.88% for those who never visited.

I also found that drivers traveling with friends were more likely to accept Coffee House coupons than those traveling alone (59.69% versus 43.79%).

Age showed some differences, but most age groups had fairly similar acceptance rates.

## My Takeaways

One thing that stood out to me was how much visiting habits seemed to matter for both Bar and Coffee House coupons.

Based on these findings, I think businesses could make better use of coupons by considering how often customers visit a particular type of business, rather than sending the same offers to everyone.

Of course, these are patterns in the data. They don't necessarily mean that one factor causes someone to accept a coupon.

## Tools Used

- Python
- pandas
- Matplotlib
- Seaborn
- Google Colab

## Notebook

[View my analysis](Practical_Application_1.ipynb)

## Data Source

[UCI Machine Learning Repository — In-Vehicle Coupon Recommendation](https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation)
