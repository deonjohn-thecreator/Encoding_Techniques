# Transforming Categorical Data into Numerical Format

## Comparative Study of Label Encoding and One-Hot Encoding Techniques

### Objective
The objective of this task is to understand and compare Label Encoding and One-Hot Encoding techniques for converting categorical data into numerical form.

---

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Google Colab

---

## Dataset Used
A dummy hospital dataset was created containing categorical columns such as:
- Gender
- AppointmentType
- City

---

## Steps Performed

### 1. Dataset Creation
Created a sample hospital dataset using Pandas DataFrame.

### 2. Dataset Inspection
Used:
- `df.info()`
- `df.describe()`

to inspect data types and dataset structure.

### 3. Label Encoding
Applied Label Encoding using:
```python
from sklearn.preprocessing import LabelEncoder
