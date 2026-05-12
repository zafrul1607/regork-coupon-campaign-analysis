# regork-coupon-campaign-analysis

## Project Overview

This project analyzes Regork's Campaign 18 coupon promotion using the Complete Journey retail dataset. The goal is to evaluate campaign effectiveness, identify customer segments with higher coupon redemption rates, analyze product-level sales lift, and recommend data-driven promotional strategies.

## Business Problem

Regork invests heavily in coupon campaigns but needs to understand whether promotions are driving incremental sales or simply subsidizing purchases that customers would have made anyway. This analysis helps answer:

1. Are promoted products generating sales lift?
2. Which customer segments respond most strongly to coupons?
3. When do customers redeem coupons during the campaign?
4. Which products deserve future promotional investment?

## Tools and Packages Used

This project was completed in R using R Markdown.

Main packages:

- completejourney
- tidyverse
- lubridate
- scales
- gt
- rmarkdown
- knitr

## Data Source

The analysis uses the `completejourney` R package, which contains retail transaction, campaign, coupon, product, and household demographic data.

Datasets used include:

- campaign_descriptions
- campaigns
- coupons
- coupon_redemptions
- transactions
- products
- demographics

## Main Analysis Sections

- Campaign redemption timing
- Income-based redemption analysis
- Household composition analysis
- Product-level revenue lift
- Weekday sales pattern analysis
- Pre, during, and post-campaign revenue comparison
- Strategic recommendations for future campaigns

## How to Run the Project

1. Clone this repository.
2. Open the project folder in RStudio.
3. Install the required packages:

```r
install.packages(c(
  "completejourney",
  "tidyverse",
  "lubridate",
  "scales",
  "gt",
  "rmarkdown",
  "knitr"
))
