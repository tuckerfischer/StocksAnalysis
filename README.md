#Project Overview

In this project we were given a list of green stocks and their performance in 2017 and 2018. We then looped through each ticker to determine the Total Daily Volume and return percentage for that stock. By doing this we were able to advise whether or not a certain stock was a good pick for that year. 

	##Refactored Vs. Original Code
		The first code we ran we had a nested for loop that would loop through each ticker then through each row. With the refactored code we first set the tickerVolumes for each ticker to 0 and then we looped through each row. Then we looped through adding the data to excell and finally formatted the code. 	##Big O
	Since Big O of a nested for loop is O(n^2) while Big O for a for loop is linear time or O(n) therefore we would expect the refactored code to be faster the the original code. 

#Results

##Run Times

All Stocks Analysis 2017.PNG
The run time for the original code in through the 2017 data was 0.574 seconds

All Stocks Analysis 2017 Refactored.PNG
The run time for the refactored code through the 2018 data was 0.009 seconds

All Stocks Analysis 2018.PNG
The run time for the original code O(n^2) was 0.582 seconds.

All Stocks Analysis 2018 Refactored.PNG
The run time for the refactored code O(n) was 0.105

As predicted by knowing the Big O for each macro the refactored code ran quicker than the original code. 

##Stock Performance

In 2017 all but one stock (TERP) had gains. In 2018 the results were a lot more bleak with only two stocks having gains (ENPH and RUN). 

	###ENPH
	In 2017 ENPH had gains of 129.52% with the total daily volume of $221,772,100, and in 2018 percent gains decreased to 81.92% with the total daily volume increasing to $607,473,500.

	###RUN
	In 2017 RUN had gains of 5.55% with the total daily volume of $267,681,300 and in 2018 the percent gains increased to 83.95% with the total daily volume increasing to $502,757,100

#Summary

Refactoring the code had two clear advantages. The first being that it is easy to debug since each piece of the code is in an isolated loop. The second advantage is the decrease in run time which if you were planning on running this for every stock ticker would have a huge impact. The disadvantage of the refactored code is that it takes up more lines of code versus the original code. 
