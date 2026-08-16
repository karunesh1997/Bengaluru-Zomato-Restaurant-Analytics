# 🍽️ Bengaluru Zomato Restaurant Analytics

An end-to-end exploratory data analysis project on Bengaluru's restaurant ecosystem using Zomato restaurant data. The project analyzes restaurant popularity, ratings, pricing, cuisines, locations, customer engagement, online ordering, table booking, and geographic distribution to uncover meaningful business insights.

---

## 📌 Project Overview

The restaurant industry generates large amounts of data related to customer preferences, pricing, ratings, restaurant categories, cuisines, and service offerings.

This project analyzes a Bengaluru Zomato dataset to understand:

- Where restaurants are concentrated across Bengaluru
- Which restaurant chains have the largest presence
- Which cuisines and restaurant types are most popular
- How restaurant ratings are distributed
- Which restaurants receive the highest customer engagement
- How much customers typically spend for two people
- Whether pricing differs based on online ordering availability
- Whether table booking and online ordering are associated with restaurant characteristics
- How restaurant popularity varies across locations

The project follows an end-to-end data analytics workflow covering data cleaning, exploratory data analysis, visualization, statistical exploration, and geographic analysis.

Machine Learning can also be extended from this analysis to predict restaurant ratings and segment restaurants based on pricing, popularity, and customer ratings.

---

## 🎯 Business Questions

The analysis aims to answer the following questions:

1. Which locations in Bengaluru have the highest concentration of restaurants?

2. Which restaurant chains have the largest number of outlets?

3. What are the most common restaurant and food types?

4. Which cuisines are most popular among Bengaluru restaurants?

5. What is the typical cost of a meal for two people?

6. Which restaurants are the most expensive and least expensive?

7. How are restaurant ratings distributed?

8. Which restaurants receive the highest number of customer votes?

9. Is there a relationship between restaurant ratings and customer votes?

10. Does restaurant pricing differ between restaurants that accept online orders and those that do not?

11. How does table-booking availability vary across restaurants?

12. Which Bengaluru locations have the highest restaurant density?

13. Are highly rated restaurants also more popular in terms of customer votes?

14. Can restaurant characteristics be used to predict restaurant ratings?

15. Can restaurants be segmented based on their ratings, popularity, and pricing?

---

## 📊 Dataset

The dataset contains restaurant-level information for restaurants listed on Zomato in Bengaluru.

### Important Features

| Feature | Description |
|---|---|
| `name` | Restaurant name |
| `online_order` | Whether online ordering is available |
| `book_table` | Whether table booking is available |
| `rate` | Restaurant rating |
| `votes` | Number of customer votes |
| `location` | Restaurant location |
| `rest_type` | Type/category of restaurant |
| `cuisines` | Cuisines offered |
| `approx_cost(for two people)` | Approximate cost for two people |
| `listed_in(type)` | Category in which the restaurant is listed |

---

## 🧹 Data Cleaning

The raw dataset required several preprocessing steps before analysis.

### Cleaning performed

- Removed duplicate records
- Handled missing values
- Converted restaurant ratings into numerical format
- Removed `/5` from rating values
- Converted approximate cost into numerical format
- Removed commas from cost values
- Converted votes into numeric format
- Checked data types and dataset structure
- Prepared categorical and numerical variables for analysis

### Example

Raw rating:

```text
4.1/5
3.8/5
4.5/5

Converted rating:
4.1
3.8
4.5
