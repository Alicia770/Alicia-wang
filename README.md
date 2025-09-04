# Programming Language Trend Analysis with PySpark

## Table of Contents
- Project Overview
- Approach
- Key Findings
- Business Impact

## Project Overview
This project analyzes the top 10 programming language trends over the past five years using a large-scale dataset. The goal was to transform raw data into a structured DataFrame containing the following features:
- language
- quarter
- post_count
- percentage_of_total
- growth_rate

The project not only measures overall popularity but also identifies which languages are growing vs. declining in relevance.

## Approach
- PySpark & Spark SQL: Used for large-scale data processing, filtering, and transformation.

- Window Functions: Applied to compute quarter-over-quarter growth rates and trend analysis.

- Matplotlib: Created visualizations to illustrate popularity trends across time.

## Key Findings
- Produced a cleaned and filtered dataset segmented by language and quarter (2019–2024).

- Generated a visualization of the top 10 programming languages, highlighting their popularity trends.

- Identified the top 5 fastest-growing and top 5 fastest-declining languages.


## Business Impact
The Expected output includes language, quarter, post_count, percentage_of_total, and growth_rate.

This provided a structured dataset with post counts, growth rates, and share of total activity, enabling clear trend tracking.

Visualizations showed R experienced the steepest decline in popularity over the past five years.

Insights can support curriculum design, hiring strategies, and technology investment decisions by identifying which languages are gaining traction and which are losing relevance.

<img width="511" alt="Screenshot 2025-04-01 at 3 01 21 PM" src="https://github.com/user-attachments/assets/cd26625a-efae-4435-a7e7-efddfbc1d96d" />



