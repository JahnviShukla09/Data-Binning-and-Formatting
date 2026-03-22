# 📊 STUDY OF DATA BINNING AND DATA FORMATTING USING PYTHON

Name – Jahnvi Shukla <br/>
Branch – ENTC A3 <br/>
PRN – 25070123055 <br/>

---

## 🎯 Aim

To study and perform **data binning and data formatting techniques using Python and the Pandas library**.

---

## 📘 Introduction

In data analysis, raw numerical data is often difficult to interpret directly. **Data binning** helps in grouping continuous data into categories, making it easier to understand patterns.

**Data formatting** ensures that the dataset is consistent and properly structured by converting data types and standardizing values.

Python, with the help of **Pandas and NumPy**, provides powerful tools to perform binning and formatting efficiently.

---

## 📚 Theory

Data binning is a technique used to **divide continuous numerical data into discrete intervals (bins)**. This helps in simplifying data and identifying patterns. In Python, binning is performed using the `pd.cut()` function, where data is grouped into ranges and labeled accordingly (e.g., Low, Medium, High).

Binning is useful in:

* Reducing data complexity
* Improving data visualization
* Categorizing numerical data

Another important concept is **data formatting**, which ensures that data is stored in a consistent format. This includes:

* **Data type conversion** using `.astype()` (e.g., int to float)
* **Text formatting** using string functions like `.str.upper()`
* **Handling categorical data types**

Formatting helps avoid errors and improves data readability.

Additional operations such as **sorting and finding unique values** are also used to better organize and understand the dataset.

By using Pandas functions, data can be easily transformed into a structured and meaningful form.

---

## ⚙️ Procedure

1. Import **Pandas and NumPy libraries**.
2. Create a dataset containing product details such as price and units sold.
3. Perform **data binning on Price** using `pd.cut()` to classify into Low, Medium, and High categories.
4. Perform **data binning on Units Sold** to classify sales levels.
5. Convert data types using `.astype()` where required.
6. Convert text values into uppercase using `.str.upper()`.
7. Sort the dataset using `sort_values()`.
8. Display unique category values using `unique()`.
9. Create another dataset (food delivery data).
10. Apply binning on:

* Delivery Time
* Order Value
* Distance

11. Convert columns into proper data types.
12. Format text values and sort final dataset.

---

## 📊 Observations / Result

* Price was categorized into **Low, Medium, and High** using binning.
* Sales were classified into **Low, Medium, and High Sales**.
* Some values outside bin range resulted in **NaN**.
* Data types were successfully converted (int → float).
* Product names were standardized to **uppercase**.
* Sorting helped organize data in ascending order.

For second dataset:

* Delivery time categorized into **Short, Medium, Long**
* Order value categorized into **Affordable, Luxe, Gourmet**
* Distance categorized into **Close, Medium, Far**

Final datasets became **well-structured, categorized, and easy to analyze**.

---

## 🛠️ Tools / Libraries Used

* Python
* Google Colab / Jupyter Notebook
* Pandas Library
* NumPy Library

---

## 💡 Applications

* Data preprocessing in data science
* Market and sales analysis
* Customer segmentation
* Data visualization preparation
* Business analytics

---

## ✅ Advantages

1. Simplifies complex numerical data
2. Helps in better data interpretation
3. Improves visualization and analysis
4. Ensures consistency in dataset
5. Reduces errors due to improper formats
6. Makes data ready for further processing

---

## 🏁 Conclusion

Data binning and formatting are essential techniques used to **simplify and organize data**. Binning helps in converting continuous data into meaningful categories, while formatting ensures consistency and correctness of data. Using Python and Pandas, these operations can be performed efficiently, making the dataset suitable for analysis.


