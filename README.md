# Communicate-Findings-PISA-Test

#About the Project:

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, I used Python visualization libraries to systematically explore the selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, I produced a short presentation that illustrates interesting properties, trends, and relationships that I discovered in the selected dataset.

(Description taken from Udacity in parts)



#About the Data Set: PISA Data

PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

Details about the Survey Design can be found in the technical report:
http://www.oecd.org/pisa/data/pisa2012technicalreport.html



#Research Questions:

Does performane in Math, Reading and Science literacy depend on gender or location?

Does family background influence student performance?



#Data Visualization:

Data Wrangling (detailed steps can be found in the exploration file)

- I converted all the string columns to numerical columns where needed
- I replaced NaN values with the mean and dropped null values where relevant
- I computed the average student score for Math, Reading and Science from the given data
- I renamed the columns for better demonstration
- I dropped irrelevant columns

>Data Set Overview

In order to demonstrate relevant data distribution in our data set, I decided to use a Histogram for the demonstration of the age and Student Performance distribiution and a bar chart for the distribution of the students' family background in the data set.

In order to show the relationship between the different student performance categories, namely Math, Reading and Science, I have decided to use a multivariate pairplot. This demonstrates the individual relationships in a good manner.

>Influence of Gender and Location on student performance in Math, Reading and Science literacy

In order to show the ranking of average Math, Reading and Science scores in relation to the countries of origin, I decided to use a violin plot. This shows the distribution well in a comparable manner.

>Influence of family background on student performance

In order to show the difference between the average scores in Math, Reading and Science in relation to the students' family background, I decided to use a boxplot, as it shows the distribution in an understanding manner.



#Main Findings

>Location influence of student performance

The differences between the best performance countries seem not to be significant, but one can see that there is still a difference between well and poor performaning countries, which lets us conclude that location does influence student performance. 
This might be caused by different approaches to education in different countries.

>Gender influence on student performance

The difference between the male and female students in terms of their performance seems not to be siginificant, but we can observe that male student performed better in Math and Science and female students better in Reading. This finding is surprising as we have seen a positive correlation between the different categories and would have expected the same result of male and female participant performance ranking in each of the categories.

>Family background influence on student performance

Student from a heterogeneous family background showed better results in the different categories than students from a homogeneous background. This result might be misleading though, as the the group of heterogeneous family background student was way smaller than the group of students from a homogeneous background. 



#Conclusion:

The student performance in the investigated data set seems to be influenced by location, gender and family background. As we discovered a relationship between Math, Reading and Science scores, such as a sample size difference of students with a heterogeneous and a homogeneous family background, the results would need further investigation though.

#Resources:

Udacity Resources
Stack Overflow
https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html
https://docs.python.org/3/tutorial/inputoutput.html#tut-files
