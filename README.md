# Data-Cleaning
The project highlights key steps for transforming raw(dirty) data into usable(clean) data.

**Data Cleaning** is a stage in the data preparation process that involves fixing errors, identifying inconsistencies, and generally improving the quality and reliability of data before it can be used for analysis. This process is carried out early in the analytics cycle before building advanced Machine Learning models or generating insights. If done properly, Data Cleaning improves the accuracy of decisions without compromising vital data, thereby avoiding the Garbage in Garbage out (GIGO) situation.

Data cleaning is a skillset analysts rarely get a chance to develop while learning becasue most of the online datasets are curated with little or not errors to work on. We often jump straight into analysis after performing basics tasks like dropping duplicates and missing values. However, this not the case with real-life datasets. It is often said that most o the analyst time (60 -80 percent) is spent on wrangling data. Hence the importance of this skillset. Manually cleaning data is a tedious process. However, the Python Pandas library has a range of techniques (methods) that help transform raw data to usable form in an efficient manner. These techniques have been applied in this project to convert the **dirty_data** dataframe to **clean_data**. 

In order to create a comprehensive data cleaning project, data used for this project was created from a combination of online datasets with each column edited to address common data cleaning issues like; changing datatypes, cleaning strings, changing column names, etc.

After getting a better overview of the dataset from the EDA section, this section focuses on applying data cleaning techniques to covert the original dataset (dirty_data) into a quality data that can be used for decision making.

Data is said to have quality if it fufils the following criteria;

* Accuracy : Data reflects real world objects, events and scenarios and are sourced from verifiable source(s)

* Completeness : Data has the ability to delivers complusory/required values successfully

* Consistency : Data is unifrom across all datasets with no conflicting measurements

* Uniqueness : No duplicate, redundant, or overlapping records exists across the dataset

* Validity: Data is collected in accepted formats and they fall within the proper range as defined by the organizatons rules and parameters.

![Data Cleaning](https://github.com/leks39/Data-Cleaning/assets/113634690/5cb6e719-7c4b-4ab8-9d50-e66ec2e1bbd9)
