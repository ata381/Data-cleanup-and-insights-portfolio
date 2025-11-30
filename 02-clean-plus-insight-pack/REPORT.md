# Clean + Insight Pack — Sales Summary

## Overview
We analysed a synthetic extract of 45 cleaned ecommerce orders covering January–April 2023. The dataset represents consumer purchases across the Netherlands, Belgium, Germany, and France with mixed product categories such as Electronics, Home, Clothing, and Beauty.

## Data Quality Improvements
- Parsed and standardised order dates (multiple input formats) while dropping the single row that lacked a valid timestamp.
- Removed duplicate order IDs plus rows with zero/negative unit prices before analysis.
- Normalised country names and aligned text fields (countries, payment methods) for consistent grouping.
- Capped extreme discount values at 60% and enforced numeric types to ensure trustworthy revenue calculations.

## Key Metrics
- **Total revenue:** ~EUR 8.3k after cleaning.
- **Orders analysed:** 45 unique transactions.
- **Average order value:** ~EUR 185.
- **Top categories:** Electronics (~EUR 3.7k), Home (~EUR 1.8k), Clothing (~EUR 1.2k).

## Visual Highlights
- Monthly revenue grows from ~EUR 1.7k in January to ~EUR 2.6k in March before dipping slightly in April, signalling momentum worth monitoring.
- Electronics is the standout category, more than doubling Home and triple Clothing, while Beauty and Sports contribute smaller but steady streams.
- The Netherlands generates ~65% of revenue, with Belgium and Germany forming the next tier and France providing emerging demand.

## Recommended Next Steps
1. Double down on Electronics merchandising bundles, given their outsized contribution.
2. Run targeted campaigns in the Netherlands and Belgium to sustain the current growth curve.
3. Investigate April's softening revenue for potential stock, marketing, or seasonality factors.
4. Audit discount policies above 40% to confirm they drive profitable incremental sales.
5. Layer simple retention or cohort views onto the cleaned dataset to see how returns or repeat purchases shape revenue.
