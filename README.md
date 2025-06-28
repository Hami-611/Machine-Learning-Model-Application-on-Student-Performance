# 🎓 Student Performance Regression Project

This project predicts students' **math scores** based on demographic, educational, and test preparation factors using various regression models in Python.

---

## 📁 Dataset

- **Source**: `StudentsPerformance_3_lyst1729690388778.csv`
- **Rows**: 1000
- **Columns**: 8
- **Target Variable**: `math score`
- **Features Used**:
  - gender
  - race/ethnicity
  - parental level of education
  - lunch
  - test preparation course
  - reading score
  - writing score

---

## 🛠️ Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split, RandomizedSearchCV
from sklearn.preprocessing import OneHotEncoder, StandardScaler
from sklearn.compose import ColumnTransformer
from sklearn.metrics import r2_score, mean_absolute_error, mean_squared_error

from sklearn.linear_model import LinearRegression, Ridge, Lasso
from sklearn.neighbors import KNeighborsRegressor
from sklearn.tree import DecisionTreeRegressor
from sklearn.ensemble import RandomForestRegressor
```
---
## 👩‍💻 Author
Hamika, Aeronautical Engineering Graduate transitioning into IT with skills in Python, ML, and Data Science.

You can save this content into a file named `README.md` in your project directory. Let me know if you want the README tailored to a GitHub-specific format (with badges, etc.) or exported as a downloadable `.md` or `.pdf` file.

