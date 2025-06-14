# ✈️ Customer Segmentation for Sun Country Airlines

This repository contains a customer segmentation project conducted using clustering analysis for **Sun Country Airlines**, developed as part of a team case assignment at the **Paul Merage School of Business, UC Irvine**. The goal was to uncover actionable marketing and retention strategies through data-driven segmentation.

## 📁 Project Contents

- `Project Code.ipynb` – Python notebook for data cleaning, K-Means clustering, and segment-wise visual analysis
- `SCA Project Report.pdf` – Comprehensive report detailing methodology, segment insights, and marketing recommendations

## 🎯 Objective

To segment Sun Country Airlines’ customers into distinct groups based on demographic, behavioral, and loyalty-related data and provide targeted marketing and service recommendations.

## 🔍 Methodology

### 1. Data Preparation
- Cleaned and encoded features for clustering (90+ columns)
- Checked for null values, dropped IDs, standardized input
- Created a preserved original dataset for validation

### 2. Clustering
- Performed **K-Means clustering** with Elbow Method to determine optimal `k = 5`
- Assigned cluster labels and merged with customer data

### 3. Visual Analysis by Segment
- Distribution by age group, gender, booking channel, amount spent, days pre-booked, travel class, and loyalty tier

## 📊 Segment Insights

| Segment | Description           | Highlights |
|---------|------------------------|------------|
| 0 | **Vacationers** | Prefer Outside Booking, plan 60+ days in advance, Coach class, non-loyalty |
| 1 | **Convenience Seekers** | Use SCA Website, book ~50 days in advance, mix of loyalty tiers |
| 2 | **Family Flyers** | Largest group, diverse booking channels, high female share, mix of class usage |
| 3 | **White Collar Travelers** | Budget-conscious, low average spend, book 36 days ahead |
| 4 | **Deluxe Comfort** | High spenders, most pre-booking days (68), high loyalty and First Class travelers |

## 💡 Strategic Recommendations

- **Vacationers**: Offer early-bird deals, bundled vacation packages
- **Convenience Seekers**: Promote flexible booking and off-peak discounts
- **Family Flyers**: Launch family-focused loyalty programs and holiday campaigns
- **White Collar**: Use flash sales, business class perks, and corporate discounts
- **Deluxe Comfort**: Focus on luxury promotions and personalized loyalty rewards

## 🛠️ Technologies & Tools

- Python (pandas, seaborn, matplotlib, scikit-learn)
- K-Means clustering
- Data visualizations (boxplots, heatmaps, stacked bars)

## 👥 Team Members

- **Viraj Vijaywargiya** *(myself)*
- Zhiwei Lu  
- Yuh-Shin Yen    
- Anna Haroutounian  
- Danqi Zheng

---

📌 *This project showcases how clustering and customer analytics can directly drive marketing and loyalty strategy for airlines.*
