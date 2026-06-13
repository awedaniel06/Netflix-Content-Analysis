# 📺 Netflix Content Analysis

## Project Overview

This project analyzes Netflix's content library to uncover trends in content distribution, audience targeting, geographic representation, and catalog growth.

Using Excel and Power BI, I explored Netflix's dataset to understand how the platform has evolved over time and identify strategic opportunities for future growth.

---

## Business Problem

Netflix operates one of the world's largest streaming libraries, but content quantity alone does not guarantee sustainable growth.

This analysis seeks to answer:

- What types of content dominate Netflix's catalog?
- Which audience segments receive the most attention?
- Which countries contribute the most content?
- How has Netflix's content library grown over time?
- What potential risks and opportunities exist within Netflix's current content strategy?

---

## Dataset Information

The dataset contains information on:

- Show_id
- Content type
- Content ratings
- Listed_in (Genres)
- Title
- Countries of production
- Date added to Netflix
- Release year
- Duration
- Directors
- Cast members

---

## Data Cleaning Process

The dataset was cleaned and transformed using Power Query.

Cleaning Steps

✔ Removed duplicate records

✔ Trimmed unnecessary spaces

✔ Standardized column values for consistency

✔ Replaced blank values with "N/A"

✔ Split the Country column into individual rows to accurately analyze content contributions by country

✔ Created separate dimension tables for:

- Country
- Genre

✔ Built relationships between dimension tables and the main fact table

✔ Created a calculated Year column from the Date Added field to support yearly trend analysis

---

## Dashboard Features

Content Distribution

- Movies vs TV Shows
- Percentage share of each content type

Audience Analysis

- Content ratings distribution
- Audience targeting patterns

Geographic Analysis

- Top contributing countries
- Global content distribution

Genre Analysis

- Most common content categories
- Genre concentration

Growth Analysis

- Content additions over time
- Yearly growth trends

---

## Key Insights

1. Movies Dominate the Catalog

Movies account for approximately 70% of Netflix's content library, while TV Shows represent only 30%.

2. Mature Audiences Are the Primary Focus

TV-MA is the most common rating, suggesting Netflix heavily targets adult viewers.

3. Content Production Is Concentrated

The United States contributes the largest share of content, with India ranking second.

4. International Movies Lead the Platform

International Movies, Dramas, and Comedies are the most represented genres.

5. Rapid Growth Followed by Slowdown

Content additions increased significantly between 2016 and 2020 before showing signs of decline.

---

## Business Questions

- Is Netflix becoming overly dependent on mature audiences?
- Are certain genres receiving disproportionate investment?
- Does the decline in content additions indicate future growth challenges?
- Could increasing TV Show production improve subscriber retention?
- Is Netflix relying too heavily on content from a small number of countries?

---

## Recommendations

Diversify Audience Reach

Expand family-friendly and youth-focused content to attract broader demographics.

Balance Genre Investments

Increase investment in underrepresented genres with emerging demand.

Investigate Content Addition Decline

Determine whether the slowdown reflects strategic optimization or potential growth limitations.

Expand High-Retention Content

Invest further in quality TV series that encourage longer subscriber engagement.

Strengthen Global Content Diversity

Increase content production across additional countries to reduce geographic concentration and enhance global appeal.

---

## Tools Used

- Power BI
- Power Query
- DAX
- Excel 

---

## Conclusion

The data suggests that Netflix's future success may depend less on expanding its content volume and more on optimizing its content strategy.

A balanced portfolio across audiences, genres, and regions can help Netflix strengthen engagement, reduce strategic risks, and support sustainable long-term growth.

---

## Dashboard Preview

![Netflix Dashboard](Nextflix%Dashboard/netflix_dashboard.png)

---


Data Analyst Portfolio Project

Created to demonstrate skills in:

- Data Cleaning
- Data Modeling
- Data Visualization
- Business Intelligence
- Data Storytelling

