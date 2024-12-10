# -Coders_Boutique_task-

# Web Scraping and Analysis Pipeline for E-commerce Data

## Project Overview

This project was completed as part of a technical assessment for the Data Engineer Intern position at Coders Boutique. The goal was to build a pipeline that extracts, processes, and analyzes e-commerce data while integrating machine learning for predictive tasks. The solution demonstrates skills in web scraping, data preprocessing, machine learning, and database storage.

## Features

1. **Web Scraping**:
   - Extracted product details (name, price, ratings, and reviews) from a publicly available e-commerce website using Selenium.
   - Saved the scraped data in CSV format for further processing.

2. **Data Preprocessing**:
   - Handled missing values and duplicates in the data.
   - Normalized price and rating columns for consistency.

3. **Machine Learning**:
   - Developed a regression model to predict product ratings based on price and reviews using Scikit-learn.
   - Evaluated the model using metrics like RMSE.

4. **Data Storage**:
   - Stored the cleaned and processed data in an SQLite database.
   - Used SQLAlchemy for seamless database interactions.

5. **Automation**:
   - Automated the entire pipeline from scraping to prediction.
   - Implemented error handling and logging for better reliability.

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- Google Chrome and ChromeDriver
- Required Python libraries: `selenium`, `pandas`, `scikit-learn`, `sqlalchemy`, `sqlite3`

### Steps to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
# Web Scraping and Analysis Pipeline for E-commerce Data

## Project Overview

This project was completed as part of a technical assessment for the Data Engineer Intern position at Coders Boutique. The goal was to build a pipeline that extracts, processes, and analyzes e-commerce data while integrating machine learning for predictive tasks. The solution demonstrates skills in web scraping, data preprocessing, machine learning, and database storage.

## Features

1. **Web Scraping**:
   - Extracted product details (name, price, ratings, and reviews) from a publicly available e-commerce website using Selenium.
   - Saved the scraped data in CSV format for further processing.

2. **Data Preprocessing**:
   - Handled missing values and duplicates in the data.
   - Normalized price and rating columns for consistency.

3. **Machine Learning**:
   - Developed a regression model to predict product ratings based on price and reviews using Scikit-learn.
   - Evaluated the model using metrics like RMSE.

4. **Data Storage**:
   - Stored the cleaned and processed data in an SQLite database.
   - Used SQLAlchemy for seamless database interactions.

5. **Automation**:
   - Automated the entire pipeline from scraping to prediction.
   - Implemented error handling and logging for better reliability.

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- Google Chrome and ChromeDriver
- Required Python libraries: `selenium`, `pandas`, `scikit-learn`, `sqlalchemy`, `sqlite3`

### Steps to Run

1. Clone this repository
2. Install required dependencies
    pip install -r requirements.txt
3. Ensure ChromeDriver is installed and available in your PATH or the project directory.

4. python main.py
5. Output Files:

        Scraped data will be saved as ecommerce_data.csv.
        SQLite database file will be named ecommerce_data.db.
