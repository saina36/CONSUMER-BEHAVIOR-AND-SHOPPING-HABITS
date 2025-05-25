# CONSUMER-BEHAVIOR-AND-SHOPPING-HABITS
CONSUMER BEHAVIOR AND SHOPPING HABITS-MINI PROJECT
# 🛍️ Customer Purchase Behavior Analysis - Power BI Dashboard

## 📊 Overview

This project presents an interactive Power BI dashboard that analyzes customer purchase behavior using a retail dataset of 3,900 customers. The dashboard provides key insights into demographics, product preferences, shipping behavior, and customer feedback.

---

## 📁 Project Structure

---

## 🔍 Dataset Summary

- **Rows:** 3,900
- **Columns:** 18
- **Key Features:**
  - Customer demographics (age, gender, location)
  - Product details (item purchased, category, size, color)
  - Order behavior (purchase amount, shipping type, discount)
  - Customer feedback (review rating, subscription status)

---

## 📌 Key Insights & Visualizations

### A. Demographic Analysis

#### 📌 Gender Distribution (Pie Chart)
- **67.97%** of customers are **male**, and **32.03%** are **female**.
- Insight: Indicates a male-dominated customer base—can influence personalized marketing strategies.

#### 📌 Age Distribution (Bar Chart)
- Most customers fall between **ages 30 to 50**, with each group nearing **800 customers**.
- Insight: These are the most active shoppers; under-20 and over-60 age groups are underrepresented.

#### 🗺️ Map Visualization (Geographic Chart)
- Shows customer spread across the U.S., with pie charts representing **product categories**.
- Insight: Balanced preference for **accessories, clothing, footwear, and outerwear** in most regions.
- Regional variation in purchases indicates potential for location-based promotions.

---

### B. Purchase Behavior

#### 🛍️ Top Items Purchased (Bar Chart)
| Item         | Count |
|--------------|-------|
| Blouse       | 172   |
| Jewelry      | 171   |
| Pants        | 171   |
| Shirt        | 169   |
| Dress        | 165   |

- Insight: Blouses, jewelry, and pants are most frequently bought, whereas gloves and jeans are less popular.
- Suggests trends and seasonal preferences influence purchases.

---

### C. Shipping Preferences

#### 📦 Shipping Type vs Purchase Amount (Bar Chart)
| Shipping Type    | Total Purchase Amount | Season |
|------------------|-----------------------|--------|
| Free Shipping    | 10,825                | Summer |
| Express          | 10,609                | Fall   |
| Store Pickup     | 10,580                | Spring |
| 2-Day Shipping   | 10,352                | Spring |

- Insight: Purchase amounts are **evenly spread** across shipping types and seasons.
- Suggests customer demand is stable year-round for all shipping methods.

#### 📊 Shipping Type Distribution (Pie Chart)
- **2-Day Shipping** is slightly preferred (**17.39%** of customers).
- Insight: Shipping choice is likely driven by availability, urgency, or pricing—no single type dominates.

#### 📈 Count by Shipping Type
| Shipping Type    | Customers |
|------------------|-----------|
| Free Shipping    | 677       |
| Standard         | 652       |
| Store Pickup     | 649       |
| Next Day Air     | 646       |
| Express          | 644       |
| 2-Day Shipping   | 625       |

---

### D. Customer Feedback

#### ⭐ Review Ratings vs Purchase Amount (Line Chart)
- Fluctuating review ratings across different purchase amounts.
- Insight: No strong correlation—indicates **customer satisfaction is not strictly tied to how much they spend**.

---

## 🧹 Data Cleaning & Preprocessing

- Imputed missing **numeric values** (`Age`, `Purchase Amount`) using **mean**, as there were **no significant outliers**.
- Imputed **categorical variables** (`Gender`, `Location`) using **mode**.
- Removed rows with missing values in less important columns.
- Validated data completeness and outlier presence using **boxplots**.

---

## 📂 Tools Used

- **Power BI** for visualization
- **Python (Pandas, Matplotlib)** for preprocessing
- **GitHub** for version control and documentation


---

## ✅ Conclusion

This project provides a 360-degree view of customer behavior, preferences, and feedback in the retail domain. The visual insights can support business decisions in areas such as:

- Targeted marketing by age/gender
- Region-specific inventory planning
- Optimized shipping options
- Understanding customer satisfaction drivers

---



