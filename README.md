
# Zomato Data Analysis

## Author

- Vishwjeet Singh chauhan [@vishwjeet14](https://github.com/vishwjeet14)

## Introduction

* This README describes work done on the Zomato data set for the Fundamentals of Data Analysis module assessment due 21 April 2022. Resources used include Python and associated packages Jupyter, matplotlib, Seaborn, Pandas, Numpy . These packages all come as part of the Anaconda distribution of Python.

* The analysis takes the form of a single Jupyter notebook of filename given above. To view this file, download it from this repository and start Jupyter notebook in the folder containing the file. Use the command Jupyter notebook on the command line.

* Alternatively, view a static version of the notebook (by providing its GitHub url) using Jupyter Nbviewer.

* The Zomato data set is downloaded from kaggle. It contain to Files one is CSV and other is Excel. Both the file are related to each other and connected with attribute called Country code.

* I have tried to structure the Jupyter notebook and this README so that they have corresponding sections. However, I do not wish to merely repeat here what has been stated in the notebook. I will endeavour to have this README summarize the work of the notebook and, hopefully, complement the analyses done there.

## Programming Language Use in Data analysis

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/python.png)

## Python library use in python

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/pandas.png)
![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/matplotlib.png)
![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/download.png)
![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/seaborn.png)


## Description of the data set

The data in the Zomato data set contains 9551 rows of data and 22 attributes. Information within includes 'Restaurant ID', 'Restaurant Name', 'Country Code', 'City', 'Address','Locality', 'Locality Verbose', 'Longitude', 'Latitude', 'Cuisines','Average Cost for two', 'Currency', 'Has Table booking','Has Online delivery', 'Is delivering now', 'Switch to order menu','Price range', 'Aggregate rating', 'Rating color', 'Rating text','Votes', 'Country' with different data types. It Contains 15 countries with 141 cities. It has 14 Categorical atrributes and 8 numerical attribute.

## Atrributes data type

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/info.png)

## Descriptive statistics 

Pandas describe() can provide a quick summary of the data set as outlined in the notebook

### 1. Numerical Data

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/describe.png)

### 2. Categorical Data

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/Categorical.png)

## Country use currency

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/contrycurrency.png)

## Missing Values in data set

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/missing1.png)

## Initial Findings

* Number of columns 22
* Number of rows 9551
* Number of categorical columns is 14
* Number of Numerical columns is 8
* Missing values is Cuisines column total value 9

## Corelation ship between the attributes

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/corr1.png)
![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/corr2.png)

## Top Three country use zomato

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/top3contryusezomato.png)

## Country Have zero Ratings

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/contry%20zero%20rating.png)

## Countries have online deliveries option

Only two country have online delivery service.

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/contryhave%20onlinesrervice.png)

## Top 5 cities distribution

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/top%20city%20distribution.png)

## Top 10 cuisines

![alt text](https://github.com/vishwjeet14/Zomato-Data-Analysis/blob/main/Picture/top10cusin.png)

## Conclusion

1. Missing Values are present in Cuisines column and no. of values is 9.

2. UK, US, INDIA is top three country use zomato.

3. Maximum number of 0 ratings are from Indian customers

4. Online Deliveries are available in India and UAE

5. Top 5 City use zomato in india are Delhi, Noida, Ghaziyabad, Faridabad, Gurgaon.

6. Top 10 Cuisines on zomato are North Indian, Street Food, Bakery Desert, North Indian Mugalai Chinese, Bakery, Cafe, North Indian Mugalai, Fast Food, Chinese, North Indian Chinese

## Feedback

If you have any feedback, please reach out to us at vishc70@gmail.com


