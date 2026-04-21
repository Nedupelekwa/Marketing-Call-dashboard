# Marketing Calls Analysis Dashboard

## Project Overview
This project provides a comprehensive data analysis of marketing outreach performance. It utilizes a large-scale dataset of telephonic interactions to evaluate lead conversion, program interest, and communication effectiveness.

## Dataset Structure
The core analysis is based on the `Raw Data` sheet, which includes 14,741 entries with the following attributes:
* **Date**: The chronological record of the outreach effort.
* **Programme**: The specific course or service offered (e.g., Virtual Assistant, Cyber Security, Music Production, Film Production, Content Creation).
* **Status**: The direct result of the call (e.g., "Ringing, No Answer", "I Will Pay", "Already Paid", "Device Constraint").
* **Category**: A higher-level classification of the outcome (e.g., "Will Make Payment", "Unanswered", "No Longer Interested").
* **Answered Status**: A binary indicator of whether a conversation was successfully established.

## Key Insights & Objectives
* **Conversion Tracking**: Identifying the percentage of leads that progress to "Already Paid" or "Will Make Payment" statuses across different programs.
* **Lead Quality Analysis**: Evaluating programs with high "No Longer Interested" or "Wrong Number" rates to refine target demographics.
* **Operational Efficiency**: Analyzing "Unanswered" call patterns and "Dropped Call" instances to optimize call timing and technical infrastructure.
* **Program Popularity**: Comparative analysis of outreach volume vs. success rate for specific tracks like Virtual Assistant and Cyber Security.

## Technologies Used
* **Google Sheets**: For data hosting, initial cleaning, and structured categorization.
* **Data Visualization**: Google sheets

## How to Use
1. **Raw Data**: View the source metrics in the `Raw Data` sheet.
2. **Filtering**: Use the `Programme` and `Category` columns to segment results by specific marketing campaigns.
3. **Status Audit**: Review the `Status` column to understand specific barriers to conversion (e.g., Technical Difficulties or Device Constraints).
