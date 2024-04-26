# IT Specialist Data Analytics 1

Welcome to "IT Specialist Data Analytics 1"! 🚀

Step right into a treasure trove of resources and code snippets crafted to enhance your grasp of the fundamental principles of Data Analytics, crucial for mastering the art of data analysis.

We've curated a rich array of topics, ranging from understanding the basics of Data, to the intricacies of Data Cleansing and Manipulation.

Let's embark on this exciting data journey together! 📊✨

Thank you for dropping by! 🙌

## Data Basics

Data is a collection of facts or values ​​that have not been processed or organized so that they do not have a clear meaning. Data can be numbers, letters, images, sounds, or anything else that can be captured and stored.

Data is Organized in matrix:
1. Row
2. Columns

<div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/3d41c139-6ee4-4bef-90b6-062f54ab4f3e" /></div>

### Categorical
1. Nominal
   
   <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/867eeb22-d976-4e2e-a3ed-d3282be14901" /></div>

2. Ordinal
   
    <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/5fbcf2bf-77db-4675-ab20-d2297783a1db" /></div>

### Numeric
1. Discrete

   <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/c874b6c7-4c9a-48c7-a8be-9cf47c890a38" /></div>

2.. Continues

    <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/bfa62fae-8e1a-4463-9482-d4e61406d75e" /></div>

### Data Categories
1. Quantitative
 
 <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/761a06b3-39ca-4097-a38c-d7fa59a480d8" /></div>

2. Qualitative

 <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/2f182697-3221-4b03-9add-853169d31348" /></div>

### Metadata
Metadata is a set of data that contains information about a piece of data to make it easier to manage. The form of metadata for a file will differ from that of another file. For instance, the content of information in a text will vary from that of an image or a photograph.

### Big Data
Big Data is a term used to describe a vast and intricate collection of data that is too extensive to be analyzed and processed using conventional techniques and methods. This term encompasses various types of data, including structured and unstructured data, as well as data generated from various sources such as social media, sensors, mobile devices, log files, and web servers.

## Data Manipulation

### 1. Import, Store and Export Data
1. Extract
2. Transform
3. Load

### 2. Data Cleansing

Fillna with Mode
 
 <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/e77475f7-2a3a-4153-8d1d-df616137b755" /></div>

Fillna with Median

 <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/33837e1a-2c55-41dd-91be-ab50524c831f" /></div>

Remove Special Character
 
 <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/cbe14eb4-677d-481d-8cb3-4b10ff823362" /></div>

Remove Duplicates

 <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/4fd6d08b-fd76-47cb-bbcd-0ca571d1d13a" /></div>

Drop
> Before
>  <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/f23f56c7-5c57-47f8-a05d-bfe9ab04aa9e" /></div>

> After
>  <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/37725541-eb8e-44b5-9c3e-b40ba366b777" /></div>


### 3. Organized Data:

1. Add a New Column
- We're going to manipulate the data by adding a new column, namely the "Status" column.

That's done not to alter the data values, but to facilitate the machine in reading the data.

<div align="center"><img src="https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/d0f41748-07d6-4121-9ec1-5721138956b0" /></div>

2. Filtering
   
    Subset the dataframe rows or columns according to the specified index labels.

     - We'd like to retrieve data of customers aged over 40 based on their gender.

<div align="center"><img src="https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/3b306366-4e1d-47c5-9500-deb5c09944a0" /></div>

3. Sorting
   
    The sort_values() function is the process of arranging data elements in a specific order, either ascending or descending, based on certain values or criteria.

<div align="center"><img src="https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/7e20c7b8-7062-4ccf-9d40-78e05a09e7ff" /></div>

4. Slicing or Get Dummies
* Convert categorical variable into dummy/indicator variables.
* Each variable is converted in as many 0/1 variables as there are different values. Columns in the output are each named after a value; if the input is a DataFrame, the name of the original variable is prepended to the value.

![image](https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/34b499d6-2637-4262-81fd-e3b4d12d1fc5)

![image](https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/70d6412f-3846-48d5-abff-c7af390edee9)

5. Rename
   
    The rename() function in pandas is used to rename columns or indexes in a DataFrame, allowing users to easily customize the names according to data analysis or presentation needs.

* Before:
![image](https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/66d713e3-ffad-4672-9373-44cad0d665d3)

* After:
![image](https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/6816435a-dbc4-4303-bda7-b6b12b1b81a8)


6. Transposing
   
    The transpose() function in Pandas is used to transpose DataFrames and Series. This will swap rows and columns, so rows will become columns and vice versa.

<div align="center"><img src="https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/a64ffd6a-3a8c-475f-9f60-82042433c6ad" /></div>

7. Truncating
   
    The truncate() function in Pandas is used to trim a DataFrame or Series by removing rows or columns from the beginning or end of the data according to the specified length. This is useful when you want to eliminate irrelevant data from the start or end of your dataset.

![image](https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/63277be0-2ee0-4f6b-ab02-069cd86d8feb)


### 4. Aggregate Data

1. Pandas.pivot()

    pandas.pivot(index, columns, values) function produces a pivot table based on 3 columns of the DataFrame. Uses unique values from the index/columns and fills them with values.

![image](https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/3d3d4f5b-4d10-44e0-b9d1-013e56063e91)

The result is

![image](https://github.com/Aisyahrahmap/IT-Specialist-Data-Analytics-1/assets/166115307/2549464e-fbe6-4518-80e5-9bd1fd44c0d6)

* Apart from that, we can also just create a pivot table without a chart.
![image](https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/66554e4e-9377-4d7a-8918-a445f56666ab)

* We can also grouping in Pivot, by adding one or more column to the index
![image](https://github.com/Vanz92x/IT-Specialist-Data-Analytics-1/assets/165736197/a66ce2b4-56a5-4938-bc55-5844e504370a)


2. Crosstab

    The crosstab() function especially when using Pandas, is used to create a crosstabulation of two or more variables. A cross table is a table that shows the frequency of appearance of a combination of values for these variables.
    Syntax : `pd.crosstab(df.Age, df.Gender)`

<div align="center"><img src= "https://github.com/difasafrina/IT-SPECIALIST-Data-Analytic-1/assets/113273578/cecbf5a4-f247-40f5-ab88-b3714dec557a"/></div>

3. Group By

    Using the group by function, you can group rows of data based on specific values in one or more columns, and then apply aggregation operations such as sum, count, mean, etc. in each group.

 <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/c36b2a4e-7d4c-4bca-970c-6bed1ff793ad" /></div>

4. Concat

    The concat() function in data manipulation is generally used to combine dataframes either row-wise or column-wise.

> syntax:

> `df1 = df[['ID','Gender', 'Age']][0:5]
> df2 = df[['ID', 'Profession','Age']][0:5]`

**df1**

 <div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/8b25c72f-d5de-4d32-8d25-39193873352d" /></div>

**df2**
<div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/e0d3ee9c-a589-4ef8-bd4f-88f789925d50" /></div>

**concat**
<div align="center"><img src="https://github.com/salsanssp/IT-Specialist-Data-Analytic-1/assets/166114037/e7e26340-9d83-4da5-8a1b-9feb3460a594" /></div>

5. Merge

    The .merge() method is used to merge DataFrame or Series. It's equivalent to SQL join methods (left join, right join, inner join, and outer join), but we need to specify the tables on the left and right sides, as well as the key columns for merging.
<div align="center"><img src= "https://github.com/difasafrina/IT-SPECIALIST-Data-Analytic-1/assets/113273578/c7adb202-4103-4031-8b0b-8e0bf416f9d0"/></div>


# Data Analytics Journey 🌟
Thank you for diving into "IT Specialist Data Analytics 1" where you'll find a treasure trove of resources and code snippets to master data analytics. From unraveling data mysteries to cleaning and manipulating data, let's embark on this thrilling journey together! 🚀 Happy analyzing! 📊✨


