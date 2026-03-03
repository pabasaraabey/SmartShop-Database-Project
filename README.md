# SmartShop Ltd Database Project

## Overview
This project presents the database design and implementation for SmartShop Ltd, a mid-sized retail company operating both physical stores and an online platform.

## Technologies Used
- MySQL (Relational Database)
- Power BI (Business Intelligence & Data Visualisation)
- MongoDB (NoSQL Database for Reviews)

## Project Structure
- smartshop_database.sql → Contains table creation scripts, sample data insertion, and analytical queries.

## How to Run the Project

1. Open MySQL Workbench
2. Create a new database:
   CREATE DATABASE smartshop;
3. Open smartshop_database.sql
4. Execute the script
5. All tables and sample data will be created automatically.

## Power BI
Load the exported CSV files into Power BI and recreate relationships:
- Customers → Orders
- Orders → OrderItems
- Products → OrderItems
- Branches → Orders

## MongoDB
Database: smartshop_reviews
Collection: reviews
Contains sample customer review documents.
## MongoDB (NoSQL Implementation)

The MongoDB database named `smartshop_reviews` stores unstructured customer review data.

Collection: reviews

Fields include:
- customer_name
- branch
- product
- rating
- review_text
- review_date

To import the MongoDB data:

1. Open MongoDB Compass
2. Create database: smartshop_reviews
3. Create collection: reviews
4. Click Import Data
5. Select mongodb_reviews_sample.json
6. Import as JSON
