# Product-Analytics-User-Behavior-Analysis
Overview

This project analyzes large-scale e-commerce event data to understand user behavior across browsing, purchasing, retention, and engagement stages. The goal is to identify funnel drop-offs, retention patterns, and distinct user segments to derive actionable product insights.

Dataset

Source: E-commerce user interaction logs
Scale: ~285 million raw events
Approach:
A representative sample of ~5–10 million events was used for analysis to balance scale and computational efficiency.
Methodology

Exploratory Data Analysis (EDA) to understand event distribution and user activity
Funnel analysis to evaluate conversion behavior (View → Cart → Purchase)
Cohort-based retention analysis to measure user churn over time
User-level feature engineering and K-Means clustering for behavioral segmentation
Key Insights

User behavior is heavily browsing-driven, with over 97% of interactions being product views.
Approximately 60% of purchases occur without a cart event, indicating strong direct-purchase behavior.
Cohort analysis reveals sharp Day-1 churn (~80–85%), followed by stabilization among returning users.
User segmentation identifies four distinct groups:
Casual Browsers
Window Shoppers
Impulse Buyers
Power Users
A very small fraction of power users contributes disproportionately to engagement and purchases.
Tools Used

Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
Jupyter Notebook

Future Work

Validate findings on a larger data sample
Build supervised models for churn or purchase propensity
Design A/B tests to evaluate retention and conversion improvements
