#stocks-analysis

Module 2

#Refractoring Code for Stock Analysis 

##Overview of Project 

###Purpose

The purpose of this analysis is to analyze several stocks while maintaining a low run time and not utilizing too much memory to run the analysis. This is done by refactoring, which is changing the original code in a way where it can loop through multiple stock tickers but provide the same output as running through a single stock ticker. The goals are to make the code more efficient, easier to read, and run quickly.  

##Stock Analysis and Execution times 

###Stock Analysis Between 2017 and 2018

There are 11 of the same stock tickers ran during the years 2017 and 2018. Overall, 2017 was a better year because most of the stocks had a positive return including four tickers with a return over 100 percent. Another factor that stands out in 2017 is the volume. The daily volume for a majority of the stocks were higher than the daily volume in 2018. In contrast to 2017, the daily volume for the majority of the stocks in 2018 were significantly lower. Additionally, the majority of the tickers had a negative return in 2018.   

###Execution times 

Refactoring the code had a positive impact on the execution times. It is best to keep the execution times low when considering the number of tickers the code must loop through. In the original code, the execution times for 2017 and 2018 were both over one minute. In the refactored code, the execution times for both years were under one minute.  

####The original execution times

![image](https://user-images.githubusercontent.com/99801608/159138439-fdedd641-0f56-413a-908e-c0dc7550380a.png)

![image](https://user-images.githubusercontent.com/99801608/159138448-a9feb204-4d6e-4262-9975-7c40f4f1eeb6.png)

####The new Execution times

![image](https://user-images.githubusercontent.com/99801608/159138453-f094d18b-af8b-4663-aee6-f15fdf1a0ab6.png)
   
![image](https://user-images.githubusercontent.com/99801608/159138457-b30a2459-e60b-41fa-a050-3d9bb86e9431.png)
      
##Advantage and Disadvantage of Refactoring a code 

The obvious disadvantage of refactoring a code is the process can be time consuming. In addition to the amount of time, the code might not run on the first try which leads to additional time rewriting code. However, once the code is written and it works, it does run smoothly and quicker. Refactored codes ae also easier to read and understand.  

The disadvantages of the original script are the run time and the readability of the actual code. Making a code easy to read  allows for more effective revisions especially when programmers are working in a group.  

