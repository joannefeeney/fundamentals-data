# Fundamentals of Data Analytics

This is my repository for my ATU Fundamentals of Data Analytics project & tasks.

I have created two jupyter notebooks, named tasks.ipynb & project.ipynb which contain all my code and findings from my research for this module.

## Project

![iris_flowers](https://user-images.githubusercontent.com/123767624/236692889-280b9db3-e557-4c14-bd65-8fb64eb8f002.png)

### Introduction

For this project I will create a notebook investigating the variables and data points within the well-known iris flower data set associated with Ronald A Fisher.

I will discuss the classification of each variable within the data set according to common variable types and scales of measurement in mathematics, statistics and Python. I will also select, demonstrate and explain what I believe to be the most appropriate summary statistics to describe each variable and explain the most appropriate plot(s) for each variable

The Iris dataset includes three flower (iris) species with 50 samples each as well as some properties about each flower. 

The columns in this dataset are:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Class

### Main Body

First I import all the packages that I use for almost all of my college projects including pandas, seaborn etc.

I read in the dataset, add column names and look at the first few lines using .head().

I use .info(), a pie plot, .describe() & .isnull().sum() to find out more information about the dataset. We can see there are 150 entries, there are no non-null entries and the different data types which are set as either floats or objects.

By using all of the above quick python codes, we can already make some assumptions about the iris dataset. We can see that it is a clean, evenly distributed dataset i.e. there are no missing values and each variable has a count of 50. We only have two types of variable, floats and objects. 

There is not a great difference in length (cm) between the iris widths when comparing minimum to maximum but a fairly sizeable difference when comparing the min. & max. iris lengths.

I then group the data by class (or species) and create some plots. I also use python code to back up the .describe() function calculations on mean, min and max values.

### Conclusion

In this notebook, I investigated the Iris dataset. My investigation aimed to work out the patterns and characteristics of three species/class of iris flowers: setosa, versicolor and virginica.

I used various data analysis techniques to get some insight into the key attributes of the iris flowers. From scatter plots and pair plots to statistical measures such as mean, max etc., I compared these species. I discovered the distinguishing features of the iris species, such as sepal length, sepal width, petal length, and petal width. The outputs provide us with a lot of information on the unique identitifiers of each species.

In summary, the iris dataset has allowed me to use some valuable skills in data analytics and get much more familiar with a subject I hope to use much of in the future.

***

## Tasks

Task 1 - The Collatz Conjecture

Task 2 - The Penguins Data Set

Task 3 - The Penguins Data Set - Suggesting appropriate probability distributions

Task 4 - Flipping two coins, each with a probability p of giving heads

Task 5 - Individual plots for each of the iris dataset variables

***
## The End
