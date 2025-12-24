Exploratory Data Analysis (EDA) is the first and most critical step in any data science workflow.  
Before building models or drawing conclusions, you need to **understand your data**.

In this post, we’ll walk through a practical EDA workflow using Python.

---

## Why EDA Matters

EDA helps you:
- Understand data distributions
- Detect missing values and outliers
- Identify relationships between variables
- Avoid incorrect modeling assumptions

Good EDA often saves more time than it costs.

---

## Tools We’ll Use

The most common Python tools for EDA are:

- **pandas** – data manipulation
- **numpy** – numerical operations
- **matplotlib** – basic plotting
- **seaborn** – statistical visualizations

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns