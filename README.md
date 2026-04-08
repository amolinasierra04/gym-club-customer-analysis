# Gym Club Customer Analysis

## Project Overview
This project analyzes gym membership data to understand customer profiles, usage behavior, and service adoption patterns. The goal is to generate actionable insights for neighborhood sports clubs that want to improve their offer, customer experience, and commercial strategy.

## Business Objective
Identify the main customer segments in a gym and detect opportunities to improve service usage, increase engagement, and support decision-making.

## Key Business Questions
- What is the profile of the average gym member?
- Are there relevant differences between Standard and Premium members?
- Which customers are more likely to attend group lessons?
- What type of members use personal training or sauna services?
- Are there clear customer segments based on behavior and service usage?

## Dataset
- Source: gym_membership.csv
- Number of records: 1000
- Main variables: age, gender, membership type, weekly visits, average session time, group lessons, personal training, sauna use

## Tools Used
- SQL (SQLite)
- Power BI
- GitHub

## Project Structure
- `data/`: raw data
- `sql/`: SQL queries by analysis stage
- `powerbi/`: dashboard file
- `visuals/`: exported dashboard images
- `docs/`: methodology and conclusions

## Methodology
1. Data overview and quality check
2. Data cleaning and preparation
3. Customer profile analysis
4. Usage pattern analysis
5. Service adoption analysis
6. Customer segmentation
7. Business recommendations

## Key Insights
1. Membership type strongly influences engagement  
Premium members tend to visit the gym more frequently and show higher usage of additional services such as personal training and sauna. This suggests that higher-tier memberships are associated with more active and valuable customers.

2. Service adoption is concentrated in specific customer groups  
Services like group lessons and personal training are not evenly used across all members. Instead, they are concentrated among certain profiles, indicating clear opportunities for targeted promotion.

3. Higher engagement is linked to multi-service usage  
Members who use multiple services (e.g., classes, personal training, drinks) tend to visit the gym more often and spend more time per session. This highlights the role of service bundling in increasing customer engagement.

4. A large portion of members show low to moderate activity levels  
Despite having active users, a significant share of members visit the gym relatively few times per week. This indicates untapped potential to increase usage and improve customer retention.

5. Group lessons act as an entry point for engagement  
Members attending group lessons show distinct behavioral patterns, often linked to higher consistency in attendance. This suggests that group activities can play a key role in building habits and loyalty.

6. Customer base is diverse and requires segmentation  
The variability in behavior, service usage, and visit frequency confirms that a “one-size-fits-all” strategy is inefficient. Clubs need to segment their customers to optimize offerings and communication.

## Dashboard Preview
The Power BI dashboard provides an interactive overview of gym member behavior and service usage.

Main components include:
- Customer profile overview (age, gender, membership type)
- Usage patterns (visits per week, time spent in gym)
- Service adoption (group lessons, personal training, sauna, drinks)
- Segmentation views to identify different customer types

The dashboard is designed for non-technical stakeholders, allowing sports club managers to quickly explore key metrics and identify actionable insights.

## Business Recommendations
1. Drive Premium Membership Upgrades  
Given the higher engagement levels of Premium members, clubs should actively promote upgrades from Standard plans. This can be achieved through:
- Free trial periods for Premium features
- Bundled offers including classes or sauna access
- Clear communication of added value

---

2. Increase Service Adoption Through Targeted Offers  
Since services are used by specific customer groups, clubs should:
- Identify profiles most likely to adopt each service
- Design targeted campaigns (e.g., personal training for frequent users)
- Offer introductory sessions to reduce entry barriers

---

3. Use Group Lessons as a Retention Tool  
Group classes can help build consistent habits. Clubs should:
- Expand or optimize class schedules
- Promote classes to low-frequency users
- Encourage social engagement within classes

---

4. Activate Low-Engagement Members  
A significant portion of members shows low activity. To address this:
- Launch re-engagement campaigns (emails, promotions)
- Offer incentives for increased attendance
- Track inactive users and intervene early

---

5. Bundle Services to Increase Customer Value  
Members using multiple services show higher engagement. Clubs can:
- Create service packages (e.g., classes + drinks + sauna)
- Offer discounts for combined services
- Promote “all-in-one” experiences

---

6. Adopt a Data-Driven Management Approach  
Even small clubs can benefit from tracking:
- Visit frequency
- Service usage
- Customer segments

Using data regularly allows clubs to make better decisions, optimize resources, and improve customer experience.

## Limitations
- No revenue or churn data available
- No information on customer tenure
- Dataset may not fully represent all age groups in real gyms

## How to Reproduce
1. Import the CSV into SQLite
2. Run the SQL scripts in order
3. Open the Power BI dashboard
