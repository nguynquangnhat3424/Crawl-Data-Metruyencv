# Project Introduction

## Objective:

* To identify the best novels.
* To discover trends in reading habits over the years and across different genres.

## Idea:

This project will build a 2-page dashboard:

* Page 1: A novel ranking based on a ranking criteria calculated using the author's 8 years of reading experience.
* Page 2: A report on reading trends with charts and detailed analysis.

NOTE: This dashboard's unique feature is its ability to **automatically update with the latest data**.

## Implementation:

**Data Crawling:**

* Use the requests library in Python to crawl data from the metruyencv.com API.

* Convert JSON data to DataFrame format for easy processing.

**Data Cleaning:**

* Remove errors, duplicates, and irrelevant data.

* Standardize data to ensure consistency.

**Data Modeling:**

* Divide the data into Fact_Books, Dim_Genres, Dim_Authors, and Dim_Translators tables.

* Design code to only crawl new data since the last run, ensuring data is always up-to-date.

**Importing Data into Power BI:**

* Use Power Query to import data from DataFrame into Power BI.

* Configure the path to the data storage directory for automatic updates when new data is available.

**Dashboard Creation:**

* Build the dashboard on Power BI based on the initial idea.

* Add detailed analysis to the "More information" section of the dashboard.

**Expected Results:**

* The dashboard provides users with helpful information in choosing good novels to read.

* Analysis of reading trends helps authors to have a direction of creation in line with readers' tastes.

* The dashboard has the ability to automatically update with the latest data, ensuring information is always accurate and up-to-date.

**Technologies Used:**

* Python

* Power BI
