# British Airways Review Dashboard – Tableau Project

## Project Overview
This Tableau project analyzes British Airways customer reviews from March 2016 to October 2023, focusing on passenger sentiment, service experience and satisfaction trends. The dashboard helps identify performance patterns across countries, aircraft types, traveler categories and time periods, enabling data-driven insights into airline service quality.

## Problem Statement
Airlines receive thousands of customer reviews, yet understanding patterns across time, locations and traveler types is challenging. This dashboard solves that by bringing together review scores, traveler attributes and aircraft information into a single analytics view. It helps stakeholders identify what influences passenger satisfaction and where improvements can be made.

## Dataset Description
### ba_reviews.csv (Main Reviews Dataset)
Contains detailed customer reviews with the following columns:
| Column Name         | Description                      |
| ------------------- | -------------------------------- |
| header              | Review header/title              |
| author              | Reviewer name                    |
| date                | Review date                      |
| place               | Reviewer country                 |
| content             | Review text                      |
| aircraft            | Aircraft type used               |
| traveller_type      | Business, Leisure, Solo, etc.    |
| seat_type           | Economy, Business, First Class   |
| route               | Flight route                     |
| date_flown          | When the reviewer travelled      |
| recommended         | Yes/No (reviewer recommendation) |
| trip_verified       | Verified trip flag               |
| rating              | Overall rating score             |
| seat_comfort        | Rating of seating comfort        |
| cabin_staff_service | Rating of cabin crew service     |
| food_beverages      | Food & drink rating              |
| ground_service      | Ground staff rating              |
| value_for_money     | Value for money rating           |
| entertainment       | In-flight entertainment rating   |






![Dashboard Preview](BritishAirwaysReview.png)

## Key Features

- **Average Ratings Breakdown**  
  Visualizes scores across categories like Cabin Staff Service, Entertainment, Food & Beverages, Ground Service, Seat Comfort and Value for Money.

- **Interactive Filters**  
  Slice the data by:
    - Rating category
    - Month of travel
    - Traveller type (e.g.: Business, Couple Leisure)
    - Seat type (Economy, Premium Economy, Business, First Class)

- **Dynamic Visuals**
  - 📈 *Average Overall Rating by Month*: Time series trends from 2016–2023  
  - 🌍 *Average Rating by Country*: Geographic sentiment mapping  
  - 🛫 *Rating by Aircraft*: Compare aircraft models like Boeing 747-400, Airbus A380, etc.

- **Review Distribution**  
  Horizontal bar chart showing the count of reviews by star rating (1–5).

## 📊 Dashboard Link

Explore the live dashboard on Tableau Public:  
👉 [British Airways Review Dashboard](https://public.tableau.com/shared/Z65N6WXS9?:display_count=n&:origin=viz_share_link)

## 🧠 Motivation

This project was inspired by the need to understand how customer experience varies across different flight conditions and aircraft types. It demonstrates how data visualization can uncover patterns in service quality and traveler satisfaction, helping airlines and passengers alike make informed decisions.

## 🛠️ Tools Used
- **Tableau Public** – for dashboard design and interactivity  

## Connect with Me 🤝
If you found this project interesting, let’s connect!  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow%20Me-blue?logo=linkedin&style=for-the-badge)](https://www.linkedin.com/in/sunil-prajapati832) 

