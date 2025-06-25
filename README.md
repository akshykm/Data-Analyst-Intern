
##  Task 1: Data Cleaning and Preprocessing – Data Analyst Internship

### 🧹 Data Cleaning Steps Performed in Python:
###  Objective: 
To clean and preprocess a raw dataset by identifying and fixing missing values, duplicates, inconsistent formatting, and incorrect data types using **Python (Pandas)**.

### Dataset Used: **Hospital Appointment Data** (from Kaggle)

### Data Cleaning Steps Performed:
1. **Missing Values**
   * Checked using `.isnull().sum()`
   * No critical missing values detected

2. **Duplicate Rows**
   * Removed using `.drop_duplicates()`

3. **Standardized Text Fields**
   * `Gender`: converted to uppercase (e.g., `'F'`, `'M'`)
   * `No-show`: converted to lowercase (e.g., `'yes'`, `'no'`)
   * `Neighbourhood`: standardized to uppercase for consistency

4. **Formatted Date Columns**
   * Converted `ScheduledDay` and `AppointmentDay` to `datetime` format (`dd-mm-yyyy`)

5. **Renamed Columns**
   * Cleaned column names to be lowercase with underscores (e.g., `AppointmentDay` → `appointment_day`)

6. **Corrected Data Types**
   * `age`: ensured as integer
   * `PatientId`: converted from float to `int64`
   * Date fields: parsed into proper datetime objects

---

### 🧠 Key Learnings:

* Used **Pandas** for real-world data wrangling
* Practiced essential preprocessing steps like text normalization, date parsing, and column renaming
* Understood the importance of clean data before analysis or modeling

---

### 📂 Files in this Repo:

| File                       | Description                           |
| -------------------------- | ------------------------------------- |
| `task1_cleaning_script.py` | Python script with all cleaning steps |


---



### 🧹 Data Cleaning Steps Performed in Excel:

1. **Handled Missing Values**
   * Identified missing cells using **filters** and **conditional formatting**
   * No major null values found requiring imputation or deletion

2. **Removed Duplicates**
   * Used Excel’s **"Remove Duplicates"** feature under the *Data* tab to eliminate duplicate rows

3. **Standardized Text Values**
   * `Gender`, `Neighbourhood`, and `No-show` values were standardized using:
     * **UPPER()** and **TRIM()** functions to ensure uniform casing and remove extra spaces

4. **Formatted Date Columns**
   * Converted `ScheduledDay` and `AppointmentDay` to consistent **`dd-mm-yyyy`** format using **Format Cells**

5. **Renamed Column Headers**
   * Cleaned all column names to be lowercase, underscore-separated, and consistent (e.g., `AppointmentDay` → `appointment_day`)

6. **Checked Data Types**
   * Ensured:
     * `age` is numeric
     * `PatientId` values are integers
     * Date columns are recognized as valid Excel dates

---

### 🧠 Key Learnings:
* Used Excel for real-world data cleaning tasks
* Gained hands-on experience with Excel features like filters, formatting, data validation, and formula-based cleaning
* Reinforced understanding of data preprocessing essentials

---

### 📂 Files in this Repo:

| File                   | Description                                               |
| ---------------------- | --------------------------------------------------------- |
| `cleaned_dataset.xlsx` | Final cleaned dataset with all formatting and corrections |


