# FUNNEL-ANALYSIS
Funnel Analysis Project

Project Overview

This project aims to analyze user behavior on a website using funnel analysis to track the journey from initial visit to purchase completion. The data comes from the raw_events table in BigQuery, which captures various user interactions based on timestamps.

Objectives

Understand User Behavior: Identify key events that users perform on the website.

Data Cleaning: Ensure each user is counted only once per unique event to avoid inflating results.

Funnel Creation: Build a funnel chart that tracks user progression through key events.

Country-wise Analysis: Compare funnel performance for the top three countries with the highest number of events.

Insights & Recommendations: Identify drop-off points and suggest improvements to optimize conversions.

Methodology

1. Data Exploration

Queried the raw_events table to understand event types, timestamps, and user activity.

Identified duplicate events and determined a method for selecting unique events per user.

2. Data Cleaning

Removed duplicate events, ensuring only the first occurrence of each event per user was retained.

The final dataset includes only unique user-event combinations for accurate funnel analysis.

3. Identifying Key Funnel Events

Selected 4-6 meaningful events for the funnel.

Ordered events in a logical sequence to analyze user progression.

4. Aggregation by Country

Identified the top three countries by event volume.

Grouped user activity by event type and country.

Calculated the percentage drop-off at each stage of the funnel.

5. Visualization & Insights

Created a funnel chart to display user drop-off through different stages.

Applied conditional formatting to highlight key trends.

Suggested actionable insights to improve conversion rates.

Deliverables

Data Table: A structured table showing event progression with percentage drop-offs.

Funnel Chart: A graphical representation of user flow through key events.

Insights & Recommendations: Business-driven analysis of retention and drop-off trends.

Key Insights

High Drop-off at Checkout: A significant number of users abandon their carts before completing a purchase. Recommendations include improving the checkout experience and implementing cart abandonment reminders.

Differences Across Countries: Conversion rates vary by country, indicating potential localization opportunities.

Re-engagement Strategies: Influencer marketing, loyalty programs, and targeted ads can help retain users who drop off early in the funnel.

Reference

For SQL queries used in this project, please refer to the uploaded file.

Next Steps

Further segment data by device type, traffic source, or returning vs. new users.

Conduct A/B testing to evaluate improvements in funnel conversion.

Implement personalized email or push notification campaigns for users dropping off before purchase.

