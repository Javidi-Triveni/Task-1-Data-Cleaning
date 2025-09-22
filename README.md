# Data Cleaning Task - Customer Dataset

## 📌 Task Overview
This project demonstrates the process of cleaning a raw dataset (`raw_customer_data.csv`) into a usable cleaned dataset (`cleaned_customer_data.csv`).  
The workflow is implemented in **Python (Pandas)** inside a Jupyter Notebook.

---

## ⚙️ Steps Performed
1. **Loaded raw dataset** (`raw_customer_data.csv`)
2. **Inspected dataset** for missing values, duplicates, and inconsistent formats
3. **Removed duplicates**
4. **Handled missing values**  
   - Numeric columns → filled with median  
   - Categorical columns → filled with `'unknown'`  
5. **Standardized text values** (lowercase, trimmed spaces)
6. **Converted date columns** to proper datetime format (if any found)
7. **Saved cleaned dataset** as `cleaned_customer_data.csv`
8. **Generated summary report** in JSON format (`cleaning_summary.json`)

---

## 📂 Files in Repository
- `raw_customer_data.csv` → Original dataset
- `customer_data_cleaning.ipynb` → Jupyter Notebook with step-by-step cleaning
- `cleaned_customer_data.csv` → Final cleaned dataset
- `cleaning_summary.json` → Summary of cleaning operations (row counts, missing values handled, etc.)
- `README.md` → Project documentation

---

## ▶️ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/customer-data-cleaning.git
   cd customer-data-cleaning
   ```

2. Open the Jupyter Notebook  
   ```bash
   jupyter notebook customer_data_cleaning.ipynb
   ```

3. Run the cells step by step to reproduce the cleaning process.

---

## ✅ Deliverables
- Cleaned dataset: `cleaned_customer_data.csv`
- Cleaning summary: `cleaning_summary.json`
- Notebook: `customer_data_cleaning.ipynb`
- Documentation: `README.md`

---

## 📊 Summary of Changes (Example)
- Rows before cleaning: 10  
- Rows after cleaning: 9  
- Duplicates removed: 1  
- Missing values reduced: 6 → 1  

