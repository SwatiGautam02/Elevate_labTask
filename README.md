# 🛍️ Mall Customer Segmentation Analysis

This project performs **data cleaning** and **basic analysis** on a Mall Customer Segmentation dataset using Python. The goal is to clean raw customer data and prepare it for further analytics and visualization tasks.

---

## 📁 Dataset

The dataset contains details about mall customers, including:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

**File used:** `mall_customer_segmentation_large.csv`

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Google Colab (for running code)

---

## ✨ Tasks Performed

### ✅ Data Cleaning Steps:
1. Handled missing values
2. Removed duplicate entries
3. Standardized inconsistent text (like gender entries)
4. Renamed columns for consistency
5. Exported cleaned dataset as `mall_customer_cleaned.csv`

### 🔍 Analysis You Can Try Next:
- Age distribution of customers
- Average spending by income groups
- Gender-based purchasing behavior
- Customer segmentation using K-Means clustering

---

## 🚀 How to Run

1. Clone the repo or upload files to Google Colab
2. Upload the CSV file (`mall_customer_segmentation_large.csv`)
3. Run the Python script `data_cleaning_script.py` (or the code in `notebook.ipynb`)
4. Get the cleaned output file for analysis

---

## 📊 Sample Output (after cleaning)

| CustomerID | Gender | Age | Income (k$) | Spending Score |
|------------|--------|-----|-------------|----------------|
| 1          | Male   | 19  | 15          | 39             |
| 2          | Female | 21  | 81          | 6              |

---

## 📎 License

This project is open-source and free to use for learning and educational purposes.

---



