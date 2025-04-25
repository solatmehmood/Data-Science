# Student Habits and Performance Analysis

This project uses **Pandas** to analyze how different student habits (like sleep, study hours, exercise, social media usage, etc.) impact academic performance.

## 📁 Dataset
- `student_habits_performance.csv` — contains student demographic data, habits, and academic grades.

## 📌 Project Objectives
- Explore the dataset structure and summary statistics.
- Clean the data: handle missing values and duplicates.
- Perform aggregations and group-based analysis.
- Create meaningful filters and new columns.
- Derive insights about habits that correlate with better or worse academic performance.

## ✅ Tasks

### 1. Data Loading and Exploration
- Load the dataset using `pd.read_csv()`
- Use `.info()`, `.describe()`, `.head()`, and `.tail()` to understand the structure

### 2. Data Cleaning
- Check for and handle missing values
- Remove duplicates if any

### 3. Data Understanding
- Explore unique values and distributions in categorical columns
- Use `.value_counts()` to analyze categories

### 4. Statistical Analysis
- Analyze average grades based on habits like sleep and study hours
- Use `.corr()` to find relationships between numeric values

### 5. Grouping & Aggregation
- Group data to find trends (e.g., by `gender`, `part_time_job`)

### 6. Sorting & Filtering
- Identify top students
- Filter based on custom criteria

### 7. Custom Analysis
- Examine the effect of sleep, social media usage, and jobs on grades

### 8. Feature Engineering
- Create new columns like `is_high_achiever` and `is_sleep_deprived`

### 9. Save Cleaned Data
- Export cleaned and filtered datasets for further use

## 💾 Output
- Cleaned data and key insights can be saved as CSV for reporting.

## 🛠 Tools Used
- Python 3
- Pandas

---

Feel free to fork and contribute new ideas or insights!