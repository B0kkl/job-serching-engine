# Python Job Listings Web Scraper

A Python-based web scraping and data analysis project that collects publicly available job listing data and transforms it into a structured dataset for analysis.

## Overview

This project demonstrates an end-to-end workflow for collecting job listing data from a web page, extracting relevant fields, validating the collected data, exporting it to CSV, and performing basic exploratory analysis.

The current implementation uses a learning-oriented job listings website as the initial data source. The scraping workflow is designed to be adaptable to other publicly accessible sources where automated data collection is permitted.

## Objectives

* Collect job listing data programmatically
* Parse HTML using Beautiful Soup
* Handle missing fields during extraction
* Structure scraped information into records
* Export the dataset to CSV
* Perform basic data-quality checks
* Analyze job locations and companies
* Visualize the most common job locations and companies

## Data Collected

| Field       | Description                         |
| ----------- | ----------------------------------- |
| `job_title` | Title of the advertised position    |
| `company`   | Company associated with the listing |
| `location`  | Location of the position            |
| `job_url`   | URL to the job detail page          |

## Technologies Used

* Python
* Requests
* Beautiful Soup
* Pandas
* Matplotlib
* CSV
* Jupyter Lab

## Project Workflow

```text
Web Page
   ↓
Requests
   ↓
HTML Response
   ↓
Beautiful Soup
   ↓
Data Extraction
   ↓
Data Validation
   ↓
CSV Dataset
   ↓
Pandas
   ↓
Exploratory Data Analysis
   ↓
Visualization
```

## Project Structure

```text
job-serching-engine/
│
├── python_job_listings_scraper.ipynb
├── data/
│   └── job_listings.csv
├── requirements.txt
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/B0kkl/job-serching-engine.git
```

### 2. Navigate into the project

```bash
cd job-serching-engine
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Lab

```bash
jupyter lab
```

Open:

```text
python_job_listings_scraper.ipynb
```

Run the notebook cells from top to bottom.

## Data Quality Checks

The project performs basic validation including:

* Missing-value checks
* Duplicate-record checks
* Record-count validation
* CSV output verification
* Unique company analysis
* Location frequency analysis

## Analysis

The collected dataset is used to identify:

* The most common job locations
* Companies with the highest number of listings
* The overall structure and quality of the collected data

The notebook also includes basic visualizations using Matplotlib.

## Future Improvements

The project can be extended into a more complete job-market data pipeline by adding:

* Job-description extraction
* Skill extraction using Natural Language Processing
* Job-category classification
* Salary extraction where available
* More advanced exploratory data analysis
* Interactive dashboards
* Database storage
* Automated scheduled scraping
* Multiple permitted job-listing sources
* Historical job-market tracking

## Learning Outcomes

This project demonstrates practical experience with:

* Web scraping
* HTML parsing
* Data extraction
* Data cleaning
* Data validation
* CSV data handling
* Pandas
* Exploratory Data Analysis
* Data visualization
* Reproducible Python workflows

## Author

**Hussein Mwachikumba**

Aspiring Data Analyst / Data Engineer with a background in ICT support, networking, software development, and automation.

## Disclaimer

This project is intended for educational and portfolio purposes. Always review and comply with a website's terms of service, robots.txt directives, and applicable laws before scraping or automating data collection.
