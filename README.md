# R-Final-Project-Gaming-vs.-Academic-Performance
My final for R is about gaming vs. academic performance.
The data I am using for this project is https://www.kaggle.com/datasets/aiexplorer77/gaming-vs-academic-performance from Kaggle


The first data manipulation is to see the mean and median of the grades, gaming hours, attendance, and hours slept. This manipulation shows that, for the most part, in this data, all the averages and medians are almost the same for each category. 


The next thing I wanted to see what percentage of the types of gamers in the data.

The R file shows that the data is fairly even across the board for what genres people play, but there are a few more people that first person shooters (FPS), role-playing games (RPG), and casual games.


Now I wanted to know what the percentage of people playing games for more than 2 hours is. It seems that in this data, about 76% of people in this data have a play time of over 2 hours.


The next thing I needed to do was make some categories to make it easier to see at a glance if someone has a low, moderate, or high play time. After getting the count for each category, I made it look like in this data, most of the people have a play time that is over 3 hours, next are people that have a moderate play time of 1-3 hours, and the fewest people have a play time that is less than 1 hour.


Finally, the last data manipulation I did was creating a column that shows the students' letter grade. The count of the students' grades is showing that, for the most part, our data is even in all letter grades, except for students with an F. It looks like, in this data, there are 3 times more students with F's than any other letter grade.


The next thing that I needed to do with my data was run a Z-test. For that test, I would like to know if Men and Women have the same play time on average.

My hypotheses are as follows.

Null Hypothesis: Men and women have no difference in their average play time.

Alternative Hypothesis: There is a difference between men's and women's average play time.


First, I needed to set up for my Z-Test, knowing what the standard deviation for hours playing games is in my data set. It would seem that we have a standard deviation of about 2.


After that, I need to set up new data frames, one that only has the columns of people's gender and the gaming hours. Then I need to split that data set into two different data frames, one for men and one for women.


Next, I need to set my alpha of 0.05, sigma, means, and the length for the Z-Test
Finally, with all the setup done, I can run my Z-Test. We got a Z-score of -0.20, but the Z-score does not tell us much, so we need to get the P-Value from the Z-score.


So after we got the P-value from the Z-score, we got a P-value of .83, meaning we failed to reject the null hypothesis. This means that there is little to no difference in the amount of time men and women play games.


Next, I wanted to create some graphs to visualise my data.


For my first graph, I wanted to know how many students are in each letter grade and compare their stress levels vs how many hours they play games. 

So, looking at the graphs, it's showing that most of the students have a medium stress level no matter how much they play games, but the most surprising graph is the low stress levels and the high play time. The majority of the students in this graph have an F grade.


The next graph I wanted to see was a comparison of the students' addiction score and the number of hours they play. I also colored the scatter plot with the students' letter grades to see if there was a trend for their grades, and finally, I wanted to compare all the data to the gaming genres.

Looking at the graph, it shows that when comparing the genres of games, there doesn't seem to be too many differences, and with the grades, the dose seem that the more hours played and a higher addiction score do seem to lower the grade, and the lower addiction score and lower hours played do seem to help their grade.


Another graph I wanted to see was how the average sleep time affected the students' grades and what their play time was.

From looking at the data, it does seem that the more sleep on average the students got, the better their grades are. Another interesting thing is that the highest bar is the one with a high sleep average, and an A is also colored for High play time, meaning that when the students get enough sleep, they get a good grade and also play games for hours.


The final thing I wanted to do was make a correlation heat map of all the numeric values in my data.

I needed to make another data frame of just the numeric data from the original data frame, and then make a correlation

Finally, I created the heat map.

Looking at the map, it seems that not many things correlate, but when they do correlate, almost all of the correlations are high to moderate correlation ether positive or negative. Some of the standout ones tho are the negative strong correlation between reaction time and gaming hours, another one suppring one is that there is a moderate correlation between grades and reaction time.
