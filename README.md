
# 🍽️ Zomato Sales Analysis Dashboard  

## 📌 Introduction  
This project presents an analytical dashboard built in **Tableau Public** to evaluate Zomato’s sales performance over time, across cuisines, cities, restaurants, and customer behavior patterns. The goal is to provide actionable insights into operational efficiency, customer demand patterns, and partner restaurant performance.  

---

## 📊 Executive Summary  
Zomato’s sales data demonstrates **exceptional operational reliability and consistent performance**:  

- **Total Orders:** 148,541  
- **Completion Rate:** 100%  
- **Cancellation Rate:** 0.001% (only 2 problematic orders)  
- **Problematic Orders:** 2  

### Key Insights:  
- **Growth vs Decline:** A strong growth phase from 2017–2018 peaked (~400M sales in Jan 2018), followed by a decline in 2019–2020, with the steepest drop in 2020 (~150M).  
- **Weekday vs Weekend Trends:** Friday shows the highest sales (~260M) – a **“Friday Peak”** effect. Surprisingly, sales decline during weekends, creating a **“Weekend Paradox”**.  
- **Cuisine Trends:** Sweets & Tandoor generated the highest revenue (442K), followed by Biryani & Bakery (322K).  
- **City Insights:** Tirupati leads with the highest revenue (174K), followed by Sirsi and Siwan.  
- **Restaurant Ratings:** Highest revenues are clustered between **3.2 and 4.8 ratings**. Some restaurants with **5-star ratings** underperform in sales.  

---

## 💡 Recommendations  
1. **Support 5-Star Restaurants with Low Sales**  
   - Promote them via targeted marketing campaigns, discounts, or visibility boosts.  
   - Provide business consulting to balance pricing and demand.  

2. **Leverage Mid-Rated High-Revenue Restaurants (3.2–4.8)**  
   - Identify best practices and replicate across partners.  
   - Offer loyalty programs to strengthen customer retention.  

3. **Maintain Operational Excellence**  
   - With near-perfect completion, ensure strong customer support continues.  
   - Use predictive monitoring to prevent cancellations or failed deliveries.  

---

## 📈 Visualizations Used  
- **KPI Cards** – Total Orders, Completion Rate, Cancellation Rate, Problematic Orders  
- **Line Chart** – Sales Over Time (growth and decline phases)  
- **Bar Chart** – Sales by Day of the Week (Friday Peak vs Weekend Paradox)  
- **Bar Chart** – Revenue by Cuisine Type  
- **Bar Chart** – Revenue by City (Top 10)  
- **Scatter Plot** – Revenue vs Rating (relationship between quality and sales)  

---

## 🌐 Interactive Dashboard  
🔗 **View the live Tableau dashboard here:**  
[Zomato Sales Analysis – Tableau Public](https://public.tableau.com/app/profile/eunice.mukangarambe/viz/zomatoanalysis_17562908135280/Dashboard2)

📸 **Preview Screenshot:**  
[Dashboard Preview]((<img width="793" height="450" alt="Screenshots zomato dashboard" src="https://github.com/user-attachments/assets/e7bbc2a5-aaaa-4def-b676-e56364c56fe7" /)
 
  

---

## 🧩 Research Plan & Decomposition  

### Research Area  
Understanding **customer demand and operational performance** in Zomato’s food delivery business.  

### Research Questions  
1. How reliable is Zomato’s order fulfillment process?  
2. What are the sales trends over time (growth, peak, decline)?  
3. Do sales vary by weekday/weekend, and why is there a “Weekend Paradox”?  
4. Which cuisines and cities generate the most revenue?  
5. How do restaurant ratings correlate with revenue?  
6. Where should Zomato focus to increase both customer satisfaction and partner performance?  

### Hypotheses  
- Orders are completed at a very high success rate (>99%).  
- Sales peak towards the end of the workweek (Friday celebrations).  
- Despite high ratings, some restaurants underperform in sales due to pricing, location, or limited visibility.  
- Certain cuisines dominate revenue contribution (e.g., sweets, tandoor, biryani).  

### Data Preparation Steps  
1. **Cleaning** – Remove null/duplicate records, validate order counts.  
2. **Handling Negative Values** – Identify cancellations or refunds (e.g., -1 values).  
3. **Derived Fields** – Create calculated fields for cancellation rate, problematic orders.  
4. **Aggregation** – Summarize revenue by date, cuisine, city, and restaurant.  
5. **Validation** – Ensure KPI totals match across sheets.  

### Scope & Exclusions  
- Focus is on **customer demand patterns and partner performance**.  
- Product-level details (e.g., menu items, pricing strategy) are out of scope.  
- No predictive modeling; only descriptive analytics provided.  

---
