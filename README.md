# -Sport-Participation-Club-Performance-Analysis-Power-BI-

📌 Project Overview

This project was undertaken as a self-initiated data challenge to strengthen my skills in data analysis, Power BI modelling, and data storytelling within the context of public sector sport and physical activity.

Using publicly available data published by sportscotland, I analysed club membership, participant engagement, and coaching capacity across Scotland over a three-year period. The aim was to understand how participation in sport is changing over time, identify patterns across gender, age group, and geography, and present these insights in a clear, decision-focused dashboard.

🎯 Context & Data Source

sportscotland works in partnership with Scottish Governing Bodies (SGBs) to support opportunities for people across Scotland to take part in sport.
As part of this, data is collected and published on:

Club membership

Participants (non-members)

Coaches

Local authority coverage

The dataset used in this project was sourced from the sportscotland website and covers three years (2023–2025) for a single Scottish Governing Body.

📊 Dashboard Structure

The Power BI report is structured into three analytical pages, supported by a custom navigation menu built using bookmarks and buttons for a clean, app-like user experience.

Page 1: Club Members – Year-on-Year Performance

Purpose: Understand how formal club membership is changing over time.

Key insights:

Total membership increased to 234K, with a 2.01% year-on-year growth

Adult members account for 147K, while youth members account for 84K

Female members total 111K and male members 129K

Growth patterns vary significantly across clubs, highlighting areas of strong performance and areas that may require targeted support

Visuals included:

KPI cards (Total members, YoY growth, gender split)

Line chart showing membership trends over time

Stacked bar chart showing adult vs youth and male vs female composition

Club-level growth ranking

Club summary matrix with YoY %, Youth %, and Female %

Page 2: Participants – Year-on-Year Performance

Purpose: Analyse participation beyond formal club membership.

Key insights:

Total participants reached 134K

Adult participants: 76K

Youth participants: 57K

Female participation represents 44% of total participants

Youth participation represents 43% of total participants

Participation levels are highest in major urban local authorities

Visuals included:

KPI cards for total participants and demographic percentages

Trend analysis showing YoY changes

Participation composition by year

Club-level participation performance

Participation by local authority comparison

Why this matters:
Participant data provides insight into future membership potential and highlights where engagement strategies may be most effective.

Page 3: Coaches, Capacity & Location – Year-on-Year Analysis

Purpose: Assess coaching capacity in relation to participation growth.

Key insights:

Total coaches: 2,570

Qualified coaches: 1,263 (49%)

Female coaches represent 29% of the workforce

Coaches-to-members ratio: 0.01

Coaching capacity is unevenly distributed across local authorities

Visuals included:

KPI cards (Total coaches, Qualified %, Female %)

Coaches by local authority bar chart

Qualification split over time

Gender balance by region

Coaches per club ranking

Strategic implication:
While participation and membership are increasing, coaching capacity — particularly qualified and female coaches — may become a limiting factor without targeted development.

🧭 Navigation & User Experience

A dedicated menu page was created using Power BI bookmarks and custom buttons

Enables intuitive navigation between report sections

Improves usability for non-technical stakeholders

Creates a professional, application-style experience

🛠️ Data Preparation & Modelling

Data was cleaned and transformed using Power Query

Separate fact tables created for members, participants, and coaches

A lookup table used for club–local authority mapping

Relationships modelled using Club ID and Year

Measures built using DAX for:

Year-on-year analysis

Percentages and ratios

Gender and youth representation

🔎 Data structure note:
The source data contained multiple row headers, which required restructuring during data preparation. A more standardised, single-header tabular structure would further improve efficiency and data accuracy in future releases.

📈 Key Skills Demonstrated

Power BI data modelling

DAX (YoY calculations, ratios, percentages)

Power Query transformations

Data storytelling for public-sector decision-making

UX design using bookmarks and navigation

Translating raw data into actionable insight

🚀 Future Enhancements

Extend analysis with longer historical time series

Track conversion from participants to members

Introduce age-band segmentation

Benchmark performance against national averages

Add drill-through pages for club-level deep dives
