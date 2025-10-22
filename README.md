# Feature Engineering & Data Preprocessing

This repository demonstrates core **feature engineering and preprocessing techniques** in machine learning. These steps prepare raw data to improve model performance and learning efficiency.

---

## Techniques Covered

### 1. Binning (Discretization)
- Converts continuous numeric data into discrete categories (bins).  
- **Example:** `Age → Teen / Adult / Senior`.

### 2. Transforming
- Changes feature distribution or scale to reduce skewness or outliers.  
- **Common Transformations:**  
  - `Log` → Reduce effect of large outliers  
  - `Square Root` → Reduce skewness  
  - `Box-Cox / Yeo-Johnson` → Make data more normal  
  - `Normalization` → Scale values between 0–1

### 3. Encoding
- Converts categorical data into numeric form for ML models.  
- **Types:**  
  - **Label Encoding** → Ordered categories  
  - **One-Hot Encoding** → Independent categories  
  - **Binary / Target Encoding** → High-cardinality categories

### 4. Scaling
- Standardizes feature ranges to ensure no feature dominates.  
- **Methods:**  
  - `Min-Max Scaling`  
  - `Standardization (Z-score)`  
  - `Robust Scaling`

### 5. Shuffling
- Randomly rearranges data to remove order bias and improve generalization.

---
