# Sociolla-Skincare-Product-Repurchase-Analysis

**Python · Pandas · Scikit-learn · Power BI · Data Visualization**

### Overview

Analyzed **7,636 skincare product records from Sociolla** to understand product characteristics associated with higher customer repurchase rates and identify key factors influencing repurchase behavior.

**My Contribution:** Data Analytics & Data Visualization

---

## 🎯 Business Problem

For e-commerce platforms, understanding why customers repurchase a product can help brands identify products with stronger customer acceptance and improve product strategies.

This project investigates:

> **What product factors are associated with higher repurchase rates on Sociolla?**

---

## 📊 Dataset

**Source:** Sociolla All Brands Products Catalog — Kaggle

**7,636 product records** with attributes including:

* Product & brand
* Product category
* Average rating
* Recommendation rate
* Repurchase rate
* Total reviews
* Wishlist
* Effectiveness
* Packaging
* Scent
* Texture
* Value for money

---

## 🔍 Analysis Approach

### 01. Data Preparation

* Reviewed dataset structure and attributes
* Handled missing values
* Checked duplicate records
* Transformed relevant variables
* Selected analytical features

### 02. Exploratory Data Analysis

* Descriptive statistics
* Distribution analysis
* Outlier analysis
* Correlation analysis
* Rating and repurchase analysis
* Brand & category analysis

One notable finding was the highly skewed distribution of product reviews: the median was **33 reviews**, while the maximum reached **21,536 reviews**, indicating that a small number of products generated disproportionately high engagement.

### 03. Predictive Analysis

Applied **Random Forest Classification** to classify products into:

* Low Repurchase
* Medium Repurchase
* High Repurchase

**Model Performance**

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 76.66% |
| Precision | 76.06% |
| Recall    | 76.66% |
| F1-Score  | 76.11% |

### 04. Feature Importance

The model identified the following features as the most influential:

1. **Average Rating**
2. **Recommendation Rate**
3. **Average Effectiveness**
4. **Average Texture**

This suggests that product ratings and customer recommendations were important indicators associated with higher repurchase levels.

---

## 📈 Dashboard

Developed a dashboard to help explore:

* Product performance
* Repurchase rate
* Average rating
* Brand performance
* Product categories
* Customer engagement
* Rating vs. repurchase relationship

**Dashboard Highlights**

* 4,485 products
* 279 brands
* Average rating: 4.64
* Average repurchase rate: 0.74

---

## 💡 Key Insights

**01 — Product ratings matter**

Products with stronger ratings tend to show higher repurchase rates.

**02 — Customer recommendations are an important signal**

Recommendation rate was among the strongest features in the Random Forest analysis.

**03 — Product engagement is highly concentrated**

Most products receive relatively limited review activity, while a small number of products generate extremely high engagement.

**04 — Product experience matters**

Effectiveness and texture were also among the features with higher importance in predicting repurchase levels.

---

## 💼 Business Recommendations

Based on the analysis, e-commerce platforms and skincare brands could:

* Monitor products with declining ratings or recommendations.
* Identify high-repurchase products and analyze their product characteristics.
* Encourage customers to leave ratings and reviews.
* Use product feedback to identify opportunities for improving product experience.
* Monitor product categories and brands with stronger repurchase performance.

---

## 🛠️ Tools

**Python:** Pandas, Scikit-learn
**Analysis:** EDA, Correlation Analysis, Random Forest
**Visualization:** Power BI
**Environment:** Google Colab
