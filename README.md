# AIS16642intern
Task1:
1.Variable declaration rule: Studied the rules for variables declaration of variable.
2.Operators: Studied various operators in python like Arithmetic,logical,comparision,numeric,identity ,Menbership and bitwise.
Datatypes:
3.List-Studied how to declare datatype  list and its method like append,remove,insert,pop,sort,count,accesing,copy,reverse and its properties.
4.Tuple:Studied how to declare tuple and its method like index,count,etc.
5.Set:Set declaration and its properties like mutable,ordered etc.
6.Dictionary:declaration of dictionary,methods like copy,index pop and use of for loop accesing.
7.String:declaration of string
8.Number:int,float and complex.
Also difference between list and tuple and difference between dictionary and set.


Task2:
1.if stmt:use of if statement to check a single condition in various examples i.e to check whethere the number is positive,negative,odd,even  within a specific range etc..
2.if else stmt: used to check two conditions in example like number is odd or even,pos or neg etc.
3.if elif else:to test multiple condition at a time if above condition false then next condition is tested.examples like result of student.
4.For loop:used to iterate over sequence of items.
5 While loop: used to repeatedly execute  a block of statement while a condition is true.


Task3:
In task 3 we studied the break ,pass,continue statement also we studies User defined functions like Stattistical(mean,median,mode,etc) and logical(odd,even,grades).
#break-Functionality: When break is encounterd inside loop,the loop stops its execution and control is transferred to the statement immediatelyfollowing the loop.
Use case: It is useful when you want to exist a loop as soon as certain condition is met,avoidin unnecessary iterations.#Continue functionality: When continue is encountered,the current iteration is terminated,and the loop proceed with the next iteration.Use Case: It is useful when you want to skip over some parts of the loop but continue with the nextiterations.For instance ,you might want to skip over even numbers or any specific condition within a loop.#pass functionality:The pass statement does nothing and is used as a placeholder.Use case:It is useful when a statement is synthetically required ,but you do not want any action to be taken.Commonly used during development as a placeholder for future code ,in empty function or class definations,or within conditional statements where you plan to add code later.#Statistical User-Defined Functions-Statistical functions are essentials for data analysis and help summarize and understand the data's property.Mean is used to calculate average of list of numbers.Median is use to find the middle value of a list numbers.mode is used to find the most frequently occuring values in a list numbers.Variance used to measure spread of numbers  in a list from the mean. Standard deviation is used to measure the amount  of variation or dispersion of set of values .Percentile is used to determine the value below which a given percentage of obsevations fall range is used to calculate the difference between the maximum and minimum values in a list . interquartile Range(IQR) is used to measure middle 50% of the data .Covariance is used to measure how two variables change together.Correlation Coefficient  used to measure the strength and direction of the relationship between two variables.#Logical User Defined Functions:#is even purpose: Check if a number is even .#is_odd_Purpose:Check if number is odd#Check if number is prime # Check palindrome purpose etc.


Task4:
 In task 4 we studied all about Numpy library.Starting with a basic introduction and ends up with creating and plotting random data sets,and working with NumPy functions.#NumPy is open sourse project that enables numerical computing with python. numPy will always be 100% open source software and free for all use. We studied 1)creating arrays ,2)array indexing 3)slicing 4)NumPy datatypes 5) copy or view 6)array shape or reshape 7) array iterating,8)join,split,searh,sort and filter.Here 1D array,3D array and multidimensional array are studied.
 NumPy has some extra data types,and refer to data types with one character like i for integers,u for unsigned integers etc.#Then we learn how to generate Random Number.Numpy offers the random module to work with random numbers.#Data disribution is a list of all possible values,and how often each value occurs.Such lists are important when working with statistics and data scince.The random module offer methods that return randomly generated data distributions.Then we see that generation of random numbers from particular distribution and visuallisation of that distribution,like normal distribution,bimomial,poisson,uniform,logistic,multinomial,exponentialchi-square etc To plot the graph of distribution#from NumPy import random# import matplotlib.pyplot as plt # impor seaborn as sns .Then we use ufuncs stands for "Universal Functions" and they are NumPy functions that operate on the ndarray object.We studied ufunctions like simple arithmetic,roundin decimals,logs,summations,products,differences,finding lcm,gcd,trignometric functions,hyperbolic functions and set operations.

Task5:
In task 5 we studied pandas library in python.
#Pandas Series:A Pandas Series is like a column in a table.
It is a one-dimensional array holding data of any type.We can also use a key/value object, like a dictionary, when creating a Series.
#DataFrames
Data sets in Pandas are usually multi-dimensional tables, called DataFrames.
Series is like a column, a DataFrame is the whole table.We also studied how to read csv and xlsx file in python.We create DataFrame using matrix and dictionary.
We also studied DataFrame operations like value counts,apply unique,nunique,describe,head,tail and info.
We studied how to select perticular row ,column in python,We also studied conditional selection, addding ,deleting and updating a perticular column,indexing and remove indexing.How to use operations like addition,substraction,multiplication,division between two columns.
We studied checking of missing values in data,studied missing values drop by row and by columns also studied filling of missing values by using mean and median.

 Task6
 In task 6 we studied that matplotlib and seaborn library.
 Matplotlib is a graph plotting library in python that serves as visualization utility.
 #pyplot
 Pyplot
Most of the Matplotlib utilities lies under the pyplot submodule, and are usually imported under the plt alias:
import matplotlib.pyplot as plt
#ploting x and y plots
The plot() function is used to draw points (markers) in a diagram.
In matplotlib we studied matplotlib plotting with markers,lines,labels,grid,subplot,scatter plot,bar,histogram and pie charts.
#seaborn library
#Seaborn is a Python data visualization library based on Matplotlib. It provides a high-level interface for drawing attractive statistical graphics.
#It provides a high-level interface for drawing attractive and informative statistical graphics.
#Seaborn is built on top of Matplotlib and closely integrated with Pandas data structures, making it particularly convenient for working with DataFrame objects.
#Once installed, you can import it in your Python script or Jupyter Notebook:
import seaborn as sns
In seaborn library we see different types of plotting of graphs such as Scatter Plot,Line plot,bar plot,box plot, Violin plot,Heatmap,pairplot,residual plot.

 Task 7
1] Numpy exercise:- solved probles related to array indexing slicing,creating arrays containg zeros ones generating random numbers from normal distribution,using linspace addition of elements in an array calculate mean standard deviation, etc
2]Ecommerce purchase exercise:- studied the dataset and found out the mean purchase price maximum and minimum purchase price,number of people having job title lawyer number of people making the purchase during the AM and how many people made the purchase during PM,5 most common Job Titles,person with the following Credit Card Number: 4926535242672853 ,number of people have American Express as their Credit Card Provider and made a purchase above $95,number of people have a credit card that expires in 2025,top 5 most popular email providers/hosts (e.g. gmail.com, yahoo.com, etc...)
3] Salary exercise:-studied the data read the file and found out average BasePay,the highest amount of OvertimePay in the dataset,job title of JOSEPH DRISCOLL, How much does JOSEPH DRISCOLL make,name of highest paid person,name of lowest paid person,the average (mean) BasePay of all employees per year,number of unique job titles,the top 5 most common jobs,number of  Job Titles were represented by only one person in 2013, people have the word Chief in their job title,there a correlation between length of the Job Title string and Salary.

Case study :-
In this case study we download the titanic data from kaggle and import it to jupyter notebook.Then we find the missing values and filled the missing values by its mean ,and droped the variable like cabin,passenger id etc. Then we do label encoding for the categorical variable.
Then Performd the EDA i.e exploratory data analysis on titanic data such as bar plot,scatter plot,joint plot and pie chart .
From the graph it is seen that the females are survived more than males.The passengers who are in class 1st are most survived as compared to class 2nd and 3rd.
In titanic data survival is the dependent variable and other variables like age,sex,fare,sibps,embarked are independent variables.
Then we split data into train test and fit the algorithms like naive bayes,KNN, decision tree and predict the text data using particular fitted model.
In model evaluation we find accuracy,classification report,confusion matrix,precision and recall for each algorithm .and compare it with each other and we may conclude that 
decision tree is the best model on the basis of prcision , accuracy and recall, Where the values of precision,accuracy and recall for dicision tree are high as compared to knn and naive bayes.

Dashboard:-
In this task we created a dashoard on project data i.e Bike sharing demand data in power bi dashboard.We download the Bike sharing demand data from kaggle. In power bi we get the data from csv file then by using graphs ,sclicers,card and other features we create a dashoard in power bi.

Project:-
Objectives:
1.To identify and evaluate the seasonal fluctuations in the demand for rental bike.
2.Investigate the variations in bike rental demand across different hours per day and days of the month and to identify the peak demand periods.
3.To identify which features in dataset have the most significant impact on target outcome
4.To determine which model is best suited for bike sharing demand dataset.
5.To identify relationships between variables to understand how different factor influence the demand for rental bikes
MODEL BUILDING:-
In the bike sharing demand data prediction project we download the data from kaggle and import it to jupyter notebook then perform EDA on the data.
Then we cleaned data by handling missing values and outliers to build the various models like - linear regression,ridge regression,elastic net, random forest, decision tree,KNN,SVR9Support vector regressor),PCR(principal component regbressor),PLSR(partial least square regressor),Gradient Boosting and find the root mean square error and R square for all the 10 models.
Then we perform grid search cv on 10 models to find the best parameter once we find the Best parameters then again we build the 10 models with that best parameter, and find the RMSE and R square values after the grid search cv .
Also we find feature importance from decision tree model and find the best parameter i.e Hour , tempreture,solar radiation,humidity,seasons and holiday and fit the all 10 models with these 6 variables.and find the RMSE and R square of all models.
Then plot the bar graphs and joint bar plots of rmse values and r square values. Also compare the rmse and R square values of before and after grid search cv .

CONCLUSION:
1. Seasonal Trends: Bike-sharing demand typically varies with the season, with higher usage in warmer months and lower usage in colder months.

2 Weather Impact: Weather conditions such as temperature, humidity significantly influence bike-sharing demand. Favorable weather conditions usually correlate with increased bike usage.

3 Impact of Holidays: Holidays tend to disrupt regular usage patterns, often resulting in lower demand.

4 Based on rmse and r square ,the best performing models are random forest and gradient boosting.

5 By feature importance the variables like hour, tempreture, humidity, solar radiation, Functioning day and seasons are important impact on bike sharing demand.
