# Communicate Data Findings
### Ford GoBike Data Analysis

## Overview 🚴‍♂️
This project analyzes the Ford GoBike bike-sharing system data to uncover trends in user behavior, trip duration, peak usage times, and more. The dataset includes details on ride duration, user type, gender, birth year, and trip timestamps.

## How to Run 🏃
1. Clone this repository:
   ```sh
   git clone https://github.com/AmmarYasserAI-2/FordGoBike-Analysis.git
   ```
2. Install dependencies:
   ```sh
   pip install numpy pandas matplotlib seaborn
   ```
3. Run the Jupyter Notebook or Python scripts.


## Key Insights 📊
- **Trip Duration:** Most trips last under 16 minutes, but outliers extend beyond 83 minutes.
- **User Types:** The majority of riders are **subscribers** (regular users), while **customers** (occasional riders) take longer trips on average.
- **Gender Distribution:** Most riders are **male**, followed by **female**. A smaller group chose **'Other'**, showing higher trip duration variation.
- **Age Distribution:** Most users were born between **1980 and 2000**, but some data entries suggest birth years before 1900, likely errors.
- **Peak Usage Patterns:**
  - **Weekdays:** Peaks at **8 AM** and **5-6 PM**, indicating commuter behavior.
  - **Weekends:** Higher activity from **12 PM to 4 PM**, suggesting leisure trips.
- **Trip Duration by User Type:**
  - **Customers** tend to have **longer trips**.
  - **Subscribers** have **consistent trip durations**.
- **Daily Usage Patterns:**
  - **Subscribers** ride more on **weekdays** (especially Tuesday-Thursday).
  - **Customers** have more balanced usage, with slightly higher rides on **Saturdays**.

## Dataset 📂
The dataset used is the **201902-fordgobike-tripdata.csv**, which contains:
- **Trip details** (start/end time, duration, start/end station)
- **User information** (user type, gender, birth year)
- **Bike-sharing participation**

## Technologies Used 🛠️
- **Python** 🐍
- **Pandas** 📊
- **Matplotlib & Seaborn** 🎨
- **NumPy** 🔢

## Conclusion 🎯
This analysis reveals distinct biking patterns in the Ford GoBike system, differentiating between subscriber and customer behaviors. Peak times align with work commutes, while weekends show increased leisure activity.

## Future Work 🚀
- **Enhance data cleaning** to handle unrealistic birth years.
- **Include weather data** to assess its impact on bike usage.
- **Develop a predictive model** for trip duration based on user behavior.


## Acknowledgments 🙌
This project was conducted as part of the **DECI and Udacity Data & AI Track**. 

![image](https://github.com/user-attachments/assets/b2fb6d93-aee2-4127-9843-a6e9d9bc7b4f)

---
🔗 **Follow my work:** [GitHub](https://github.com/AmmarYasserAI-2) | [LinkedIn](https://linkedin.com/in/ammar-batea/)

