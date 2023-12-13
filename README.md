# Recommendations_with_IBM
Project 3 for Data Scientist Nanodegree
# Table of Contents

* [Installation](#Installation)
* [Project Motivation](#Project-Motivation)
* [File Descriptions and Analyses](#File-Descriptions-and-Analyses)
* [Results](#Results)
* [Licensing, Authors, and Acknowledgements](#Licensing,-Authors,-and-Acknowledgements)


## Installation <a name="Installation"></a>
The code should run with no issues using Python versions 3.8.8 using Jupyter Notebook server version 6.3.0.  Numpy, Pandas, matplotlib.pyplot, math, seaborn, wordcount,  

Datapane must then be installed as below

```python
pip install -U datapane
```

## Project Motivation <a name="Project-Motivation"></a>
For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like.   

**_Business Problem Understanding_**
 
 
Your project will be divided into the following tasks

**I. Exploratory Data Analysis**

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

**II. Rank Based Recommendations**

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

**III. User-User Based Collaborative Filtering**

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

**IV. Content Based Recommendations (EXTRA - NOT REQUIRED)**

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

**V. Matrix Factorization**

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.


## File Descriptions and Analyses <a name="File-Descriptions-and-Analyses"></a>
**_Data Understanding_**


**_Data Preparation_**  



## Results <a name="Results"></a>



```python
# )
```  


[A Medium blog](https://medium.com/@nirvannsramp/intrepid-explosive-voyages-77f23e47e24e?source=friends_link&sk=b97c94187c9f435b0b955aa12acc408d) was created using the results. 

## Licensing, Authors, and Acknowledgements<a name="Licensing,-Authors,-and-Acknowledgements"></a>
The data was available from the (Towards data science)[https://towardsdatascience.com/5-pandas-group-by-tricks-you-should-know-in-python-f53246c92c94]. [https://www.geeksforgeeks.org/get-n-largest-values-from-a-particular-column-in-pandas-dataframe/], https://note.nkmk.me/en/python-pandas-duplicated-drop-duplicates/

