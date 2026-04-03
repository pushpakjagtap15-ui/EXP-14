# Experiment No: 14  
**Title:** Data Normalization and Turning Categorical Variables into Quantitative Variables in Python  

---

## Student Details  
- **Name:** Pushpak Jagtap  
- **PRN:** 25070123148  
- **Branch:** Electronics and Telecommunication Engineering (ENTC)  
- **Batch:** 2025–2029 (A1)  

---

## Aim  
To study and perform data normalization and convert categorical variables into quantitative variables using various Python functions and operations.  

---

## Theory  

### 1. Data Normalization  
Data normalization scales numerical data into a common range so all features contribute equally.  

- **Min-Max Normalization:** Scales values between 0 and 1 using `min()` and `max()`.  
- **Z-score Normalization (Standardization):** Uses mean and standard deviation (`mean()`, `std()`) to measure deviation from average.  
- **Decimal Scaling:** Shifts decimal points by dividing with powers of 10.  

**Useful Functions:**  
- `describe()` → summary statistics  
- `dtypes` → identify numerical columns  
- `loc[]`, `iloc[]` → select specific columns for normalization  

---

### 2. Turning Categorical Variables into Quantitative Variables  
Categorical variables (e.g., Gender, Payment Method, Product Category) must be encoded into numerical form for analysis.  

- **Label Encoding:** Assigns numeric values to categories.  
  - Example: Male → 0, Female → 1  
  - Functions: `LabelEncoder()`, `fit_transform()`  

- **One-Hot Encoding:** Creates binary columns for each category.  
  - Example: Electronics → [1,0,0]  
  - Function: `get_dummies()`  

- **Dummy Encoding:** Similar to One-Hot but removes one column to avoid redundancy.  
  - Function: `get_dummies(drop_first=True)`  

---

## Conclusion  
Data normalization and categorical variable transformation techniques were successfully studied using various Python functions and operations.  
