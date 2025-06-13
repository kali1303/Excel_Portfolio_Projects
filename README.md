
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

Total Revenue: $96,623

Average Rating: 3.89 ★

Happy Callers: 307

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/Call_kpis.png?raw=true)

### 📈 Step 4: Trend & Category Analysis
#### 📅 Daily Trends
Most Active Day: Saturday

Least Active Day: Thursday 

Visualized using column chart with slicer for day selection.

#### 📆 Monthly Trends
Tracked overall revenue and duration month-by-month.

Helps identify performance spikes and drops.

Used combo line+column charts.

#### Most active months: March and April

#### Least active month: December, Novermber, Augest

These weekly and monthly trends of calls helps the organization to find out the reason for call drops in particular days and months to take necessary actions.

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/Calls_trends.png?raw=true)

### 👥 Step 5: Representative Performance
### 🔝 Top Representatives (By Revenue):
R03 – $20,872

R02 – $20,581

R05 – $20,104

R01 – $18,415

R04 – $16,651

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/Call_reps_revenue.png?raw=true)

### ⭐ Step 6: Customer Satisfaction Analysis
Rating Distribution: 4★ ratings dominate, followed by 5★ and 3★.



Duration Buckets: 1–2 hrs was the most common call length.


![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/Call_rating.png?raw=true)


### 🔍 Insights from Regional Call Performance Data
#### 📍 City-Wise Performance
#### Cincinnati

Highest revenue from customer: C0004 with $7,689 total.

Lowest performer from customer: C0003 with $4,804 total.

#### Cleveland

Highest : C0013 with $7,230.

Lowest : C0008 with $5,009 especially 

#### Columbus

Highest : C0005 with $7,747.

Lowest: C0014 with $5,404.

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/Call_custormers.png?raw=true)



### 🌟 Special Features
📸 Dynamic Representative Images: Unique to this dashboard, selecting a rep in the slicer reveals their image, making performance data feel more human and relatable.

🔄 Fully Interactive Slicers for day, month, rep, and city

⚡ Clean UI powered by Excel’s Pivot Table and slicer functionalities

📊 Effective visualizations using icons, bars, and conditional formatting

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/rep1.png?raw=true)

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/rep2.png?raw=true)

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/rep3.png?raw=true)

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/rep4.png?raw=true)

![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/rep5.png?raw=true)



## Call Centre Final Report
![Pizza KPI Dashboard](https://github.com/kali1303/Excel_Portfolio_Projects/blob/main/Call_cetre_report.png?raw=true)


## 📌 Conclusion
This Excel-based Call Center Performance Dashboard provides actionable insights into representative efficiency, call volume, and customer satisfaction. By visualizing KPIs such as total calls, average call duration, revenue generated, and rating trends, it helps identify both top and underperforming reps. The interactive filters and representative-wise visuals — including dynamic profile images — allow managers to personalize performance reviews. These insights enable targeted training, performance coaching, and workload balancing. Ultimately, this solution supports continuous improvement in customer experience and drives higher revenue. It empowers decision-makers to make data-backed strategies for growth.

