# Customer Profiling of Aerofit Trade Mill

## 🧩 Problem Statement

A fitness equipment manufacturer, wants to analyze customer characteristics to understand **which customer segments prefer which treadmill model**. With three treadmill products (KP281, KP481, KP781), the goal is to identify the demographic and usage-related factors influencing product choice. This will help Aerofit optimize marketing strategies and improve customer targeting.

**Product Portfolio:**

- The KP281 is an entry-level treadmill that sells for $1,500.

- The KP481 is for mid-level runners that sell for $1,750.

- The KP781 treadmill is having advanced features that sell for $2,500

---

## 🎯 Objective
- To analyze demographic and behavioral attributes of treadmill customers.
- To identify the characteristics of customers choosing KP281, KP481, and KP781.
- To extract actionable insights to support Aerofit’s market segmentation strategy.
- To build clear customer profiles for each treadmill model.
---
## Column Profiling:

|Feature |	Description|
|--------|-------------|
|Product |	Product Purchased: KP281, KP481, or KP781|
|Age |	Age of buyer in years|
|Gender |	Gender of buyer (Male/Female)|
|Education |	Education of buyer in years|
|MaritalStatus |	MaritalStatus of buyer (Single or partnered)|
|Usage |	The average number of times the buyer plans to use the treadmill each week|
|Income |	Annual income of the buyer (in $)|
|Fitness |	Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape|
|Miles |	The average number of miles the buyer expects to walk/run each week|

---
## 🛠️ Tasks Performed
- Imported and inspected the dataset for structure, schema, and content.
- Checked for missing values, duplicate entries, and data consistency.
- Performed exploratory data analysis (EDA) on numerical and categorical features.
- Conducted distribution analysis to identify skewness and outliers.
- Visualized customer attributes using histograms, bar charts, and boxplots.
- Examined product purchase patterns across different demographic variables.
- Segmented customers based on Age, Income, Usage frequency, and Miles run.
- Developed detailed customer profiles for each treadmill model.
- Interpreted analysis results into actionable insights and business recommendations.

---
## 🧠 Concepts Used

This project applies foundational **Exploratory Data Analysis (EDA)** techniques, including:

### 🔹 Data Preprocessing
- Null value check
- Duplicate value detection
- Data type validation

### 🔹 Univariate & Bivariate Analysis
- Distribution analysis (histograms, boxplots)
- Skewness analysis
- Outlier detection
- Categorical variable frequency plots

### 🔹 Customer Profiling
- Segmentation based on age, income, fitness usage, and miles run
- Comparative analysis across product types
  
---
## 🔍 Findings & Observations
Based on the provided dataset:
1. **Data Quality**
    - No missing values were found.
    - No duplicate entries exist.
    - Key variables (Age, Usage, Income, Miles) show right-skewed distributions.

2. **Product Distribution**
    - **KP281** is the **most purchased** treadmill.
    - **KP781** has the **lowest sales**, indicating it appeals to a niche segment.
    - Customer purchase patterns suggest varying fitness motivations across models.

3. **Demographic Insights**
    - Most users belong to a **younger to mid-age** bracket.
    - Income distribution indicates that Aerofit attracts a **moderate-income customer base**.
    - Usage patterns show that customers generally plan to use the treadmill **less than 5 days per week**.

4. **Outliers**
    - Notable presence of outliers in **Income** and **Miles** variables.
    - These may represent high-income or high-intensity fitness users.
---
## 💡 Key Insights
- **KP281 buyers** are typically entry-level or casual users with lower usage frequency.
- **KP481 attracts mid-level runners**, indicating moderate commitment and slightly higher income.
- **KP781 buyers** appear to be **serious runners** with higher income and higher weekly mileage.
- Younger customers dominate the treadmill market, suggesting Aerofit should target youth fitness campaigns.

---
## 🧑‍🤝‍🧑 Detailed Customer Profiles (By Product)
### 🔵 KP281 — Entry-Level Users

#### Profile Summary:
- Price-conscious buyers
- Casual exercisers or beginners
- Prefer affordable, low-maintenance fitness equipment

#### Customer Characteristics:
- **Age**: Younger demographic (20s–30s)
- **Income**: Low to moderate
- **Usage**: 2–4 days/week
- **Miles**: Lower mileage — mainly light workouts

#### Interpretation:
KP281 attracts customers who want basic fitness equipment without advanced features.

### 🟢 KP481 — Mid-Tier Users

#### Profile Summary:
- Moderate fitness commitment
- Seeking performance + affordability balance
- Ideal for consistent joggers/runners
  
#### Customer Characteristics:
- **Age**: Mid 30s–40s
- **Income**: Medium range
- **Usage**: 3–5 days/week
- **Miles**: Moderate running distance

#### Interpretation:
This group values durability and moderate performance but is still price-sensitive.

### 🔴 KP781 — High-End Fitness Enthusiasts

#### Profile Summary:
- Serious runners or high-performance users
- Less price-sensitive
- Prefer advanced features and sturdy equipment

#### Customer Characteristics:
- **Age**: 30–45
- **Income**: High-income bracket
- **Usage**: 5–6 days/week
- **Miles**: Highest mileage in the dataset

#### Interpretation:
KP781 buyers represent a premium segment — committed, fitness-focused individuals.

---
## 📌 Recommendations
- **Segmented Marketing Campaigns**
    - Advertise KP281 to beginner-level users and budget-conscious buyers.
    - Promote KP481 to intermediate runners seeking consistent home workouts.
    - Position KP781 as a premium, high-performance product for fitness enthusiasts.

- **Income-Based Targeting**
    - Digital ads can be optimized for different income segments based on product price points.

- **Feature Highlighting**
    - Highlight durability and performance metrics for KP781.
    - Emphasize ease of use and affordability for KP281.

- **Improve Data Collection**
    - Include more lifestyle and behavioral attributes for deeper segmentation.

---
## 🏁 Conclusion

This analysis provides a clear understanding of Aerofit’s treadmill customer base. By examining demographic and behavioral characteristics, the study highlights distinct customer groups for each product. These insights can support **better product positioning**, **refined marketing strategies**, and **data-driven decision-making** for future product development and targeting.
