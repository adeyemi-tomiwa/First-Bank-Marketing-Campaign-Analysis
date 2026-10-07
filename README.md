# First-Bank-Marketing-Campaign-Analytics-
An end-to-end data analytics project analyzing customer demographic and behavioral patterns to optimize term deposit subscription rates for First Bank. This project translates raw marketing campaign data into actionable business recommendations and an interactive visual dashboard.
## Project Overview
The objective of this project is to evaluate the effectiveness of First Bank's direct marketing campaigns aimed at driving subscriptions to term deposit accounts. By analyzing customer profiles, historical campaign results, contact channels, and seasonal patterns, this project identifies primary drivers of customer conversion to maximize future ROI.

## Key Metrics & KPIs

Total Customers Analyzed: 11,163 (represented as 11.16K)

Total Conversions: 5,289 (5.29K)

Overall Subscription Rate: 47.4%

Average Call Duration: 6.20 minutes

## Interactive Dashboard

<img width="633" height="347" alt="Screenshot 2026-10-07 133834" src="https://github.com/user-attachments/assets/8b54154c-f00e-4ea6-9c85-5551fef53477" />

### Dashboard Highlights:

KPI Scorecards: Instant visibility into Total Customers, Conversions, Conversion Rates, and Average Call Duration.

Demographic Breakdown: Subscription rate analyses by Job Category, Customer Age Brackets, and Balance Tiers.

Engagement & Channel Performance: Conversion efficiency across Cellular vs. Landline and Engagement Levels (Low, Medium, High).

Seasonality Trends: Monthly volume vs. conversion rate tracking.

Interactive Slicers: Dynamic filtering by Previous Campaign Outcome (poutcome) and Customer Age Bracket.

##  Data Preparation & Quality

Dataset Size: 11,163 customer records evaluated across 21 attributes (age, job, account balance, loan status, campaign contact details, etc.).

Missing & "Unknown" Values: Categorized unrecorded fields (such as previous marketing outcomes) into distinct unknown cohorts rather than removing them, preventing bias and preserving valuable volume metrics.

### Feature Engineering & Aggregation:

Created custom Age Brackets (18-30, 30-40, 40-50, 50-60, 60-70, 70+).

Structured Balance Tiers (Low, Medium, High) to measure wealth distribution against conversion readiness.

Segmented Engagement Levels based on call interaction and frequency.

## Key Findings & Insights

### Call Duration as Primary Conversion Driver:

Average call duration across all contacts was 6.20 minutes.

Longer, meaningful conversations directly correlated with higher agreement rates, proving that engagement quality outweighs contact volume.

### Demographics & High-Converting Cohorts:

Seniors & Older Adults: Customers aged 60–70 (84.0%) and 70+ (79.9%) had the highest conversion rates.

Students: Achieved a 74.7% conversion rate, making them a prime emerging demographic.

Job Types: Students (74.7%) and Retirees (66.3%) led all professional categories.

### Previous Campaign Synergy:

Prior positive response (poutcome = success) is the strongest predictor of repeat conversion, yielding a 91.3% subscription rate.

### Timing & Seasonality Dynamics:

Peak Efficiency Months: Off-peak months showed massive conversion rates: December (90.9%), March (89.9%), September (84.3%), and October (82.4%).

Low Efficiency Bottlenecks: May saw the highest call volume but achieved the lowest conversion rate (32.8%).

### Contact Channel Performance:

Cellular contacts produced 42.67% of overall conversions, outperforming traditional landlines (39.58%).

## Strategic Recommendations

 Target High-Converting Segments: Prioritize marketing efforts toward retirees, seniors (60+), and students rather than over-allocating budget to lower-responding middle-aged brackets.

 Quality Over Velocity: Train sales agents to focus on consultative sales conversations rather than fast pitches. Keeping prospects engaged past the 6-minute mark significantly increases conversion probability.

 Reallocate Seasonal Budget: Shift agent bandwidth and campaign budget away from high-volume, low-yielding months like May toward high-converting periods in March, September, October, and December.

 Cellular-First Strategy: Adopt mobile devices as the primary channel for customer outreach.

 Leverage Warm Leads First: Always prioritize customers with a history of campaign success (poutcome = success), as over 90% re-subscribe.
