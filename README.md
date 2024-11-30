# Screen Time Project

## Table of Contents
1. [Motivation](#motivation)
2. [Tools](#tools)
3. [Data Source](#data-source)
4. [Data Processing](#data-processing)
5. [Data Visualizations](#data-visualizations)
6. [Data Analysis](#data-analysis)
   - [Active Times](#active-times)
   - [Notifications and Unlocks](#notifications-and-unlocks)
   - [Usage Intensity Across Applications](#usage-intensity-across-applications)
   - [Trends in Time Spent Across App Categories](#trends-in-time-spent-across-app-categories)
7. [Findings](#findings)
   - [Daily Activity Patterns](#daily-activity-patterns)
   - [Notifications and Application Prioritization](#notifications-and-application-prioritization)
   - [Trends in Usage by Categories](#trends-in-usage-by-categories)
8. [Limitations](#limitations)
   - [Data-Sourced Limitations](#data-sourced-limitations)
   - [Personal Limitations](#personal-limitations)
9. [Future Work](#future-work)

---

## Motivation
The increasing dependency on smartphones has a huge impact on daily routines and time management strategies. Today, increased phone usage and time spent on social media are significant. This project aims to analyze smartphone usage patterns to understand the time a university student spends on social media, phone usage time, notifications, app interactions, and overall trends.

---

## Tools
- **Python**: Examination and analysis of data in code.
- **Pandas**: Used to organize, filter, and clean the dataset.
- **Excel**: Processing and analysis of data.

---

## Data Source
1. **Screen Time Data**:
   - Processed from iPhone reports between October 2024 and November 2024.
   - Includes daily statistics such as notification counts, screen unlocks, and application usage durations.

2. **Custom Categories and Insights**:
   - Most active time of day (morning, afternoon, evening).
   - Categorical breakdown of apps used.

---

## Data Processing
- Organized data by date, starting from 11/29/2014 and ending on 10/1/2014.
- Calculated daily averages for screen time and notifications.
- Categorized apps such as TikTok, Zoom, WhatsApp, Instagram, and YouTube.
- Analyzed daily active periods.

---

## Data Visualizations
1. **Daily and Weekly Trends**:
   - Bar charts to represent daily app usage and notification intensity.
   - Line graphs to visualize weekly changes in total screen time.

2. **Application Usage Insights**:
   - Pie charts categorizing time spent across applications.

3. **Interruptions and Unlocks**:
   - Scatter plots showing the relationship between notifications and screen unlocks.

---

## Data Analysis

### Active Times
- Peaks in smartphone use during mornings (8 AM - 11 AM) and evenings (7 PM - 10 PM).
- Periodic declines in late-night use.

### Notifications and Unlocks
- Notifications directly correlate with an increase in phone unlock frequency.
- Social Media apps, especially WhatsApp and Instagram, are the primary contributors to high notification counts.

### Usage Intensity Across Applications
- Social Media dominates total screen time, with Instagram being the most-used app.
- Productivity apps see steady usage during the workweek.

### Trends in Time Spent Across App Categories
- Weekends show a marked increase in Entertainment app usage.
- Notifications are higher on weekdays, driven by work-related apps.

---

## Findings

### Daily Activity Patterns
- Screen time varies across weekdays and weekends, with a clear increase in recreational app use on weekends.
- Weekday mornings are dominated by productivity tools, while evenings are reserved for social apps.

### Notifications and Application Prioritization
- WhatsApp and Instagram generate the majority of notifications, often leading to excessive screen unlocks.

### Trends in Usage by Categories
- Social Media accounts for nearly 40% of the total screen time.
- Entertainment apps show spikes on Fridays and Saturdays.

---

## Limitations

### Data-Sourced Limitations
- Limited to two months of screen time data, which may not capture seasonal variations.
- Data is user-specific and may not generalize to other individuals.

### Personal Limitations
- Lack of in-depth metadata from the iPhone's Screen Time feature limits further detail.
- The iPhone screen time section allows access to only the past one month of data.

---

## Future Work
1. **Extended Data Collection**: Incorporate a larger dataset spanning multiple months or seasons.
2. **Machine Learning Models**: Develop predictive tools to anticipate high screen time days or app usage trends.
3. **Interactive Dashboards**: Create a dynamic interface for exploring data insights using tools like Power BI.
4. **Behavioral Recommendations**: Offer tailored suggestions to reduce distractions and improve productivity based on analysis.
