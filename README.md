# Excel_Portfolio_Projects
# Call Centre Performance Report – Excel Dashboard


## Problem Statement

Call centres often face challenges in monitoring agent productivity, understanding customer satisfaction, and optimizing performance. Data is typically scattered, making it hard to derive actionable insights. This Excel dashboard addresses these issues by consolidating call data into a clean, interactive report, tracking key metrics such as total calls handled, revenue generated, average call duration, and customer satisfaction. The solution empowers operations managers to make data-driven decisions, identify top performers, and enhance service delivery.


### Steps followed 
### 🛠️ Step 1: Data Preparation & Power Query Processing
🔍 Power Query Transformations:
Enabled Column Quality, Distribution, and Profile for complete dataset analysis.

Removed nulls, blanks, and standardized all column names.

#### Extracted key derived fields:

Day of Week from Date of Call

Duration Bucket for call segmentation

Rating Rounded for consistent aggregation

Joined customer demographic data using Customer ID as key.

### 🔄 Step 2: Data Modeling and Calculations
Used calculated columns and formulas in Excel to enrich data:

Total Calls	= COUNTA(Call Number)

Total Call Duration	= SUM(Duration)

Total Revenue = SUM(Purchase Amount)

Average Call Duration = Total Duration / Total Calls

Average Rating = AVERAGE(Satisfaction Rating)

### Step 3: KPIs 
#### 🎯 KPIs Displayed:

Total Calls Handled: 1,000

Total Call Duration: 89,850 minutes

Total Revenue: ₹96,623

Average Rating: 3.89 ★

5★ Calls: 307

![Pizza KPI Dashboard](https://github.com/kali1303/PowerBI_projects/blob/main/Pizza/KPIs.png?raw=true)

### 📈 Step 4: Trend & Category Analysis
#### 📅 Daily Trends
Most Active Day: Monday

Least Active Day: Saturday

Visualized using column chart with slicer for day selection.

#### 📆 Monthly Trends
Tracked overall revenue and duration month-by-month.

Helps identify performance spikes and drops.

Used combo line+column charts.

![Pizza KPI Dashboard](https://github.com/kali1303/PowerBI_projects/blob/main/Pizza/Daily_trends.png?raw=true)

### 👥 Step 5: Representative Performance
🔝 Top Representatives (By Revenue):
R02 – ₹20,581

R01 – ₹18,415

R04 – ₹13,935

R03 – ₹12,895

R05 – ₹12,797

### ⭐ Step 6: Customer Satisfaction Analysis
Rating Distribution: 5★ ratings dominate, followed by 4★ and 3★.

Bucketed Ratings: Rounded for aggregation (3★, 4★, 5★).

Duration Buckets: 1–2 hrs was the most common call length.




### 👨‍👩‍👧‍👦 Step 7: Customer Demographic Insights
Category	Observation
Age Group	Majority of customers are aged 25–40
Gender Split	Slightly more males in data
Top Cities	Columbus, Cleveland, Cincinnati

These insights can help tailor communication styles or support hours.


### 🌟 Special Features
📸 Dynamic Representative Images: Unique to this dashboard, selecting a rep in the slicer reveals their image, making performance data feel more human and relatable.

🔄 Fully Interactive Slicers for day, month, rep, and city

⚡ Clean UI powered by Excel’s Pivot Table and slicer functionalities

📊 Effective visualizations using icons, bars, and conditional formatting


## The Pizza sales report images:
### Page 1
![Pizza KPI Dashboard](https://github.com/kali1303/PowerBI_projects/blob/main/Pizza/Pizza_sales_1.png?raw=true)


## 📌 Conclusion
This Excel-based Call Center Performance Dashboard provides actionable insights into representative efficiency, call volume, and customer satisfaction. By visualizing KPIs such as total calls, average call duration, revenue generated, and rating trends, it helps identify both top and underperforming reps. The interactive filters and representative-wise visuals — including dynamic profile images — allow managers to personalize performance reviews. These insights enable targeted training, performance coaching, and workload balancing. Ultimately, this solution supports continuous improvement in customer experience and drives higher revenue. It empowers decision-makers to make data-backed strategies for growth.

