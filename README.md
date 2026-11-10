# 🛵 Rapido Bike Taxi – Business Performance & Customer Analytics | Power BI


---

## 📌 Project Overview

This project focuses on analyzing Rapido's ride-booking operations using **Microsoft Power BI**, transforming raw business data into meaningful insights across revenue generation, vehicle performance, customer behaviour, payment preferences, and operational efficiency.

The objective is to evaluate business performance, identify customer engagement patterns, understand revenue distribution, and uncover opportunities for improving operational effectiveness and customer retention.

The interactive Power BI report provides a comprehensive analytical view of the business through the following areas:

- **Business Overview:** Overall booking performance, revenue, ride completion, and operational KPIs.
- **Vehicle Analysis:** Comparison of Bike and Auto services based on revenue, customer count, completed bookings, distance, and ride duration.
- **Revenue Analysis:** Revenue contribution, booking value trends, and vehicle-wise financial performance.
- **Customer Analysis:** Customer segmentation, high-value customers, payment preferences, and cancellation behaviour.

The project demonstrates how business intelligence and data visualization can support data-driven decision-making in the urban mobility and ride-hailing industry.

---

## 📊 Dashboard Preview

### 1. Business Overview Dashboard

Provides a consolidated view of overall business performance through key metrics, booking trends, revenue analysis, geographic activity, and customer and driver satisfaction.



### 2. Vehicle Analysis Dashboard

Evaluates vehicle-wise performance to understand revenue contribution, completed bookings, customer distribution, trip distance, and operational trends across Bike and Auto services.


 ### 3. Customer Analytics: 
 
 Analyses customer segmentation, booking behaviour, payment preferences, cancellation patterns, and customer-level engagement to identify retention opportunities.



### 4. Revenue Analytics: 

Evaluates revenue contribution by vehicle type, payment method, and customer to identify key revenue drivers and growth opportunities.

---

## 🎯 Business Objectives

The primary objectives of this analysis are:

1. Evaluate overall booking volume and revenue performance.
2. Identify the highest revenue-generating vehicle category.
3. Analyze booking trends and daily revenue fluctuations.
4. Understand completed, cancelled, and incomplete ride patterns.
5. Evaluate customer payment preferences and transaction behaviour.
6. Identify high-value customers and analyze their revenue contribution.
7. Understand customer segmentation and retention opportunities.
8. Analyze the financial impact of customer cancellations.
9. Evaluate customer and driver satisfaction.
10. Develop actionable recommendations to improve business performance.

---

## 📈 Key Performance Indicators (KPIs)

The dashboard tracks the following business metrics:

| KPI | Reported Value |
|---|---:|
| Total Booking Value | 211K |
| Total Bookings | 1M |
| Void Bookings | 173K |
| Total Distance | 20K |
| Total Time | 48K minutes |
| Total Customers | 1,398 |
| Completed Bookings | 1,225 |
| Total Revenue | 210,972 |
| Completion Rate | 82% |
| Average Revenue per Completed Booking | 140 |
| Driver Rating | 4.00 / 5 |
| Customer Rating | 4.01 / 5 |

*Note: KPI values are reproduced from the dashboard. Some figures require validation against the underlying dataset, aggregation logic, and DAX measures.*

---

# 🔍 Detailed Business Insights & Findings

## 1. Revenue Contribution by Vehicle Type

The vehicle-wise revenue analysis highlights a significant difference between Bike and Auto services.

| Vehicle Type | Revenue | Revenue Contribution |
|---|---:|---:|
| Bike | 148,710 | 70.5% |
| Auto | 62,262 | 29.5% |
| **Total** | **210,972** | **100%** |

**Key Insights:**

- Bike services contribute approximately **70.5% of total revenue**, making them the primary revenue-generating category.
- Auto services account for approximately 29.5% of total revenue.
- Bike revenue is approximately 2.39 times higher than Auto revenue.
- The business demonstrates considerable dependence on its Bike segment for revenue generation.

**Business Recommendations:**

- Prioritize Bike driver availability during peak demand periods.
- Focus on driver retention and service reliability within the Bike segment.
- Investigate the factors contributing to higher Bike revenue.
- Introduce targeted promotional campaigns to increase Auto bookings.
- Evaluate vehicle-wise profitability instead of relying exclusively on revenue contribution.

## 2. Booking Trends & Demand Analysis

The monthly booking trend visualisation highlights variations in daily booking volumes.

**Key Insights:**

- Daily booking volumes fluctuate approximately between 35 and 60 bookings.
- The highest observed booking volume is approximately 60.
- Several days record more than 50 bookings, indicating stronger demand periods.
- Lower booking volumes of approximately 35 suggest opportunities to investigate weaker demand periods.
- Demand fluctuations may be influenced by weekday patterns, weather conditions, local events, and commuting behaviour.

**Business Recommendations:**

- Identify recurring high-demand days.
- Optimize driver allocation using historical booking patterns.
- Introduce targeted promotional campaigns during low-demand periods.
- Compare weekday and weekend booking behaviour.
- Incorporate hourly booking trends for more effective demand forecasting.

## 3. Booking Value & Daily Revenue Analysis

The Booking Value by Day visualisation provides insights into daily revenue fluctuations.

**Key Insights:**

- Daily booking value varies considerably throughout the reporting period.
- Several days record booking values around 8K, while certain days fall close to 5K.
- Revenue fluctuations may be associated with changes in booking volume, average fare, or completed rides.
- Monitoring revenue alongside completed bookings can help distinguish volume-driven growth from changes in transaction value.

**Business Recommendations:**

- Monitor daily revenue against completed booking volumes.
- Investigate days with unusually low revenue.
- Develop revenue forecasting models using historical trends.
- Track average fare per completed ride.
- Identify opportunities to improve revenue consistency.

## 4. Payment Method Analysis

Customer payment activity reveals the following distribution:

| Payment Method | Customer Count | Share of Displayed Count |
|---|---:|---:|
| UPI | 712 | 48.7% |
| Wallet | 380 | 26.0% |
| Cash | 290 | 19.8% |
| Card | 79 | 5.4% |
| **Total** | **1,461** | **100%** |

**Key Insights:**

- UPI is the most frequently used payment method, representing approximately 48.7% of the displayed payment-method count.
- Wallet payments account for approximately 26%.
- Cash payments contribute approximately 19.8%.
- Card payments represent the smallest share at approximately 5.4%.
- The distribution indicates a strong preference for digital payment methods, particularly UPI.

**Business Recommendations:**

- Prioritize a seamless UPI payment experience.
- Monitor payment failures and transaction completion rates.
- Improve digital wallet integration and convenience.
- Explore targeted incentives to encourage digital payments.
- Investigate opportunities to improve card payment adoption.

## 5. Customer Cancellation Analysis

The dashboard highlights the operational and financial implications of customer cancellations.

| Metric | Value |
|---|---:|
| Customer Cancelled Count | 96 |
| Customer Cancelled Revenue Impact | 13.46K |
| Total Void Bookings | 173K |

**Key Insights:**

- Customer cancellations represent a measurable source of potential revenue loss.
- The reported cancelled revenue impact of 13.46K highlights the financial importance of successful booking fulfilment.
- Cancellation behaviour can affect driver utilization, operational efficiency, and customer satisfaction.
- Understanding cancellation reasons is essential to reducing avoidable unsuccessful bookings.

**Business Recommendations:**

- Analyze cancellation reasons and frequency.
- Identify whether cancellations are concentrated among particular vehicle categories.
- Investigate driver availability and customer waiting times.
- Monitor customer cancellation patterns.
- Introduce targeted interventions to improve booking fulfilment.

## 6. High-Value Customer Analysis

The customer-level booking analysis identifies the highest-value customers based on their booking value.

| Customer ID | Booking Value |
|---|---:|
| CUST_3068 | 545 |
| CUST_7658 | 523 |
| CUST_9317 | 506 |
| CUST_2874 | 462 |
| CUST_4770 | 452 |

**Key Insights:**

- The top three customers collectively generate 1,574 in booking value.
- Customer-level revenue analysis helps identify users with relatively high booking contributions.
- Understanding the behaviour of high-value customers can support more effective retention strategies.
- Customer-level analysis provides an opportunity to move beyond overall revenue figures and understand individual customer contributions.

**Business Recommendations:**

- Introduce personalized offers for high-value customers.
- Develop loyalty incentives to encourage repeat bookings.
- Monitor booking frequency and average transaction value.
- Identify common characteristics and booking patterns among high-value users.
- Build customer retention campaigns based on historical booking behaviour.

## 7. Customer Segmentation & Retention Analysis

The dashboard categorizes customers into three behavioural segments.

| Customer Segment | Count |
|---|---:|
| First-Time Customers | 1,000 |
| Return Customers | 80 |
| Regular Customers | 11 |

**Key Insights:**

- First-time customers represent the largest displayed segment.
- Return and regular customers represent comparatively smaller groups.
- The segmentation highlights an opportunity to convert first-time users into repeat customers.
- Improving customer retention can support more consistent booking activity and long-term business growth.

**Business Recommendations:**

- Introduce first-to-second ride incentives.
- Develop customer loyalty and reward programmes.
- Use personalized engagement campaigns to encourage repeat bookings.
- Analyze the time interval between a customer's first and subsequent rides.
- Track customer retention and repeat booking rates over time.

## 8. Vehicle-Wise Operational Performance

The Vehicle Analysis dashboard provides a detailed comparison of Bike and Auto services.

| Performance Metric | Auto | Bike |
|---|---:|---:|
| Customer Count | 441 | 1,003 |
| Revenue | 62,262 | 148,710 |
| Completed Bookings | 353 | 872 |

**Key Findings:**

- Bike services account for approximately 71.7% of the displayed vehicle-wise customer count.
- Bike services contribute approximately 71.2% of completed bookings.
- Auto services account for approximately 28.8% of completed bookings.
- Bike services outperform Auto services across all three displayed metrics.

### Average Revenue per Completed Booking

An additional calculation provides a more meaningful comparison of revenue efficiency.

| Vehicle Type | Revenue per Completed Booking |
|---|---:|
| Bike | 170.54 |
| Auto | 176.38 |

**Important Observation:**

Although Bike services generate significantly higher total revenue, Auto services have a slightly higher average revenue per completed booking.

This suggests that Bike revenue dominance is primarily associated with its higher completed-booking volume rather than a higher average revenue per completed ride.

This distinction is important because total revenue and revenue efficiency measure different aspects of business performance.

## 9. Geographic Performance – Bengaluru

The Overview Dashboard identifies Bengaluru as a prominent location for pickup and drop activity, with approximately 1K displayed for each.

**Key Insights:**

- Bengaluru demonstrates substantial pickup and drop activity.
- Geographic demand analysis can help identify high-activity locations.
- Understanding frequently used pickup and drop locations can support better driver positioning.
- Location-based analysis can help improve service coverage and resource allocation.

**Business Recommendations:**

- Identify high-demand pickup and drop zones.
- Optimize driver positioning around frequently used locations.
- Analyze booking patterns across different city zones.
- Explore opportunities to improve service coverage in underserved areas.

## 10. Customer & Driver Satisfaction Analysis

The dashboard tracks customer and driver ratings to evaluate service quality.

| Satisfaction Metric | Rating |
|---|---:|
| Driver Rating | 4.00 / 5 |
| Customer Rating | 4.01 / 5 |

**Key Insights:**

- Both customer and driver ratings are approximately 4 out of 5.
- The difference between the two ratings is minimal.
- Maintaining service quality is important for customer retention and driver engagement.

**Business Recommendations:**

- Investigate low-rated rides and recurring complaints.
- Identify factors influencing customer and driver satisfaction.
- Introduce driver quality improvement initiatives.
- Monitor satisfaction trends over time.
- Use feedback analysis to identify service improvement opportunities.

---

# 💼 Strategic Business Recommendations

Based on the combined analysis of booking performance, revenue, customer behaviour, and vehicle operations, the following strategic opportunities emerge.

| Business Area | Recommended Strategy | Expected Business Benefit |
|---|---|---|
| Bike Operations | Optimize driver allocation and availability | Higher ride capacity |
| Auto Operations | Introduce targeted promotions | Increased Auto bookings |
| Revenue Management | Monitor daily revenue fluctuations | Better revenue planning |
| Customer Retention | Convert first-time users into repeat customers | Improved customer lifetime value |
| Cancellation Management | Investigate cancellation patterns | Better booking fulfilment |
| Digital Payments | Strengthen UPI payment reliability | Improved payment experience |
| Customer Engagement | Develop personalized loyalty programmes | Higher repeat booking frequency |
| Geographic Optimization | Focus on high-demand pickup zones | Improved driver utilization |
| Customer Satisfaction | Analyze low-rating rides | Better service quality |
| Demand Forecasting | Identify recurring booking patterns | Efficient resource allocation |

---

# 🧮 Data Validation & Analytical Observations

An important aspect of this project is validating reported metrics before drawing business conclusions.

During the analysis, several figures were identified for further validation against the source dataset and underlying DAX measures.

| Metric | Dashboard Value | Analytical Observation |
|---|---:|---|
| Total Bookings | 1M | Requires verification against underlying booking records |
| Void Bookings | 173K | Confirm whether this represents 173 or 173,000 |
| Completion Rate | 82% | 1,225 / 1,398 gives approximately 87.6%, assuming 1,398 is the relevant denominator |
| Average Revenue per Completed Booking | 140 | 210,972 / 1,225 gives approximately 172.22 |
| Payment Method Count | 1,461 | Exceeds the displayed customer count of 1,398; verify aggregation and possible multiple payments |
| Customer Segment Count | 1,091 | Does not reconcile with the displayed customer count of 1,398; investigate missing or excluded segments |
| Total Distance | 20K | Underlying distance unit requires confirmation |
| Total Time | 48K minutes | Confirm whether this includes all bookings or completed rides only |

These observations are not necessarily confirmed errors. Differences may arise from filter context, distinct-count versus transaction-count calculations, data granularity, excluded categories, or different reporting periods.

**Recommended validation checks:**

- Verify the underlying row count and distinct booking IDs.
- Review DAX measures and their filter context.
- Check whether customer counts use DISTINCTCOUNT or COUNT.
- Validate the calculation of completion and cancellation rates.
- Confirm whether revenue calculations include cancelled or incomplete rides.
- Standardize units and number formatting across all report pages.
- Reconcile customer segments and payment-method totals with the source data.

This validation process is important to ensure that dashboard metrics are accurate, consistent, and suitable for business decision-making.

---

# 🛠️ Tools & Technologies Used

| Tool / Technology | Application |
|---|---|
| Microsoft Power BI | Interactive dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and analytical measures |
| Data Visualization | Business performance reporting |
| Business Intelligence | Operational and revenue analysis |

### Technical Skills Demonstrated

- Interactive dashboard development
- Data cleaning and transformation
- KPI development and performance monitoring
- DAX-based calculations
- Revenue and operational analysis
- Customer segmentation
- Payment preference analysis
- Trend and comparative analysis
- Data storytelling
- Business insight generation
- Analytical problem-solving

---

# 📌 Overall Analytical Takeaways

The combined analysis of Rapido's business operations reveals several important findings:

1. **Revenue Concentration:** Bike services contribute approximately 70.5% of total booking value, making them the dominant revenue-generating category.

2. **Vehicle Performance:** Bike services lead in customer count and completed bookings, while Auto services generate slightly higher revenue per completed ride.

3. **Payment Preferences:** UPI is the most frequently used payment method, accounting for approximately 48.7% of the displayed payment-method count.

4. **Customer Retention:** The customer segmentation highlights an opportunity to convert first-time customers into repeat and regular users.

5. **Cancellation Impact:** Customer cancellations represent a measurable source of potential revenue loss and operational inefficiency.

6. **High-Value Customers:** Customer-level revenue analysis provides opportunities for targeted retention and personalized engagement.

7. **Demand Forecasting:** Daily booking and revenue fluctuations highlight the importance of effective demand forecasting and driver allocation.

8. **Customer Satisfaction:** Customer and driver ratings provide useful indicators for monitoring service quality.

9. **Geographic Optimization:** Pickup and drop analysis can support more effective driver positioning and service coverage.

10. **Data Quality:** Validating KPI calculations and aggregation logic is essential to ensuring reliable business intelligence reporting.

---

# 🏁 Conclusion

This project demonstrates how Microsoft Power BI can transform ride-booking data into actionable business intelligence across multiple dimensions of business performance.

By combining revenue analysis, vehicle-wise comparisons, customer segmentation, payment preferences, cancellation analysis, and operational performance, the dashboard provides a comprehensive view of the factors influencing a ride-hailing business.

The analysis identifies Bike services as the primary revenue contributor while highlighting opportunities to improve Auto utilization, strengthen customer retention, optimize digital payment experiences, reduce unsuccessful rides, and enhance operational efficiency.

More importantly, this project emphasizes that effective data analytics goes beyond creating visually appealing dashboards. It involves identifying meaningful patterns, validating metrics, interpreting business performance, and translating findings into practical recommendations.

**The ultimate objective is not just to visualize data, but to transform it into insights that support smarter, more informed, and data-driven business decisions.**

---

# 📂 Repository Structure

```text
Rapido-Power-BI-Analysis/
│
├── README.md
│
├── Dashboard/
│   ├── Rapido_Overview.png
│   ├── Rapido_Vehicle_Analysis.png
│   ├── Rapido_Customer_Analysis.png
│   └── Rapido_Revenue_Analysis.png
│
├── PowerBI/
    └── Rapido_Analysis.pbix


```

---

# 👨‍💻 Author

**Data Analytics & Business Intelligence Enthusiast**

This project is part of my Data Analytics portfolio, where I explore real-world business problems through data analysis, visualization, and actionable insights.

I am continuously developing my skills in SQL, Microsoft Excel, Power BI, Python, and business analytics to solve practical business problems using data.

If you find this project interesting, feel free to explore the repository and share your feedback!

⭐ If you like this project, consider giving the repository a star.
