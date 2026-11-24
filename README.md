# Smart India Hackathon Workshop
## Date: 24-11-2026
## Reference Number: 26004900
## Name: DIYA R

## Problem Title
SIH 26033:  Multiple intermediaries reduce farmers' earnings and increase consumer prices.

Problem creator's organization:  Ministry of Consumer Affairs, Food & Public Distribution

Theme:  Agriculture, FoodTech & Rural Development

## Problem Description
Expected solution: a digital marketplace that connects farmers and FPOs directly with consumers and bulk buyers, provides logistics support, and uses AI for demand forecasting and route optimization.
Expected benefits: better prices for farmers, lower prices for consumers, and reduced supply chain inefficiencies.
Proposed Solution
KisanConnect: an AI-powered direct farm-to-buyer marketplace
### 1. Detailed explanation
• A mobile and web platform where farmers and FPOs list produce, including pre-harvest listings.

• Households, retailers, hotels and bulk buyers order directly.

• Logistics support through village collection hubs, grading and pooled delivery.

• Payments are held in escrow and released to the farmer on delivery.

• The app is available in regional languages, with voice input and a WhatsApp/SMS option.

### 2. How it addresses the problem
• It removes the trader, commission agent and wholesaler layers, so farmers keep more of the price.

• Shorter chains and pooled delivery lower the consumer price.

• Forecasting reduces unsold stock and post-harvest loss.

### 3. Innovation and uniqueness
• AI demand forecasting tells farmers what to grow and sell.

• An AI fair-price suggestion based on mandi rates, so farmers are not underpaid.

• AI route optimization pools orders into cheaper deliveries.

• Photo-based quality grading and QR traceability from farm to buyer.

• FPO-first onboarding and a vernacular voice UI for low digital literacy.

## Technical Approach
### 1. Technologies to be used
• Frontend: Flutter or React Native, plus a WhatsApp bot.

• Backend: Django or Node.js REST APIs, PostgreSQL, Redis.

• AI/ML: Python, Prophet/LSTM/XGBoost for demand and price forecasting, Google OR-Tools for route optimization, a CNN for quality grading.

• Integrations: Google Maps or OpenStreetMap, UPI/Razorpay, Agmarknet mandi prices, weather API.

• Cloud: AWS or Azure.

### 2. Methodology and process
1.  Farmers list produce, and AI suggests a price and predicts demand.
2.  The buyer orders and pays into escrow.
3.  The route optimizer groups orders and assigns pickups and deliveries.
4.  Produce is graded at the hub and dispatched, and the farmer is paid on delivery.
5.  Order data feeds back into the models to improve forecasts.

<img width="2720" height="1000" alt="kisanconnect_system_flow" src="https://github.com/user-attachments/assets/48bc34a9-7a7a-4659-9a5b-01f268ba33e8" />

#### 1. Feasibility
• Technical: it uses mature tools and open data (Agmarknet, weather APIs, OpenStreetMap).

• Operational: FPOs already aggregate farmers, so the pilot starts with 2 to 3 FPOs and 5 to 10 crops in one district.

• Economic: revenue comes from a 2 to 5% commission, delivery fees, subscriptions and bulk-buyer analytics.

• Policy fit: aligns with e-NAM, Digital India and the PM-FPO scheme.
#### 2. Potential challenges and risks and Strategies to overcome them

<img width="682" height="355" alt="image" src="https://github.com/user-attachments/assets/d34e7248-8f53-4efd-a810-b8eb222e7c49" />

## Impact and Benefits:
### 1. Potential impact on the target audience
• Farmers: a larger share of the final price, assured buyers and price transparency.

• Consumers: fresher produce at lower prices, with traceability.

• FPOs and rural youth: new income from hub operations, grading and delivery jobs.

### 2. Benefits of the solution
• Economic: higher farmer income and lower consumer cost.

• Social: rural employment, fair trade and trust in the supply chain.

• Environmental: less food waste and fewer delivery kilometres through route optimization.

### Price comparison:

<img width="625" height="232" alt="image" src="https://github.com/user-attachments/assets/a06b66db-d119-4e28-9914-f1315fe4770a" />


## Research and References:

• Agmarknet, for mandi prices: agmarknet.gov.in

• e-NAM, the national agriculture market: enam.gov.in

• PM-FPO scheme, from the Ministry of Agriculture & Farmers Welfare: agriwelfare.gov.in

• Google OR-Tools, for vehicle routing: developers.google.com/optimization

• FAO and NABARD reports on food loss and FPO value chains, for farmer price-share and post-harvest loss statistics.
