# 📊 YesMobiles Funnel Analysis

## 🚀 Overview
YesMobiles has recently launched a **new mobile handset** and is closely monitoring its **sales funnel** to optimize conversions and identify any issues in the user journey. The company tracks user interactions on a dedicated **product webpage** to analyze **drop-off rates** and engagement patterns.

## 🎯 Objectives
- **Dropout Rate Analysis**: Identify where users are leaving the buying journey.
- **User Journey Analysis**: Understand how much time users spend at each stage.
- **Conversion Optimization**: Improve the overall conversion rate by addressing key bottlenecks.

## 📌 Data Description
The dataset contains user interactions from **Mumbai** and **Bengaluru**, categorized by **gender**, and tracks their progression through the following shopping stages:

- **User Interaction Data**: Logs each interaction with timestamps.
- **User Activity Data**: Tracks movement across the funnel (Browsing → Wishlist → Cart → Purchase).
- **User Category Data**: Segments users based on gender (Male/Female).

## 📊 Funnel Stages & User Dropout Rates

| Stage            | Male Users | Dropout Rate (Male) | Avg. Time Spent (Male) | Female Users | Dropout Rate (Female) | Avg. Time Spent (Female) |
|-----------------|------------|----------------------|------------------------|--------------|------------------------|--------------------------|
| Browsing       | 20         | -                    | -                      | 10           | -                      | -                        |
| Added to Wishlist | 7         | 65%                 | 2.80 days              | 5            | 50%                    | 0.75 days                |
| Added to Cart  | 5         | 28.57%              | 1.25 days              | 4            | 20%                    | 1.00 day                 |
| Purchased      | 4         | 20%                 | -                      | 3            | 25%                    | -                        |

### 📈 Overall Funnel Performance

| Metric                | All Users | Male | Female |
|----------------------|----------|------|--------|
| Conversion Rate     | 23.33%   | 20%  | 30%    |
| Avg. Time Spent    | 4.70 days | 6.34 days | 2.55 days |

## 🔍 Key Insights
✅ **Females have a higher conversion rate (30%) compared to males (20%)**  
✅ **Males spend more time (6.34 days) in the funnel compared to females (2.55 days)**  
✅ **Wishlist drop-off is a major issue, with 60% of users not moving forward**  

## 🎯 Actionable Recommendations
- **Optimize Wishlist & Cart Stages**: Offer targeted discounts or reminders.
- **Retarget Users Based on Engagement**: Use personalized email/SMS campaigns.
- **Streamline Checkout Process**: Reduce unnecessary steps to minimize friction.
- **A/B Testing for UX Improvements**: Test different designs to enhance engagement and conversions.

## 🛠 Tools Used
- **Data Analysis & Visualization**: Tableau, Power BI, Python (Pandas, NumPy, Matplotlib)
- **Funnel Tracking**: Amplitude, Google Analytics
- **Optimization Techniques**: A/B Testing, Customer Segmentation

## 📢 Conclusion
By understanding the **user journey**, YesMobiles can improve **sales funnels**, **reduce drop-offs**, and **increase conversions**. These insights enable **strategic decision-making** for better engagement and revenue growth.
