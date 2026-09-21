# 🎬 TMDb Movie Database SQL Analysis

### Relational Database Querying & Analysis with SQL

This project explores **The Movie Database (TMDb)** relational database through a series of SQL analysis tasks covering movies, actors, genres, production companies, and Oscars data.

The project demonstrates practical SQL skills including **filtering, sorting, pattern matching, joins, aggregations, date-based analysis, views, updates, and database normalization**.

---

## 📌 Project Overview

The TMDb database contains interconnected information about movies, cast members, genres, production companies, and award records.

The objective of this project was to use SQL to investigate the database and answer a series of analytical questions requiring different querying techniques.

Rather than relying on a single table, several questions required understanding the relationships between entities and selecting the appropriate SQL operations to extract meaningful results.

### Dataset

The database contains **12 relational tables** covering information such as:

* Movies
* Actors
* Cast
* Genres
* Production companies
* Oscars
* Keywords
* Other movie-related entities

The database was provided as a SQLite database and queried through a Jupyter Notebook using SQL magic commands.

---

# 🎯 Analytical Questions

The analysis investigated questions such as:

### Movies

* How many movies contain the word **"Spider"** in their title?
* What are the ten oldest movies in the database?
* How many movies meet specific release-date, popularity, and budget conditions?
* What genres does **The Royal Tenenbaums** belong to?

### Actors & Cast

* How many unique characters has **Vin Diesel** played?
* How many female actors have names beginning with the letter **N**?
* Which movies feature specific actors?

### Genres & Production Companies

* Which genre has the lowest average movie popularity?
* Which production companies have the highest average movie popularity?

### Oscars

* Who won the Oscar for **Actor in a Leading Role** in 2015?
* How many unique awards are represented?
* Which award category has the highest number of actor nominations?
* How can inconsistently formatted Oscar years be standardized?

### Database Design

* What SQL query can create a reusable view of movies featuring **Alan Rickman**?
* Which statements about database normalization are correct?

---

# 🛠️ Technical Skills Demonstrated

## SQL Fundamentals

The project applies core SQL techniques including:

* `SELECT`
* `WHERE`
* `ORDER BY`
* `LIMIT`
* `DISTINCT`
* `LIKE`
* `BETWEEN`
* `IS NULL`
* `GROUP BY`
* Aggregate functions
* Conditional filtering

---

## Relational Data Analysis

Several questions require working across related tables.

I used relational concepts to connect information such as:

**Movies → Cast → Actors**

and

**Movies → Genres**

and

**Movies → Production Companies**

This demonstrates the ability to reason about relationships between entities rather than treating a database as a flat table.

---

## Aggregation & Grouping

Aggregate analysis was used to investigate:

* Average movie popularity
* Counts of actors and awards
* Number of records matching specific conditions
* Production-company performance
* Genre-level statistics

Functions such as `COUNT()`, `AVG()`, and grouping logic allow the database to summarize large collections of records efficiently.

---

## Pattern Matching

Text-based analysis was used to identify records based on names and keywords.

Examples include:

* Movie titles containing **"Spider"**
* Keywords containing **"love"**
* Actor names beginning with **"N"**

This demonstrates practical use of SQL pattern matching with the `LIKE` operator.

---

## Date & Conditional Analysis

The project also includes queries requiring multiple conditions involving:

* Release dates
* Popularity scores
* Movie budgets
* Date ranges

This demonstrates how SQL can be used to combine multiple business conditions into a single analytical query.

---

## Views

One task required creating a reusable SQL **VIEW** containing information about movies featuring Alan Rickman.

The view combines:

* Movie titles
* Release dates
* Taglines
* Overviews
* Actor information

Views are useful for creating reusable subsets of relational data without repeatedly writing the underlying query.

---

## Data Updates & Standardization

The Oscars table contains historical year values stored in different formats.

For example:

`1932/1933`

instead of:

`1933`

The project examines how SQL string functions can be used to standardize the stored year value.

This demonstrates an important data-engineering concept:

> **Inconsistent data representation can affect downstream analysis and should be addressed before relying on the field for comparisons or reporting.**

---

# 🧠 Key SQL Concepts Applied

| Concept       | Application                              |
| ------------- | ---------------------------------------- |
| `SELECT`      | Retrieve required fields                 |
| `WHERE`       | Filter records                           |
| `ORDER BY`    | Sort movie records                       |
| `LIMIT`       | Restrict result sets                     |
| `DISTINCT`    | Identify unique values                   |
| `LIKE`        | Search text patterns                     |
| `BETWEEN`     | Filter date/numeric ranges               |
| `COUNT()`     | Count records                            |
| `AVG()`       | Calculate average popularity             |
| `GROUP BY`    | Analyze categories                       |
| `JOIN`        | Combine related tables                   |
| `CREATE VIEW` | Build reusable queries                   |
| `UPDATE`      | Standardize stored values                |
| Normalization | Understand relational database structure |

---

# 🔍 Analytical Approach

The general workflow followed was:

**Understand the question**

↓

**Identify the relevant table(s)**

↓

**Inspect the relationships between entities**

↓

**Select the appropriate SQL operations**

↓

**Filter / join / aggregate the data**

↓

**Validate the result**

↓

**Match the result to the analytical question**

This approach emphasizes not just writing SQL syntax, but understanding **which database operations are appropriate for a particular analytical problem**.

---

# 💡 What I Learned

This project strengthened my understanding of how SQL operates within a relational database rather than simply querying isolated tables.

Key areas reinforced through the analysis include:

### 1. Thinking relationally

Many analytical questions require identifying how tables connect before writing the query.

### 2. Translating questions into SQL logic

A natural-language question must be broken into conditions, fields, relationships, and aggregation requirements before it can be expressed in SQL.

### 3. Working with text data

Movie titles, actor names, keywords, and other text fields can be searched and filtered using pattern-matching techniques.

### 4. Aggregating data at different levels

The same database can be analyzed at movie, actor, genre, production-company, or award-category level depending on the analytical question.

### 5. Understanding data quality

The Oscar-year example demonstrates how inconsistent storage formats can create problems for analysis and why standardization matters.

---

# 📁 Project Structure

```text
TMDb-SQL-Analysis/
│
├── SQL_Exam.ipynb
├── TMDB.db
└── README.md
```

> The database file may not be included in the public repository if licensing, file size, or course-sharing restrictions apply.

---

# 💻 Tools

**SQL**  
**SQLite**  
**Jupyter Notebook**  
**Python / SQL Magic**

---

# 📊 Project Output

The primary output is an interactive Jupyter Notebook containing the SQL queries used to investigate the TMDb database.

The notebook demonstrates how different SQL techniques can be combined to answer analytical questions across a relational database.

---

# 🎯 Skills Demonstrated

**SQL Analysis · Relational Databases · Data Querying · Joins · Aggregation · Data Cleaning · Pattern Matching · Database Normalization · Views · Data Quality**

---

## Project Context

This project was completed as part of **DS 120: SQL for Data Science** and was designed to assess practical understanding of SQL and relational database concepts.

The work demonstrates my ability to translate analytical questions into SQL queries and work with interconnected datasets to extract specific results.