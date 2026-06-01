# 🏏 Virat Kohli Career Statistics Analysis Dashboard

<p align="center">

<img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black">

<img src="https://img.shields.io/badge/Cricket-Analytics-blue">

<img src="https://img.shields.io/badge/Data%20Visualization-Sports%20Analysis-green">

<img src="https://img.shields.io/badge/Project-Interactive%20Dashboard-orange">

</p>

---

# 📌 Project Overview

The **Virat Kohli Career Statistics Analysis Dashboard** is an interactive Power BI project designed to analyze the batting performance of one of cricket's greatest players, **Virat Kohli**.

The dashboard provides a comprehensive view of his career across different formats, highlighting key batting metrics, yearly performance trends, scoring consistency, and milestone achievements. It enables cricket enthusiasts, analysts, and sports professionals to explore Kohli's remarkable career through data-driven insights.

---
# 📂 Dataset Used

📊 **Dataset Link**

<a href="https://github.com/kartikgawali-00/Virat-Kohli-Career-Statistics-Analysis-Dashboard/blob/main/Virat%20Kohli%20Statistics.xlsx">Dataset.csv</a>


# 🎯 Project Objective

The objective of this project is to analyze Virat Kohli's international cricket career and provide insights into:

✅ Total Runs Scored

✅ Batting Average

✅ Strike Rate Analysis

✅ Format-wise Performance

✅ Yearly Run Trends

✅ Century & Half-Century Analysis

✅ Boundary Distribution

✅ Career Consistency

The dashboard helps users understand batting performance patterns and evaluate career progression through visual analytics.

---

# 🛠️ Tools & Technologies Used

| Technology | Purpose |
|------------|----------|
| 📊 Power BI | Dashboard Development |
| 📑 Excel | Data Preparation |
| ⚡ DAX | KPI & Measure Creation |
| 🔄 Power Query | Data Transformation |
| 📈 Data Visualization | Sports Analytics |

---

# 📂 Dataset Information

The dataset contains Virat Kohli's international batting statistics, including:

* Match Date
* Year
* Format (ODI, T20I, Test)
* Runs Scored
* Innings Played
* Batting Average
* Strike Rate
* Number of 4s
* Number of 6s
* Centuries (100s)
* Half-Centuries (50s)

---

# 📊 Dashboard Overview

## 📈 Key KPIs

| KPI | Value |
|------|--------|
| 🏏 Total Runs | 25,277 |
| 📊 Batting Average | 52.80 |
| ⚡ Strike Rate | 92.90 |
| 🎯 Total Innings | 553 |
| 📅 Career Span | 2008 - 2023 |
| 🏆 Formats Covered | ODI, T20I, Test |

---

# 📊 Dashboard Components

## 1️⃣ Career Overview

### Business Questions

* How many runs has Virat Kohli scored across his career?
* What is his overall batting average?
* How consistent has he been over the years?
* How does his performance vary across formats?

### Key Insights

✅ Virat Kohli scored over **25,000 international runs**.

✅ Maintained an outstanding batting average of **52.80**.

✅ Played more than **550 innings** across formats.

✅ Demonstrated exceptional consistency throughout his career.

---

## 2️⃣ Format Analysis

### Formats Covered

* ODI
* T20I
* Test

### Key Insights

✅ ODI cricket contributes the largest share of runs.

✅ Strong performance maintained across all formats.

✅ Consistent run-scoring ability regardless of playing conditions.

---

## 3️⃣ Runs by Year Analysis

### Visualizations Used

* Year-wise Run Distribution
* Performance Trend Analysis

### Business Questions

* Which years were the most productive?
* How has performance evolved over time?
* Which period represents Kohli's peak career phase?

### Key Insights

✅ Significant growth observed after 2010.

✅ Peak run-scoring years occurred between **2016–2019**.

✅ Maintained elite performance levels over an extended period.

✅ Consistency remained strong across multiple seasons.

---

## 4️⃣ Boundary Analysis

### Boundary Distribution

| Boundary Type | Contribution |
|--------------|-------------|
| 4️⃣ Fours | Majority Share |
| 6️⃣ Sixes | Smaller Share |

### Key Insights

✅ Most runs through boundaries came from fours.

✅ Demonstrates Kohli's classical stroke-playing ability.

✅ Relies more on timing and placement than power hitting.

---

## 5️⃣ Century & Half-Century Analysis

### Milestone Tracking

* 100s (Centuries)
* 50s (Half-Centuries)

### Key Insights

✅ Large number of half-centuries reflects consistency.

✅ Frequent conversion of fifties into centuries.

✅ Peak milestone achievements occurred during prime career years.

---

## 6️⃣ Performance Consistency Analysis

### Business Questions

* How regularly does Kohli score big runs?
* Which years produced the highest milestone counts?
* How consistent has he been throughout his career?

### Key Insights

✅ Maintained remarkable consistency across multiple formats.

✅ Regularly produced match-winning performances.

✅ Sustained elite batting standards for over a decade.

---
# 📷 Dashboard Preview

<img src="https://github.com/kartikgawali-00/Virat-Kohli-Career-Statistics-Analysis-Dashboard/blob/main/Dashboard%20Image/Screenshot%202026-06-01%20182352.png?raw=true">

# 📈 DAX Measures

### Total Runs

```DAX
Total Runs =
SUM(ViratKohli[Runs])
```

### Total Innings

```DAX
Total Innings =
COUNT(ViratKohli[Innings])
```

### Batting Average

```DAX
Batting Average =
AVERAGE(ViratKohli[Average])
```

### Strike Rate

```DAX
Strike Rate =
AVERAGE(ViratKohli[StrikeRate])
```

### Total Centuries

```DAX
Total Centuries =
SUM(ViratKohli[100s])
```

### Total Half Centuries

```DAX
Total Half Centuries =
SUM(ViratKohli[50s])
```

---

# 💡 Project Insights

## 🏏 Batting Performance

* Virat Kohli accumulated over **25,000 international runs**.
* Maintained an exceptional average above **50**.
* Demonstrated consistency across all formats.

## 📈 Career Growth

* Run-scoring increased significantly after 2010.
* Peak performance years occurred between 2016 and 2019.
* Continued delivering strong performances throughout his career.

## 🎯 Consistency Insights

* High number of fifties and centuries.
* Excellent conversion rate of starts into big scores.
* One of the most reliable batsmen in modern cricket.

## ⚡ Scoring Style

* Majority of boundaries came through fours.
* Balanced approach between aggression and consistency.
* Strong strike rate while maintaining a high average.

---

# 🚀 Key Takeaways

### 🏆 Elite Consistency

Virat Kohli has maintained world-class batting standards across formats for more than a decade.

### 📈 Peak Performance Years

The period between **2016 and 2019** represents the most dominant phase of his career.

### 🎯 Run Machine

A combination of high average, strike rate, and innings count highlights exceptional consistency.

### 💪 Adaptability

Success across ODI, T20I, and Test cricket showcases remarkable versatility.

---



# 🏆 Skills Demonstrated

### 📊 Power BI

* Interactive Dashboard Design
* KPI Development
* DAX Measures
* Data Modeling
* Sports Analytics Reporting
* Data Visualization

### 📑 Excel

* Data Cleaning
* Data Validation
* Data Preparation

### 📈 Analytics

* Sports Performance Analysis
* Trend Analysis
* Statistical Reporting
* KPI Tracking
* Career Performance Evaluation

---

# 📌 Final Conclusion

The Virat Kohli Career Statistics Analysis Dashboard provides a comprehensive overview of one of cricket's most successful careers. Through interactive visualizations and key performance metrics, the dashboard highlights his run-scoring consistency, milestone achievements, batting efficiency, and career progression across international formats.

The analysis demonstrates Virat Kohli's sustained excellence, adaptability across formats, and ability to perform consistently at the highest level, making him one of the greatest batsmen in cricket history.

---

# 👨‍💻 Author

## Kartik Gawali

📊 Data Analyst | Power BI | Excel | SQL

⭐ If you found this project useful, don't forget to star the repository.
