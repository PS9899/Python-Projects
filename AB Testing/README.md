# A/B Testing of Website Themes using Python
This project demonstrates how to perform A/B testing using Python to compare the conversion performance of different website themes — specifically, Light Theme vs Dark Theme.

## 📊 Objective
The goal is to determine whether there is a statistically significant difference in **conversion rates** between users exposed to the **light** theme versus the **dark** theme using a **two-proportion z-test**.

## 📁 Dataset
The data consists of:
- User interactions with two different website themes.
- Key columns include `Theme`, `Click Through Rate (CTR)`, and `Conversion Rate`.

## 🔍 Analysis Steps
1. **Data Preprocessing**
   - Load data using `pandas`
   - Clean and explore the dataset

2. **Data Segmentation**
   - Split data into Light Theme and Dark Theme groups

3. **Conversion Rate Calculation**
   - Calculate total conversions and total samples for each group

4. **Statistical Testing**
   - Perform a **two-proportion z-test** using `statsmodels`

5. **Interpretation**
   - Use p-value and z-statistic to assess whether the theme has a significant effect on conversion
