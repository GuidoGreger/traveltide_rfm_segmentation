# TravelTide Customer Segmentation & Rewards Program

## Data-Driven Retention Strategy for an Online Travel Startup

## Project Goal
Designed a personalized rewards program to improve customer retention for TravelTide, an e-booking startup struggling with repeat bookings despite its industry-leading travel inventory.

## Project Overview
This repository contains the complete TravelTide customer segmentation project, which addresses declining customer retention by developing a data-driven rewards program. The project analyzes customer booking behavior using RFM (Recency, Frequency, Monetary) segmentation to identify distinct customer segments and design personalized perks for each segment.

## Business Context
TravelTide is an e-booking startup in the online travel industry that provides customers with a large travel inventory. Despite its impressive inventory, the company faces challenges with customer retention. This project aims to develop a valid customer segmentation to tailor perks for a rewards program that keeps customers returning to the TravelTide platform.

## Repository Contents

### Data Processing & Analysis
#### **Google Colab Notebook:**
  * **Comprehensive SQL** queries for data extraction, cleaning, and feature engineering
    * Preliminary analysis of database inconsistencies
    * Data cleaning procedures
    * Feature engineering
    * Aggregation to session and user level

#### **Tableau Workbook**
* **RFM segmentation implementation**
  * Worksheets and Dashboards for segment analysis
  * Perk assignment logic
  * Visualizations

#### Data Files
* User-Level Data (traveltide_user_data.csv): Aggregated data at the user level (output from SQL query)
* Segmented User Data (user_rfm_segments_perks.csv): Final user-level data enhanced with RFM scores, segments, perks, and perk descriptions

#### Presentation
* **Project Summary** (TravelTide_Project_Summary_Guido_Greger.pdf): Executive summary and detailed project report
* **Presentation Slides** (TravelTide_Presentation_Guido_Greger.pdf): Slides for stakeholder presentation
* **Presentation Video** Due to the file size limitations of GitHub you can find my recorded presentation here: [The Loyalty Compass - Data-Driven Pathways to Personalized Travel Rewards](https://drive.google.com/file/d/1lX0sqTJDQhnzBgTBteRZGIw0OlzlKvpE/view?usp=sharing)

## Methodology
### Data Scope
**Time Period:** January 2023 - July 2023
**User Cohort:** High-engagement users with 7+ sessions (5,998 users)
**Base Date:** July 31, 2023 (for recency calculations)

### Data Cleaning
The project addressed several data inconsistencies:

* Duplicate cancellation records
* Negative hotel nights
* Reversed timestamps (check-in after check-out)
* Missing values for seats, bags, and flight fares
* Incorrect destination locations

### RFM Segmentation
The segmentation was based on three key metrics:

1. **Recency:** Days since last booking
2. **Frequency:** Number of total bookings per user
3. **Monetary Value:** Total booking value per user
4. 
Each metric was scored on a scale of 1-5, resulting in 125 possible RFM combinations that were consolidated into 7 actionable segments.

### Identified Segments
1. **VIP Voyagers** (RFM: 4-5, 4-5, 4-5): Frequent, high-spending loyalists
2. **Adventure Scouts** (RFM: 3-5, 3-5, 1-3): Budget-conscious experience seekers
3. **Jet-Set Newbies** (RFM: 4-5, 1-3, 4-5): High-value first-time users
4. **Wandering Regulars** (RFM: 2-3, 3-4, 2-4): Slipping away, historically regular users
5. **Almost Alumnis** (RFM: 1-2, 1-5, 4-5): High-value users at churn risk
6. **Fading Explorers** (RFM: 2-3, 1-3, 1-2): Declining activity, reduced bookings
7. **Sleeping Trekkers** (RFM: 1, 1-3, 1-3): Dormant, rare bookings, minimal spend

## Key Findings

### Segment Distribution
* VIP Voyagers: 14% of users
* Adventure Scouts: 11.5% of users
* Jet-Set Newbies: 8.9% of users
* Wandering Regulars: 16.6% of users
* Almost Alumnis: 17.5% of users
* Fading Explorers: 11.6% of users
* Sleeping Trekkers: 20.1% of users

### Revenue Impact
* VIP Voyagers: 28% of revenue
* Wandering Regulars: 24.7% of revenue
* Almost Alumnis: 12.8% of revenue
* Jet-Set Newbies: 13% of revenue
* Adventure Scouts: 8% of revenue
* Fading Explorers: 5.2% of revenue
* Sleeping Trekkers: 3.6% of revenue

### Strategic Recommendations
1. **Prioritize Retention Efforts:** Focus on retaining Wandering Regulars and Almost Alumnis through personalized offers and targeted interventions.
2. **Maximize VIP Value:** Implement the Elite Key program for VIP Voyagers to reinforce their loyalty and increase their lifetime value.
3. **Rethink Discount Strategy:** Evaluate the effectiveness of current discount practices and explore alternative strategies to reduce the gap between gross and net revenue.
4. **Reactivate Lapsed Users:** Develop re-engagement campaigns for Fading Explorers and Sleeping Trekkers to win back lost customers.

### Implementation Plan
The proposed implementation follows a phased approach:

* Phase 1: Launch for VIP Voyagers and Jet-Set Newbies
* Phase 2: Expand to Wandering Regulars and Almost Alumnis
* Phase 3: Roll out to all remaining segments

## Tableau Visualization
The Tableau dashboard is available on my Tableau Public.

## Contributors
Guido Greger

---
## Acknowledgments
* TravelTide for providing the dataset
* Elena for the initial perk proposals that were refined in this project
---
*Note: This project is based on a fictional company and dataset created for educational purposes.*
