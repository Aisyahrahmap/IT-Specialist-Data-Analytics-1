- We will handle missing values in the column "Var_1" through imputation.

Imputation is replace missing values with a statistical measure such as mean, median, or mode of the column.

![image](https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/7e7d5f97-4f2b-4057-bee3-49e88e13710b)

This method of imputation is useful for categorical or discrete data where replacing missing values with the most common value can preserve the distribution of the data to some extent.

# Data Manipulation

DataFrame manipulation in Pandas involves editing and modifying existing DataFrames.

## 1. Add a New Column
- We're going to manipulate the data by adding a new column, namely the "Status" column.

That's done not to alter the data values, but to facilitate the machine in reading the data.

![image](https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/d0f41748-07d6-4121-9ec1-5721138956b0)

## 2. Filtering
Subset the dataframe rows or columns according to the specified index labels.

- We'd like to retrieve data of customers aged over 40 based on their gender.

![image](https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/3b306366-4e1d-47c5-9500-deb5c09944a0)

 ## 3. Pandas.pivot() 
pandas.pivot(index, columns, values) function produces a pivot table based on 3 columns of the DataFrame. Uses unique values from the index/columns and fills them with values.

![image](https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/3d3d4f5b-4d10-44e0-b9d1-013e56063e91)

The result is

![image](https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/2549464e-fbe6-4518-80e5-9bd1fd44c0d6)

