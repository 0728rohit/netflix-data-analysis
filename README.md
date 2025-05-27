# 📊 Netflix Titles Data Analysis

This project involves cleaning and analyzing a dataset of Netflix titles to uncover trends in content type, release patterns, and more. The final cleaned dataset is stored in Excel format, and the analysis was performed using Google Colab.

---

## 📁 Project Files

- `netflix_titles.csv` — **Raw dataset** directly sourced for the project.
- `netflix_titles_cleaned.xlsx` — **Cleaned and preprocessed** version used for analysis.
- `projects_pynb.ipynb` — **Notebook** containing the data cleaning steps and basic exploratory analysis.

---

## 📚 Dataset Details

The dataset includes information such as:

- Title, Type (Movie/TV Show)
- Director and Cast
- Country of Origin
- Date Added and Release Year
- Rating and Duration
- Description

A new column `year_added` was created to analyze trends in content additions over time.

---

## 🧹 Data Cleaning Highlights

- Filled missing values in key fields like `director`, `cast`, `country`, `rating`, and `duration`.
- Converted `date_added` to datetime format and extracted `year_added`.
- Removed entries with null `date_added`.

The cleaned data was saved as `netflix_titles_cleaned.xlsx`.

---

## 👤 Author

**Rohith Bharadwaj**
