Task 1 – Data Cleaning and Preprocessing
Objective
This project focuses on cleaning and preparing a raw dataset from Kaggle (**Medical Appointment No Shows**) using **Microsoft Excel**.  
The goal was to identify and fix common data issues such as missing values, duplicates, inconsistent formats, and incorrect data types, resulting in a clean and analysis-ready dataset.
Dataset Description
The dataset (`KaggleV2-May-2016.csv`) contains information about medical appointments in Brazil and whether patients showed up or not.  
Key columns include:
- **PatientId**
- **AppointmentID**
- **Gender**
- **ScheduledDay**
- **AppointmentDay**
- **Age**
- **Neighbourhood**
- **Scholarship**
- **No-show**
### ⚙️ Tools Used
- **Microsoft Excel** – for data cleaning and preprocessing  
- **GitHub** – for version control and project sharing
### 🧠 Steps Performed

#### 1. Data Inspection
- Reviewed the dataset to identify missing values, duplicates, and inconsistent entries.

#### 2. Handling Missing Values
- Checked for empty cells using “Go To Special” and filters.
- Filled or replaced missing text with “Unknown” and numerical gaps with averages (where applicable).

#### 3. Removing Duplicates
- Used **Data → Remove Duplicates** to eliminate repeated records across all columns.

#### 4. Text Standardization
- Converted inconsistent text entries (e.g., “male”, “FEMALE”) to Proper Case using the `PROPER()` function.
- Standardized categorical values like **Gender** and **No-show**.

#### 5. Date Formatting
- Split combined date-time fields (e.g., `ScheduledDay`) into separate **Date** and **Time** columns.
- Formatted dates consistently as `dd-mm-yyyy`.

#### 6. Column Name Cleaning
- Renamed columns to lowercase, removing spaces and special characters (e.g., `No-show` → `no_show`).

#### 7. Outlier Check
- Reviewed the **Age** column for unrealistic values (e.g., negative or excessively high numbers) and corrected them.
### 📁 Project Files
| File Name | Description |
|------------|--------------|
| `KaggleV2-May-2016.csv` | Original raw dataset from Kaggle |
| `Medical_Appointment_NoShow_Cleaned.xlsx` | Cleaned and processed dataset |
| `Task1_Summary.pdf` | Summary of cleaning process and outcomes |
| `README.md` | Project documentation |
### ✅ Key Learning Outcomes
- Identifying and correcting common data quality issues  
- Using Excel tools and formulas for data preprocessing  
- Preparing clean, structured data suitable for analysis  
- Documenting workflow clearly for reproducibility
### 💡 Next Steps
Future work could include:
- Performing exploratory data analysis (EDA) on the cleaned dataset  
- Visualizing attendance trends by gender, age, and scholarship status  
- Building predictive models using Python (Pandas and Scikit-learn)

---

 Author
**Gift Edeko**  
*Data Analyst Intern | Excel & Data Cleaning Enthusiast*  ---
