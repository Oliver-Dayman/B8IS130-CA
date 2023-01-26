# B8IS130-CA
Introduction to my CA.
My CA will be on an Income Pipeline.
The Purpose of this is to develop a data acquisition and preprocessing Pipeline of my Choice. I have decided to make one based on income in the USA. 
This will be done primarily through python (using PANDA)
I will be tasked to extract the data, transforming appropriate features and the reloading into an appropriate database.

This project will be required to access the chosen database. extracting it and showing it.
It will also be required to process the data as needed.

The plan was to used python however after many failed attempts at connecting python to github, I have decided to instead run this through google colab instead

The dataset was on the income in the USA. it has 15 columns. those being age, workclass, final weight, education, education number, marital status, occupation, relationship, race, gender, capital-gain, capital-loss, hours per week, native country and income.
It had over 48000 entries.

Using what i learnt from the lectures I was able to use colab along with the Pandas data analysis library I downloaded the Data in a csv file in microsoft excel format, imported the pandas library and the data, and viewed the data both in table and graph form. 
After looking over the graphs i had a look at the missing values in each column, and after finding out that there werent too many missing values I ran a dataframe dropna code in a copy of the dataset and then checked again for the missing values.
which i then found out were all dropped.

