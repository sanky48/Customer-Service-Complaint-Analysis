# Customer-Service-Complaint-Analysis
This project analyzes customer service complaint data to identify patterns, trends, and factors affecting response time. The goal is to improve service efficiency by understanding complaint distribution and resolution performance.

🎯 Objectives

- Understand and clean the dataset
- Analyze complaint types and their frequency
- Perform city-wise complaint analysis
- Calculate and evaluate response time
- Identify significant variables using statistical analysis
- Visualize insights for better interpretation

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

📁 Dataset

The dataset contains information such as:
Complaint Type
City
Created Date
Closed Date
Other service-related attributes

⚙️ Steps Performed
1. Data Understanding

- Loaded dataset using Pandas
- Checked structure, shape, and column names
- Identified missing values

2. Data Cleaning

- Removed records with missing Closed Date
- Converted date columns to datetime format
- Handled missing values in City column

3. Feature Engineering

- Calculated Resolution Time
- Converted time into seconds for analysis

4. Exploratory Data Analysis (EDA)

- Frequency distribution of complaint types
- City-wise complaint analysis
- Visualization using bar charts and heatmaps

5. Time-Based Analysis

- Average response time per complaint type
- Identification of slow and fast complaint categories

6. Statistical Analysis

- Performed Kruskal-Wallis Test
- Used p-value to determine significance

📈 Key Insights

- Certain complaint types occur more frequently than others
- Complaint distribution varies across cities
- Response time differs significantly across complaint types
- Statistical testing confirmed that complaint type has a significant impact on resolution time

🧪 Statistical Conclusion

- p-value ≈ 0.0
- Reject Null Hypothesis
- Complaint Type significantly affects response time

📊 Visualizations

- Bar charts for complaint frequency
- Stacked bar charts for city-wise comparison
- Heatmaps for complaint distribution
- Scatter and hexbin plots for location-based analysis

👨‍💻 Author

Sanket Ainapure
