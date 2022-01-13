# SuperStore-Sales-Dataset---Exploratory-Data-Analysis


Exploratory Data Analysis is a technique used to understand the different aspects of a dataset. Its main objective is to give a through understand of the data. It is used to summarize the main characteristics of a dataset, to examine data before building model, find patterns, relations and anomalies in data using statistical graphs and other visualization, identify faulty points in data, understand relationship between variables while it's goal is to help businesses understand their customer behaviour/characteristics, business growth, and help make better decisions. 
Exploratory Data Analysis process is not usually a formal or linear process with a set of rules. There is no common method to perfom EDA.

![Gray Simple Cycle Diagram Chart](https://user-images.githubusercontent.com/83877492/149289628-16f24a10-06e0-4066-bb6e-5421eb3c605c.png)

To perform EDA on a dataset, you have to 
1. Understand the variables in the dataset
2. Clean the data from redundancies
3. Analyze relationship between variables
4. Explore and visualize relationships

Charts and plots such as Histograms, Scatterplots, PMFs and CMFs (to visualize distributions), Boxplots, Line graphs are used for plotting in EDA.

The following code in written in Python and mainly uses Pandas and Numpy libraries.

1. Importing the necessary libraries, the dataset and visualizing the first 5 rows

![Screenshot (27)](https://user-images.githubusercontent.com/83877492/149336711-6d7932a9-94d8-40aa-8510-bfcb99ed036f.png)

2. Visualizing the last five rows and explaining the columns available in the dataset

![Screenshot (29)](https://user-images.githubusercontent.com/83877492/149337079-156de198-4ba8-447f-bb10-e45840b18bdb.png)

3. Listing the columns and checking the data info

![Screenshot (30)](https://user-images.githubusercontent.com/83877492/149337497-8553b10a-69da-442b-8f40-f1e72e12f651.png)

4. Listing the number of distinct observation in the dataset and describing the data

![Screenshot (32)](https://user-images.githubusercontent.com/83877492/149337903-fc809e5d-7b30-466c-a455-a1026339f395.png)

5. Dropping the unnecessary columns
 ![Screenshot (33)](https://user-images.githubusercontent.com/83877492/149338198-a1950122-88be-477d-a72b-f4eed649681e.png)
 
 6. Checking for null values and dropping them 
  ![Screenshot (35)](https://user-images.githubusercontent.com/83877492/149338448-2cf09828-f0a4-46ce-8b77-0af764aaedb9.png)
  
  7. Converting the datetime tp pandas datetime and creating the year and month column 

![Screenshot (36)](https://user-images.githubusercontent.com/83877492/149338810-6aa41eaa-6323-4a14-9212-072e9c921a50.png)

8. Visualizing outliers in the sales column using boxplot

![Screenshot (38)](https://user-images.githubusercontent.com/83877492/149339015-45d089fb-1a82-4ea6-8182-8c20fa9b19a4.png)

9. Visualizing the correlation between variables using a heatmap

![Screenshot (40)](https://user-images.githubusercontent.com/83877492/149339341-3e6bfa41-90cd-4c5f-878c-0a596e64dd19.png)

10. Calculated the total revenue and sales per month using the sales column 

![Screenshot (42)](https://user-images.githubusercontent.com/83877492/149339640-c1b97974-c631-4278-92a4-936a6d29d20a.png)

11. Visual representation of sales per month and calculation of sales grouped by year

![Screenshot (44)](https://user-images.githubusercontent.com/83877492/149339978-497b86a4-56c5-4530-8261-98ce828af4d6.png)

12. Visualizing sales grouped by year 

![Screenshot (46)](https://user-images.githubusercontent.com/83877492/149340200-c7577557-1c49-46ac-abbc-ee7895d25cb8.png)

13. Total Sales grouped by segment

![Screenshot (48)](https://user-images.githubusercontent.com/83877492/149340418-61db491d-db71-4b6a-b79f-2f86d87ef089.png)

14. Total Sales grouped by top 10 cities

![Screenshot (50)](https://user-images.githubusercontent.com/83877492/149340580-06045fe0-7eab-43ad-982f-f8f16b5eb7d5.png)

15. Visualizing sales by top 10 cities

![Screenshot (53)](https://user-images.githubusercontent.com/83877492/149341972-97185a57-079d-46c3-b669-578663c220c4.png)

16. Total sales by top 10 states

![Screenshot (55)](https://user-images.githubusercontent.com/83877492/149342169-c3f47476-3edf-42de-a77d-0daedf3a1e4d.png)

17. Visualizing sales by top 10 states

![Screenshot (57)](https://user-images.githubusercontent.com/83877492/149342303-58aa114e-19d5-4eeb-aee4-f6054b4bc732.png)

18. Total sales grouped by region

![Screenshot (59)](https://user-images.githubusercontent.com/83877492/149342513-5c0a9869-24be-4388-b15d-b4d3080aaa77.png)

19. Total sales grouped by categories 

![Screenshot (61)](https://user-images.githubusercontent.com/83877492/149342734-f5b5e365-c64e-4f68-89c2-c44d1ae3b30d.png)
