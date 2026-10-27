# Smart India Hackathon Workshop
# Date: 27/10/2026
## Reference Number: DHATSHINI P
## Name:26010141

# Smart India Hackathon Workshop – 27/10/2026

**Reference Number:** DHATSHINI P  
**Register Number:** 26010141

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers' earnings and increase consumer prices.

## Problem Creator's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

# 1. Proposed Solution

**Project Name: CropWise – Smart Crop Demand and Distribution System**

CropWise is a digital platform designed to help farmers make better selling decisions by predicting crop demand and coordinating the distribution of harvested produce.

Instead of focusing only on connecting farmers with buyers, CropWise collects advance demand information from retailers, vegetable shops, hotels, and bulk buyers. It compares this information with the available produce from nearby farmers and suggests suitable selling and distribution plans.

### How it addresses the problem

1. **Advance Demand Registration:** Retailers and bulk buyers enter the types and quantities of crops they expect to purchase.
2. **Demand Matching:** The system compares buyer requirements with the produce available from farmers.
3. **Farmer Grouping:** Small farmers with suitable crops can coordinate their supply to meet larger orders.
4. **Price and Cost Estimation:** Farmers can compare buyer offers and estimate their earnings after transportation and other expenses.
5. **Smart Distribution:** The system groups nearby deliveries and suggests efficient routes.
6. **Surplus Alerts:** Farmers receive alerts when the expected supply is greater than the registered demand, helping them explore alternative buyers before the produce goes unsold.

### Innovation and Uniqueness

The main feature is the **Advance Demand Matching System**. It uses buyer demand information to help coordinate what is available from farmers with what buyers need.

By combining advance demand registration, surplus alerts, cost estimation, and shared distribution, CropWise aims to reduce avoidable intermediaries and supply-chain inefficiencies.

# 2. Technical Approach

### Technologies to be used

- **Front end:** HTML, CSS, and JavaScript.
- **Back end:** Python with Flask.
- **Database:** SQLite for the initial prototype.
- **Data analysis:** Python and Pandas.
- **AI enhancement:** Scikit-learn for demand forecasting when sufficient historical data is available.
- **Route planning:** OpenStreetMap and a suitable routing service.

### Methodology

1. Buyers register the crops, quantities, and expected purchase dates they require.
2. Farmers register their available crops, quantities, locations, and expected prices.
3. The system compares buyer demand with farmer supply.
4. Suitable matches are ranked based on crop type, quantity, location, and delivery date.
5. Farmers receive information about matching demand and possible surplus.
6. The system estimates selling revenue and delivery expenses.
7. Compatible deliveries are grouped, and suitable routes are suggested.
8. Orders and delivery statuses are recorded in the database.

### Technical Approach Flowchart

Buyer Demand Registration  
↓  
Farmer Crop and Supply Registration  
↓  
Demand and Supply Matching  
↓  
Price and Cost Estimation  
↓  
Surplus Alerts and Shared Delivery Planning  
↓  
Order Confirmation and Distribution  
↓  
Reduced Waste and Better Market Access

# 3. Feasibility and Viability

CropWise can initially be developed as a student-level web application using Python, Flask, HTML, CSS, JavaScript, and SQLite. A basic version does not require advanced AI; it can match crop names, quantities, locations, and dates using simple rules.

### Potential challenges

- Buyers may provide inaccurate demand estimates.
- Market prices may change quickly.
- Some farmers may have limited internet access.
- Demand forecasting requires reliable historical data.
- Delivery schedules may change due to weather or transport issues.

### Strategies to overcome these challenges

- Allow buyers to update or confirm their requirements.
- Show the date and source of market-price information.
- Provide a simple mobile-friendly interface and regional-language support.
- Begin with rule-based matching and introduce machine learning only when enough data is available.
- Provide alternative buyer suggestions when demand or delivery plans change.

The system is technically feasible as a prototype. Its effectiveness and commercial viability would need to be tested with farmers and buyers.

# 4. Impact and Benefits

### Economic impact
- Helps farmers identify potential buyers before harvesting or transporting produce.
- Provides better visibility of buyer offers and estimated selling costs.
- May improve farmers' net earnings by reducing avoidable distribution expenses.
- May help consumers access produce at more competitive prices.

### Social impact
- Supports small farmers and farmer groups.
- Improves coordination between rural producers and local businesses.
- Makes market information easier to access.

### Environmental impact
- May reduce food waste by identifying potential surplus earlier.
- May reduce unnecessary transport through coordinated deliveries.
- May improve the distribution of available agricultural produce.

These benefits are expected outcomes and must be verified through prototype testing and real-world trials.

# 5. Research and References

1. Smart India Hackathon – Problem Statement SIH 26033, provided in the college workshop.
2. Ministry of Agriculture and Farmers Welfare, Government of India: https://agriwelfare.gov.in/
3. National Agriculture Market (e-NAM): https://www.enam.gov.in/
4. Flask documentation: https://flask.palletsprojects.com/
5. Scikit-learn documentation: https://scikit-learn.org/
6. OpenStreetMap: https://www.openstreetmap.org/
