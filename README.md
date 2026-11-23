# Smart India Hackathon Workshop
# Date:23/11/2026
## Reference Number:26003316
## Name:Thilack.R

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description

## Proposed Solution

Multiple intermediaries between farmers and buyers can reduce producer price realization and increase consumer prices. The brief calls for a digital marketplace connecting farmers/FPOs with consumers and bulk buyers, logistics support, and AI-based demand forecasting and route optimization.

## Workflow – KisanSetu Direct

    *Farmers register and upload crop name, quantity, quality, harvest date, and location.
    *Buyers (customers, retailers, hotels, and institutions) browse crops or post their requirements.
    *The system matches farmers and buyers based on crop type, quantity, quality, location, and freshness.
    *Produce from different farmers is combined to fulfil large buyer orders.
    *Farmers check the price, transport cost, and minimum price before accepting or rejecting orders.
    *FPO centres collect the produce and arrange transportation based on distance and vehicle capacity.
    *Buyers and farmers track order status, delivery, and payment.
    *The system predicts future crop demand using previous sales and seasonal data.

## How It Addresses the Problem

1. Connects farmers directly with buyers and reduces middlemen.
2. Combines small quantities from different farmers to fulfil large orders.
3. Shows clear crop prices, transport costs, and platform fees.
4. Helps farmers know buyer demand before harvesting and reduces unsold crops.
5. Combines deliveries to reduce transportation costs and food wastage.

## Innovation and Uniqueness

1. Matches crops based on harvest dates and freshness.
2. Combines produce from small farmers through FPO centres.
3. Suggests suitable buyers and delivery routes based on quantity, distance, quality, and vehicle capacity.
4. Allows farmers to set their own minimum selling price.
5. Provides a simple mobile app with local-language support.
6. Gives priority to crops that may spoil soon to reduce food waste.

## Technical Approach

## Proposed Technology Stack
        1. Frontend: React and TypeScript to create a simple, responsive mobile-friendly website.
        2. Backend: Python FastAPI to handle user requests and platform operations.
        3. Database: PostgreSQL with PostGIS to store crop details, buyer information, orders, and location data.
        4. Demand Forecasting: Python, Pandas, and Scikit-learn to predict future crop demand using previous sales and seasonal data.
        5. Route Planning: Google OR-Tools to plan delivery routes based on vehicle capacity, distance, and delivery time.
        6. User Authentication: Secure login with separate access for farmers, buyers, FPOs, and delivery teams.
        7. Notifications: SMS, email, and mobile notifications for order updates and important alerts.
        8. Deployment & Security: Docker for deployment, HTTPS protection, database backups, and system monitoring.

## Architecture Diagram

  <img width="1234" height="1275" alt="image" src="https://github.com/user-attachments/assets/b47cc63d-2824-474d-ac9f-88ef63f48088" />

## Implementation Process
    1. Design the database for farmers, buyers, crops, orders, and payments.
    2. Develop registration, crop listing, search, and filter features.
    3. Implement order confirmation, stock management, and tracking.
    4. Add order grouping, delivery route planning, and demand forecasting.
    5. Test the system with an FPO and buyers, then evaluate the results.

## Order and Logistics sequence 

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/787e4700-5f78-44e9-ab07-ec9d6e01bb43" />

## Feasibility and Viability

## 1. Analysis of the Feasibility of the Idea**

1. Technical Feasibility: Can be developed using React, Python FastAPI, and PostgreSQL.
2. Economic Feasibility: Reduces transportation expenses and intermediary costs.
3. Operational Feasibility: Provides simple crop listing, order management, and delivery tracking.
4. Market Feasibility: Connects farmers with consumers, retailers, hotels, and institutions.
5. Scalability: Can expand to more farmers, buyers, FPOs, and regions.

## 2. Potential Challenges and Risks**

1. Farmer Awareness: Some farmers may have difficulty using the digital platform.
2. Internet Connectivity: Poor network connections may affect platform access.
3. Price Fluctuations: Changes in market prices may affect farmer and buyer decisions.
4. Transportation Issues: Delays and vehicle shortages may affect timely delivery.
5. Product Quality: Maintaining crop quality and freshness during transportation can be challenging.

## 3. Strategies for Overcoming These Challenges**

*Farmer Awareness: Provide simple training and local-language support.
*Internet Connectivity: Develop a low-data and mobile-friendly application.
*Price Fluctuations: Provide transparent pricing and minimum-price alerts.
*Transportation Issues: Use smart route planning and nearby collection centres.
*Product Quality: Follow proper quality checks and freshness-based delivery planning.

## Impact and Benefits

## Potential Impact on the Target Audience
1. Farmers: Helps farmers sell their crops directly to buyers and earn better income.
2. Consumers: Provides fresh produce with transparent pricing.
3. Retailers and Hotels: Makes it easier to find crops in the required quantity and quality.
4. FPOs: Helps manage crop collection, bulk orders, and transportation.
5. Local Communities: Creates better market opportunities and supports local farmers.
## Benefits of the Solution
1. Social Benefits: Builds direct connections between farmers and buyers and supports farming communities.
2. Economic Benefits: Reduces middlemen costs, improves farmer income, and lowers transportation expenses.
3. Environmental Benefits: Reduces food wastage and unnecessary transportation through better delivery planning.
4. Agricultural Benefits: Helps farmers understand market demand and plan their harvest.
5. Business Benefits: Provides buyers with reliable access to produce based on quantity, quality, and price.

## Research and References

    * SFAC – Small Farmers’ Agribusiness Consortium: https://sfacindia.com/
    * ONDC – Open Network for Digital Commerce: https://ondc.org/
    * AGMARKNET – Agricultural Marketing Information Network: https://agmarknet.gov.in/
    * AIF – Agriculture Infrastructure Fund: https://agriinfra.dac.gov.in/
    * NABARD – National Bank for Agriculture and Rural Development: https://www.nabard.org/
    * NCCD – National Centre for Cold-chain Development: https://nccd.gov.in/
    * DA&FW – Department of Agriculture and Farmers Welfare: https://agriwelfare.gov.in/
    * MoFPI – Ministry of Food Processing Industries: https://www.mofpi.gov.in/
