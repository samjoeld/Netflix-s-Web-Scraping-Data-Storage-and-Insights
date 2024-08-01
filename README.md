# Netflix Web Scraping and Data Export

## Overview

This project involves scraping Netflix's Top 10 movies data, storing the data in an SQL database, and exporting the results to an Excel file. The project aims to track the performance of movies over time based on criteria such as weeks in Top 10, hours viewed, runtime, and views.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Prerequisites](#prerequisites)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Data Schema](#data-schema)
6. [Export to Excel](#export-to-excel)
7. [License](#license)

## Project Structure

/netflix_scraping_project
│
├── /data
│ ├── netflix_data.db # SQLite database file
│ └── netflix_data.xlsx # Excel file output
│
├── /scraper
│ ├── scrape_netflix.py # Python script to scrape data
│ └── utils.py # Utility functions for scraping
│
├── /database
│ ├── create_schema.sql # SQL script to create database schema
│ └── insert_data.sql # SQL script to insert data
│
└── README.md # This file


## Prerequisites

- Python 3.x
- SQLite
- Pandas
- SQLAlchemy
- BeautifulSoup
- Requests
- OpenPyXL


