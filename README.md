# Detecting-Outliers-in-a-Dataset

Code to detect outliers in a given dataset (Iris.csv):

In this code I have taken the Widely available Iris dataset to perform the Outlier Detection Analysis

Mathematical Explanation for Calculating the Outliers:

Quartiles divide the entire set into four equal parts. So, there are three quartiles, first, second and third represented by Q1, Q2 and Q3, respectively. Q2 is nothing but the median, since it indicates the position of the item in the list and thus, is a positional average.

$$ IQR = Q3 - Q1 $$

Calculate your upper limit : 
$$UL = Q3  +  (1.5 * IQR)$$
Calculate your lower limit : 
$$LL = Q1  –  (1.5 * IQR)$$

All Values that fall below the lower limit are classified as lower outliers. Likewise, all values that fall below the upper limit as classified as upper outliers.


Contents:
- Exploratory data analysis of Iris.csv
- Box plot of the columns
- Identifying the columns which have outliers through Data Visualization
- Printing those outliers with their corresponding values, column name and row.
