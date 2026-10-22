# web-scraping-books

# Property Listings Data Quality Pipeline

A beginner-friendly data engineering project built using Python, Pandas, and SQLite to clean, validate, and analyse property listing data.

## 📌 Project Overview

This project demonstrates a simple ETL (Extract, Transform, Load) workflow that processes property listing data and prepares reliable data for analysis.

The pipeline identifies duplicate records, handles missing values, rejects invalid property prices and areas, and loads validated records into a SQLite database.

## 🎯 Objectives

- Process raw property listing data using Python and Pandas.
- Remove duplicate records.
- Identify and handle missing values.
- Validate property prices and areas.
- Load clean data into a SQLite database.
- Use SQL queries to check data quality and analyse property prices by city.

## 🛠️ Technologies Used

- **Python** — pipeline logic
- **Pandas** — data cleaning and transformation
- **SQLite** — database storage
- **SQL** — data quality checks and business analysis

## ⚙️ Pipeline Workflow

1. **Extract:** Read sample property listing data.
2. **Transform:** Remove duplicates and handle missing or invalid values.
3. **Load:** Store validated records in SQLite.
4. **Validate:** Use SQL queries to check record counts, unique IDs, prices, and property areas.
5. **Analyse:** Calculate property counts and average prices by city.

## 🧹 Data Quality Rules

- Property IDs must be unique.
- Missing property IDs, cities, prices, and areas are excluded.
- Property prices must be greater than zero.
- Property areas must be greater than zero.

## 📊 Expected Results

The sample dataset contains seven input rows, including a duplicate record and invalid values.

After cleaning, three valid property records should remain.

The pipeline also generates a SQL quality report and city-wise property analysis.

## 🚀 How to Run

1. Install Python 3.
2. Install Pandas:

   ```bash
   pip install pandas
   ```

3. Run the pipeline:

   ```bash
   python property_pipeline.py
   ```

SQLite is included with standard Python installations, so a separate database server is not required.

You can also run the code in Google Colab without installing Python locally.

## 📁 Project Structure

```text
property-listings-data-quality/
├── property_pipeline.py
└── README.md
```

The SQLite database is generated when the pipeline runs.

## 📚 Key Learnings

- Understanding ETL pipeline fundamentals.
- Implementing data quality checks.
- Working with Python, Pandas, and SQL.
- Loading data into a relational database.
- Converting raw data into analysis-ready information.

## 🔮 Future Improvements

- Extract real property data from permitted websites or public APIs.
- Add automated data quality reports.
- Implement logging and exception handling.
- Add unit tests and automated pipeline execution.

## 👩‍💻 Author

**Sathyaruba**

GitHub: https://github.com/Sathya-2006

---

*This project currently uses sample property data for learning and demonstration. Website scraping and API extraction are planned future enhancements.*
