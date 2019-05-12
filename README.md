# Intro

Hello, Trivago Team!

First, I want to thank you for sharing this dataset with me, and more importantly,
for taking the time to review my application and considering me for this
Data Science opportunity!

This assignment was definitely challenging and fun, and I hope you enjoy my
walk through the project, and that we can discuss it in the future.

# Task - # Predict CPC Bid

The objective of this work is to predict the right bid for a campaign,
given that all campaigns have to reach 15% CPA.

For this reason, all campaigns that didn't reach a 15% CPA were excluded from my dataset.

There are 3 important formulas that were used on the challenge, those were
provided on the challenge

CPC Bid = target CPA * BVPC estimate

CPA = direct_cost / direct_booking_value

BVPC = direct_booking_value / direct_clicks

# Follow my work

Please follow the notebooks in this repo according on the following order.

**1_Preprocessing_&_DataVis.ipynb**
**2_Baseline.ipynb**
**3_Final_Model.ipynb**

The final predictions can be find at results/final_predictions.csv

## Important Note:
For this regression problem, I only used the campaign that achieved more than 15% CPA.
