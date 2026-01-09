# SCT_DS_Task1 
## Data  Visualization - Bar Chart and Histogram

---

## 📌 Task Description
Create a **bar chart or histogram** to visualize the distribution of a **categorical or continuous variable**, such as the distribution of **ages or genders in a population**.

---

## 🎯 Objective
To understand how data visualization techniques like **bar charts** and **histograms** help in analyzing categorical and continuous data from a dataset.

---

## 📂 Dataset Used
- File Name: `food_order.xls`
- Format: Excel (.xls)
- Description:  
  The dataset contains food order information such as:
  - Day of the week
  - Delivery time
  - Order cost
  - Ratings

---

## 🛠 Tools & Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- xlrd (for reading `.xls` files)

---

## 📊 Visualizations Created

### 1️⃣ Bar Chart (Categorical Variable)
- Variable Used: `day_of_the_week`
- Purpose:  
  To visualize the number of orders placed on **Weekdays vs Weekends**.

### 2️⃣ Histogram (Continuous Variable)
- Variable Used: `delivery_time`
- Purpose:  
  To visualize the frequency distribution of delivery times.

---

## ⚙ Execution Steps

1. Open **Google Colab**
2. Upload the dataset `food_order.xls`
3. Install required dependency:
   ```python
   !pip install xlrd
