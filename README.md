# 🎬 Netflix Content Analysis with SQL

 A complete SQL project involving data cleaning, validation, statistical analysis, and exploratory data analysis (EDA) on the Netflix Titles dataset.


## 📌 Project Overview

This project demonstrates an end-to-end SQL data analysis workflow using the Netflix Titles dataset. The objective was to clean and prepare the dataset for analysis, perform statistical exploration, and uncover actionable insights into Netflix's global content library.

The project covers every stage of the analytics process—from assessing data quality and handling missing values to identifying trends, patterns, and business insights using SQL.

---

## 🎯 Project Objectives

* Assess the overall quality of the dataset.
* Identify and handle missing values.
* Validate dataset integrity.
* Standardize inconsistent data.
* Perform statistical analysis.
* Conduct exploratory data analysis (EDA).
* Generate business insights from the cleaned dataset.

---

## 📂 Dataset Information

| Item               | Details        |
| ------------------ | -------------- |
| Dataset            | Netflix Titles |
| Total Records      | 8,807          |
| Primary Identifier | Show_ID        |
| Database           | SQL Server     |
| Language           | SQL            |

The dataset contains information on movies and TV shows available on Netflix, including content type, release year, directors, cast, country, ratings, genres, and descriptions.

---

## 🛠 Tools & Technologies

* Microsoft SQL Server
* SQL Server Management Studio (SSMS)
* T-SQL

---

## 💡 SQL Skills Demonstrated

* Data Exploration
* Data Cleaning
* NULL Handling
* UPDATE Statements
* Aggregate Functions
* GROUP BY
* ORDER BY
* COUNT()
* AVG()
* MIN()
* MAX()
* DISTINCT
* Data Validation
* Business Analysis

---

# Data Cleaning Process

The dataset underwent several cleaning and validation steps before analysis.

### ✔ Dataset Familiarization

Initial exploration included:

* Reviewing sample records
* Counting total records
* Inspecting table structure
* Reviewing column data types

📷 **NetFlix Titles Preview**

![Netflix Titles Preview](Netflix_Tiles%20Preview.png)

---

### ✔ Missing Values Assessment

Missing values were identified across key columns including:

* Director
* Cast
* Country
* Rating
* Date Added

---

### ✔ Handling Missing Values

Missing values in the following columns were replaced with **'Unknown'** to preserve dataset completeness:

* Director
* Cast
* Country
* Rating

This ensured that records remained available for analysis while clearly identifying incomplete information.

📷 **Netflix Titles Null Values Replaced With Unknown**

![Netflix Titles Null Values Replaced With Unknown](Netflix%20null%20update%20to%20unknown.png)

---

### ✔ Duplicate Detection

The `Show_ID` column was verified as a unique identifier.

Result:

* ✅ No duplicate records found.

---

### ✔ Text Standardization

Country values were cleaned using:

* LTRIM()
* RTRIM()

to remove leading and trailing spaces.

---

### ✔ Data Validation

Additional validation included:

* Reviewing date consistency
* Identifying invalid ratings
* Correcting duration values incorrectly stored in the Rating column

---

# 📊 Statistical Analysis

Summary statistics were generated to understand the distribution of release years.

| Metric               | Value |
| -------------------- | ----: |
| Earliest Release     |  1925 |
| Latest Release       |  2021 |
| Average Release Year |  2014 |

### Key Observation

Netflix's catalog spans nearly a century but is heavily concentrated on modern content released after 2010.

---

# 📈 Exploratory Data Analysis (EDA)

The cleaned dataset was analyzed to uncover trends and business insights.

## 1. Content Type Distribution

* Movies: **6,131**
* TV Shows: **2,676**

Movies account for approximately **70%** of Netflix's catalog.

📷 **Content Type Distribution View**

![Netflix Titles Content Type Distribution](Netflix_Titles%20Movies%20vs%20TV%20show.png)

---

## 2. Content Added Over Time

Netflix experienced rapid catalog expansion between **2016 and 2020**, with **2019 recording the highest number of new additions.**

📷 **Content Add Over Time View**

![Netflix Titles Content Add Over Time](Netflix_Titles%20TV%20shows%20&%20Movies%20Year%20release%20Prt%201.png)
![Netflix Titles Content Add Over Time](Netflix_Titles%20TV%20Shows%20&%20Movies%20Year%20release%20Prt%202.png)

---

## 3. Top Content-Producing Countries

Top contributors include:

* United States
* India
* United Kingdom
* Japan
* South Korea

📷 **Top Content-Producing Countries View**

![Netflix Titles Top Content-Producing Countries](Netflix_titles%20Top%2010%20content%20producing%20Countries.png)

---

## 4. Rating Distribution

The most common audience ratings were:

* TV-MA
* TV-14
* TV-PG
* R
* PG-13

This indicates a strong focus on mature and teenage audiences.

📷 **Rating Distribution View**

![Netflix Titles Rating Distribution](Netflix_Titles%20Rating%20distribution.png)

---

## 5. Content Release Trends

Analysis showed:

* Low production before 2000
* Rapid growth after 2010
* Peak releases during 2018–2019

📷 **Content Release Trends View**

![Netflix Titles Content Release Trend](Netflix_Titles%20Content%20Release%20trend%20prt%201.png)
![Netflix Titles Content Release Trend](Netflix_Titles%20Content%20Release%20trend%20prt%202.png)

---

## 6. Most Common Genres

The most represented categories include:

* Dramas, International Movies
* Documentaries
* Stand-Up Comedy
* International Dramas
* Independent Movies

📷 **Most Common Genres View**

![Netflix Titles Most Common Genres](Netflix_titles%20Most%20common%20Genre.png)

---

## 7. Top Directors

Several directors contributed multiple productions to Netflix's catalog, with Rajiv Chilaka leading the list.

📷 **Top Directors Top Director View**

![Netflix Titles Top Directors](Netflix_titles%20Top%20Directors.png)

---

# 🔍 Key Business Insights

* Movies represent approximately 70% of Netflix's content library.
* Netflix expanded its catalog significantly between 2016 and 2020.
* The United States is the largest contributor of content.
* Mature audience content (TV-MA and TV-14) dominates the platform.
* Most titles were released after 2010, reflecting Netflix's focus on contemporary content.
* International dramas and documentaries are among the platform's strongest content categories.
* TV show production increased considerably after 2015, demonstrating growing investment in serialized content.

---


---

# 🚀 Key Takeaways

This project demonstrates practical SQL skills used in real-world analytics projects, including data cleaning, quality validation, statistical analysis, and exploratory data analysis to transform raw data into actionable business insights.

---

## 👤 Author

**Victor Chimbuo**

Aspiring Data Analyst | SQL | Power BI | Excel

If you found this project interesting, feel free to ⭐ the repository or connect with me on LinkedIn.
