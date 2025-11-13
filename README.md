# Data Preprocessing and Quality Improvement

📌 Description
This project is part of a Data Analyst Internship Task focused on cleaning and preprocessing the KaggleV2-May-2016 (Medical Appointment No-Shows) dataset.
The dataset provides information about patients, their scheduled appointments, and whether they attended or missed those appointments.

The main goal was to transform the raw data into an analysis-ready format by correcting structural inconsistencies, standardizing columns, and validating data integrity.
The final cleaned dataset (Cleaned_KaggleV2.xlsx) is fully prepared and suitable for data analysis, dashboard development, and predictive modeling.

# Key Tasks Performed

  Converted all column names to snake_case format.

 Fixed patient_id formatting (converted to text to avoid loss of precision).

 Standardized date fields (scheduled_day, appointment_day) → dd-mm-yyyy.

 Normalized categorical values (M → Male, F → Female).

 Ensured correct data types (integer, string, datetime).

⚠️ Removed invalid entries (e.g., age = -1, inconsistent dates).

✅ Verified no missing values and no duplicate rows.

# 📊 Dataset Information
Source: Medical Appointment No-Shows dataset

Raw file:<a href=https://github.com/Ramyakrishnan-22/Data-Cleaning-and-Preprocessing/blob/main/Cleaned_KaggleV2.xlsx

Cleaned file: <a href="https://github.com/Ramyakrishnan-22/Data-Cleaning-and-Preprocessing/blob/main/Cleaned_KaggleV2.xlsx">Raw_data</a>


Cleaned File: Cleaned_KaggleV2.xlsx

Rows: 110,000

Columns: 14

# 🛠️ Data Cleaning Highlights
# Column Renaming

Converted all column headers to lowercase with underscores.
   * Example:
     
    PatientId → patient_id
    No-show → no_show
    
# Patient ID Fix

 Converted to text format to preserve ID integrity
 
# Date Conversion	

 Removed “T/Z” characters and formatted dates
 
# Text Normalization

  * Normalized gender values:
    
    M → Male
    
    F → Female
    
# Outlier Removal
*Removed unrealistic 

   age = -1 record
   
# Date Consistency Check
Removed rows where scheduled_day > appointment_day

# Data Validation
Checked for missing, duplicate, or invalid values
*Ensured correct data types:

age → integer

patient_id → string

date columns → datetime

# 📂 Output

🧾 Cleaned_KaggleV2.xlsx — final structured dataset
# ✅ Status
The dataset has been successfully cleaned, validated, and stored in a structured format for further use.
This ensures reliable results in downstream tasks such as:

Data analysis

Dashboarding

Machine learning
