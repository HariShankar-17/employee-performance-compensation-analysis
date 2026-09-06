# Employee Performance & Compensation Analysis

## 📌 Project Overview

An exploratory data analysis project focused on understanding the relationship between employee salary and performance, and identifying departments with strong talent.

## 🎯 Business Problem

- Does higher salary correspond to better employee performance?
- Which departments have the strongest talent?

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## 🔍 Concepts Practiced

- Data exploration & cleaning
- Descriptive statistics
- Conditional filtering & Boolean masking
- `apply()`
- `query()`
- `replace()`
- `np.where()`
- `np.select()`
- Aggregations with `groupby()` and `agg()`
- `transform()` for department-level benchmarks
- Feature engineering
- Employee-level comparative analysis
- Data visualisation
- Extracting business insights

## 📊 Business Insights

### 1. Which department has the highest average salary?

Finance has the highest average salary at approximately **103.3K**, followed by IT, HR, and Sales.

### 2. Which department has the strongest average performance?

Finance has the highest average performance score at approximately **88.3**, followed by HR, IT, and Sales.

### 3. Is there an apparent relationship between experience and salary?

There appears to be a **positive relationship** between experience and salary, as more experienced employees generally tend to earn higher salaries. However, the relationship is not perfectly consistent, since some highly experienced employees have relatively lower salaries.

### 4. Which employees are high performers relative to their department?

Employees **B (IT), E (HR), H (Sales), and J (Finance)** are high performers, as each has both an above-department-average salary and an above-department-average performance score.

### 5. Are there departments where employees have relatively high performance despite lower salaries?

Yes. **HR and Sales** have lower average salaries than Finance while still having relatively strong-performing employees.

HR is particularly notable, with an average performance score of approximately **84.3** despite an average salary of approximately **68.3K**.

### 6. What should HR potentially investigate?

HR could investigate whether compensation is appropriately aligned with **performance, experience, and job responsibilities**.

## 📁 Project Structure

```text
employee_performance_compensation_analysis.ipynb
README.md
