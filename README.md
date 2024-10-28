# COGNORISE-INFOTECH


# TASK - 1 |  Unemployment During COVID-19 in India Dashboard

## Overview

This dashboard presents a comprehensive analysis of unemployment trends across India during the COVID-19 pandemic. The analysis focuses on regional unemployment rates, labor participation, and key metrics, providing insights into how the pandemic impacted employment across different areas and timeframes.

## Data Source

- **Dataset**: The dashboard uses data from the "Unemployment in India" dataset, which includes estimated unemployment rates, labor participation, and employment details across various regions in India.
- **Time Period**: The data covers the years 2019 and 2020, allowing for pre- and post-pandemic comparisons.


# Snapshot of Unemployment During COVID-19 in India  Dashboard (EXCEL)
![Screenshot 2024-10-23 125823](https://github.com/user-attachments/assets/58820b99-8102-43a8-a039-2314fe97e28f)

### Key Metrics

1. **Total Estimated Unemployment**: 
   - **11.79 million** (approx).

2. **Total Estimated Employed**: 
   - **533.13 million** (approx).

3. **Total Estimated Labor Participation**: 
   - **42.630** (approx).

### Key Insights

1. **Unemployment Increased During COVID-19**:
   - Unemployment rate rose from **38% in 2019** to **62% in 2020**, reflecting the pandemic's impact on employment.

2. **Urban Areas Had Higher Unemployment**:
   - **Urban areas** faced a higher unemployment rate (**56%**) than **rural areas** (**44%**).

3. **Regional Differences in Unemployment**:
   - Regions like **Tripura** and **Haryana** had **higher unemployment rates**, while states like **Bihar** and **Uttar Pradesh** had lower unemployment.

4. **Low Labor Participation in High Unemployment States**:
   - States such as **Tripura** and **Haryana**, which had **high unemployment**, also showed **low to moderate labor participation rates**.

5. **Sharp Drop in Employment During 2020**:
   - Employment remained fairly steady until early 2020, after which it **dropped sharply**, coinciding with the peak of the pandemic.

6. **Unemployment Peaked During April-May 2020**:
   - The unemployment rate **peaked** between **April and May 2020**, showing the significant impact of the pandemic during that period.

7. **Urban Areas Hit Harder in Various States**:
   - In several states, **urban areas experienced noticeably higher unemployment rates** than rural areas, indicating a larger economic impact in cities.

# Filters

- **Region**: Select from various Indian states and territories.
- **Months (Date)**: Filter data by months for detailed temporal analysis.
- **Quarters (Date)**: Analyze data quarterly for a broader view of trends.
- **Area**: Filter between urban and rural areas to study area-specific trends.

# Recommendations:

1. **Help Hard-Hit States**:
   - Provide **special support** and job programs to states with the highest unemployment.

2. **Create More Jobs in Rural Areas**:
   - Invest in **rural development** and provide **training** to increase employment in villages.

3. **Train Workers for New Jobs**:
   - Offer **training programs** to help people get jobs in industries like technology and manufacturing.

4. **Support Small Businesses**:
   - Give **loans** and **financial aid** to small businesses so they can recover and hire more workers.


# Conclusion

This dashboard provides a powerful tool for understanding the economic impact of COVID-19 on unemployment in India. It offers a breakdown of key unemployment statistics by region, time, and area (urban vs rural). By analyzing this data, policymakers and researchers can better understand which regions and demographics were hit hardest and develop targeted recovery strategies.



# 

# TASK - 2 | Employee Salaries for Different Job Roles - Power BI Dashboard

#### Project Overview:
This Power BI dashboard presents an analysis of employee salaries across different job roles, experience levels, company sizes, and employment types. The data was transformed and cleaned to enhance insights, including adding full forms for country names, experience levels, and employment types.

# Snapshot of Employee Salaries for Different Job Roles Dashboard ( Power BI)
![Screenshot 2024-10-23 185935](https://github.com/user-attachments/assets/17bf5da4-331b-4573-a80f-083af2e8ead0)

#### Key Metrics:
- **Total Employees:** 607
- **Total Salary:** $197M
- **Highest Salary:** $30M
- **Average Salary:** $324K
- **Job Titles Analyzed:** 50
- **Company Locations:** 50

# Data Transformations:
- **Country Names:** Added full names for employee residence countries (e.g., 'US' to 'United States').
- **Experience Level:** Expanded abbreviations to full forms (e.g., 'EN' to 'Entry Level', 'MI' to 'Mid Level', 'SE' to 'Senior Level').
- **Employment Type:** Converted short forms to full terms (e.g., 'FT' to 'Full Time', 'PT' to 'Part Time').
- **Company Size:** Clarified company size categories ('L' to 'Large', 'M' to 'Medium', 'S' to 'Small') for easier understanding.

#### Insights:
- **Top Salaries by Job Role:** Data Scientists receive the highest total salary ($73M).
- **Experience Level Distribution:** Senior employees account for 56.94% of total salaries, with entry-level at 7.96%.
- **Salary Growth:** Average salary rose to $125K in 2022, showing steady growth.
- **Company Size Impact:** Large companies contribute to 60% of the total salary, with small companies contributing 15%.
- **Remote Work:** A significant majority (381 employees) work fully remotely.

#### Recommendations:
1. **Retain Senior-Level Talent:** Focus on retaining senior employees as they represent the majority of salary expenditure.
2. **Expand Remote Work Policies:** Increase remote work opportunities to attract top talent.
3. **Competitive Pay for Key Roles:** Ensure competitive salaries for roles like Data Scientist to maintain market competitiveness.

#### Tools & Technologies Used:
- **Power BI** for data visualization.
- **CSV Dataset** with employee salary data.
- **Data Transformation:** Country names, experience levels, employment types, and company sizes were expanded and clarified for better analysis.

### Conclusion:
This dashboard provides valuable insights into employee salary trends across various job roles and experience levels. By transforming and enhancing the data, organizations can make informed decisions to improve workforce planning and compensation strategies. Continued focus on retaining senior talent and adapting to market trends will be essential for future success.

#


#  Task - 3 | Customer Travel Data Analysis

## 1. Overview
This project focuses on analyzing customer travel data to gain insights into customer behavior, preferences, and patterns that can help a travel company optimize its services. Various aspects such as age distribution, income class, frequent flyer status, and service usage are explored. The analysis also covers churn prediction based on these factors to help the company retain its customers.

We employ Python for data manipulation and visualization, using libraries like Pandas, Matplotlib, Seaborn, and WordCloud. The goal is to derive actionable insights to improve customer satisfaction and retention.

---

## 2. Data Source
The dataset consists of anonymized customer data, including:
- **Age**: Customer’s age.
- **Frequent Flyer**: Indicates whether a customer is a frequent flyer.
- **Income Class**: Categorization of customers based on their annual income.
- **Services Opted**: Number of services the customer has availed.
- **Account Synced to Social Media**: Whether a customer's account is linked to social media platforms.
- **Booked Hotel**: Whether the customer has booked a hotel.
- **Feedback**: Customer feedback on the company’s services.
- **Target**: Binary indicator of whether the customer churned (1) or not (0).

---

## 3. Key Metrics
Several key metrics were derived from the analysis:
- **Age Distribution**: Understanding the age demographic of customers.
- **Frequent Flyers vs Non-Frequent Flyers**: A comparison of the number of frequent flyers against non-frequent flyers.
- **Income Class Distribution**: Breakdown of customers by their income classes.
- **Services Opted**: Spread of services opted for by customers across different income groups.
- **Churn Rate**: The rate of churn across different income classes.
- **Social Media Synced vs Hotel Booking**: Relationship between accounts synced to social media and hotel bookings.

---

## 4. Insights & Recommendations

### Insights:
- **Age Distribution**: The age demographic is skewed towards younger customers, with a significant concentration between 25-40 years.
  
- **Frequent Flyers**: The analysis showed a nearly equal split between frequent flyers and non-frequent flyers, suggesting a balance between loyal and occasional customers.

- **Income Class Distribution**: The largest proportion of customers fall into the middle-income class, while a smaller percentage belongs to the high-income class. This suggests that the company caters more to middle-income travelers.

- **Services Opted**: Higher-income customers tend to opt for more services, with a clear trend of service usage increasing with income class.

- **Churn Rate**: The churn rate is higher in lower-income classes, possibly due to budget constraints. Customers in the high-income category show a lower churn rate, suggesting higher brand loyalty.

- **Social Media Synced vs Hotel Booking**: A positive relationship was observed between social media account syncing and hotel bookings. Customers with synced social media accounts were more likely to book hotels.

### Recommendations:
- **Target Younger Audience**: With a significant portion of the customer base aged 25-40, personalized marketing campaigns targeting this age group could improve engagement and retention.
  
- **Incentivize Frequent Flyers**: Create loyalty programs to incentivize non-frequent flyers to fly more often and turn them into frequent customers.

- **Expand Premium Services**: Since high-income customers opt for more services, introducing premium service packages or memberships could increase revenue from this segment.

- **Reduce Churn in Lower-Income Groups**: Special offers, flexible payment plans, and budget-friendly packages could reduce the churn rate in the lower-income group.

- **Leverage Social Media for Bookings**: Encourage more customers to sync their accounts with social media by offering special discounts or benefits, as this has shown to positively impact hotel bookings.

---

## 5. Conclusion
The analysis provided valuable insights into customer demographics, behavior, and service usage patterns. By leveraging these insights, the travel company can improve customer retention and tailor its services to different customer segments, especially focusing on churn reduction strategies for lower-income groups and expanding offerings for high-income customers. Recommendations provided can help the company optimize marketing efforts, improve customer satisfaction, and ultimately drive revenue growth.

## 6. Project Link 

https://colab.research.google.com/drive/1IyC2HTDOZ92nOII-K-EqztMNInWaymm3?usp=sharing
---


Please give your valuable feedback and suggestions for further improvement.






