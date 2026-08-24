# Airbnb Listings Analysis — Pandas & SQL

## 📌 Project Overview

This project analyzes an Airbnb listings dataset using **Python (Pandas)** and **SQL** to explore listings, prices, room types, reviews, hosts, and cities.

The project uses both Pandas and SQL to solve the same analytical questions and practice real-world data analysis techniques.

---

## 📂 Project Structure

```text
Airbnb-Analysis/
│
├── data/
│   └── AB_US_2020.csv
│
├── pandas/
│   └── Airbnb_Analysis.ipynb
│
├── sql/
│   └── Questions and Answers
│
└── README.md
```

---

## 📊 Analysis Questions

The project answers the following questions using **Pandas and SQL**:

### 1. Which 10 cities have the most Airbnb listings?

Find the 10 cities with the highest number of Airbnb listings.

**Concepts used:**

* `groupby()`
* `count()`
* `value_counts()`
* `GROUP BY`
* `COUNT()`
* Sorting

---

### 2. Which 10 cities have the highest average price?

Calculate the average Airbnb price for each city and identify the 10 cities with the highest average prices.

**Concepts used:**

* Pandas `groupby()`
* `mean()`
* SQL `AVG()`
* `GROUP BY`
* `ORDER BY`

---

### 3. What is the most popular room type in each city?

Determine which room type has the most listings in each city.

**Concepts used:**

* Grouping
* Counting
* Ranking
* `ROW_NUMBER()`
* `RANK()`
* Window functions

---

### 4. Which city has the highest average number of reviews?

Calculate the average number of reviews per listing for each city and identify the city with the highest average.

**Concepts used:**

* `groupby()`
* `mean()`
* `AVG()`
* `GROUP BY`
* `ORDER BY`

---

### 5. Which hosts have the most listings?

Identify the hosts who manage the largest number of Airbnb listings.

**Concepts used:**

* `groupby()`
* `count()`
* `COUNT()`
* Sorting
* `GROUP BY`

---

### 6. What are the top 3 most expensive listings in each city?

Find the three highest-priced listings within every city.

**Concepts used:**

* `DENSE_RANK()`
* `PARTITION BY`
* `ORDER BY`
* Window functions
* CTEs
* Pandas `groupby()`
* `nlargest()`

---

### 7. Which listings are more expensive than their city's average price?

Compare each listing's price with the average price of listings in the same city.

**Concepts used:**

* Pandas `groupby()`
* `transform()`
* Boolean filtering
* SQL window functions
* `AVG() OVER()`
* `PARTITION BY`
* CTEs

---

### 8. Which cities have the highest percentage of entire homes/apartments?

Calculate the percentage of listings that are classified as `Entire home/apt` for each city.

**Concepts used:**

* Conditional aggregation
* `CASE WHEN`
* `AVG()`
* `GROUP BY`
* Pandas boolean conditions
* Grouping and aggregation

---

### 9. Does price differ significantly between room types?

Compare the average price of different room types to determine whether certain room types are generally more expensive.

**Concepts used:**

* `groupby()`
* `mean()`
* `AVG()`
* `GROUP BY`
* Aggregation

---

## 🐍 Pandas Skills Practiced

* Data cleaning
* Data exploration
* `groupby()`
* `agg()`
* `count()`
* `mean()`
* `value_counts()`
* `sort_values()`
* `nlargest()`
* `transform()`
* Boolean filtering
* Creating calculated columns
* Conditional logic

---

## 🗃️ SQL Skills Practiced

### Basic SQL

```sql
SELECT
FROM
WHERE
GROUP BY
ORDER BY
HAVING
```

### Aggregate Functions

```sql
COUNT()
AVG()
SUM()
MIN()
MAX()
```

### Advanced SQL

```sql
CASE WHEN
RANK()
DENSE_RANK()
ROW_NUMBER()
PARTITION BY
CTEs
Window Functions
```

---

## 🔄 Pandas vs SQL

One of the main goals of this project was to understand how similar analysis can be performed using both Pandas and SQL.

| Task                     | Pandas             | SQL                       |
| ------------------------ | ------------------ | ------------------------- |
| Group data               | `groupby()`        | `GROUP BY`                |
| Calculate average        | `mean()`           | `AVG()`                   |
| Count records            | `count()`          | `COUNT()`                 |
| Sort data                | `sort_values()`    | `ORDER BY`                |
| Conditional logic        | Boolean conditions | `CASE WHEN`               |
| Ranking                  | `rank()`           | `RANK()` / `DENSE_RANK()` |
| Group-level calculations | `transform()`      | Window functions          |
| Filter results           | Boolean filtering  | `WHERE` / `HAVING`        |

---

## 🎯 Project Objectives

* Practice data analysis with Pandas.
* Strengthen SQL skills.
* Solve real-world analytical questions.
* Understand grouping and aggregation.
* Practice SQL window functions.
* Learn how to perform similar analysis using Pandas and SQL.
* Extract meaningful insights from Airbnb listing data.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **Jupyter Notebook**
* **SQL**
* **PostgreSQL**
* **CSV**
* **GitHub**

---

## 📚 Key Takeaways

This project provided practical experience in analyzing real-world data using both **Pandas and SQL**.

A major focus was understanding how to translate analytical questions into queries and data manipulation steps, especially when working with **grouping, aggregation, ranking, and window functions**.

---

## 👨‍💻 Author

**Mohamed Anwar**

This project is part of my journey toward becoming a **Data Analyst**, with a focus on Python, Pandas, SQL, and data analysis.
