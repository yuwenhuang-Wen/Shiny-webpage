# Shiny-webpage

## Project Overview
### This sql project aims to build an interactive webpage using R, by creating tables on local computer, creating relationships between tables, and querying data to show informations on the concert website

## Tools
- Query language: SQL
- Relational database management system: PostgresSQL (pgAdmin 4)
- webpage & database connection programming language: R (RPosgres & Shiny Packages)

## Step 1. Create Tables on PgAdmin 
- made connection with t
- created tables, extracted data from pre-made csv files, transformed data, Loaded data into tables
- ERD
![ERD](https://github.com/yuwenhuang-Wen/Shiny-webpage/blob/main/ERD.png)

## Step 2. Build webpage in R
- global.r
  - connect to the database
  - create variables that stores values returned from queries
- server.r:
  - construct user interface in details
  - Customize design with HTML 
- ui.r:
  - controls page leyer user interface  

## Webpages
![](https://github.com/yuwenhuang-Wen/Shiny-webpage/blob/main/homePage.png)
![](https://github.com/yuwenhuang-Wen/Shiny-webpage/blob/main/TourPage.png)
![](https://github.com/yuwenhuang-Wen/Shiny-webpage/blob/main/TourPage2.png)
![](https://github.com/yuwenhuang-Wen/Shiny-webpage/blob/main/TourPage3.png)
![](https://github.com/yuwenhuang-Wen/Shiny-webpage/blob/main/VideoInsert.png)
![](https://github.com/yuwenhuang-Wen/Shiny-webpage/blob/main/ProductPage.png)
![](https://github.com/yuwenhuang-Wen/Shiny-webpage/blob/main/ReservPage.png)
