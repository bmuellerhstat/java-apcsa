# Movie Ratings

For this assignment, you will write a program that will aggregate a set of movie ratings for a new film. Sites such as IMDB (Links to an external site.) and RottenTomatoes (Links to an external site.) take lots of data about how much people enjoyed movies and aggregate this to produce a single score indicating how good a movie is. With new movies being released every day it makes sense to use a computer program to calculate these scores.

Your program will compute an overall movie rating as a weighted average of ratings from a popular movie review website, ratings given by a private focus group, and movie critic ratings. You'll see a starter code template for this assignment in your code editor window, and you should write your code in the place indicated.

For input, the program should accept a film title (as a string) and a running time in minutes (as an int). It should then take 3 different integer ratings from a movie review website, then 2 different decimal ratings from a focus group, and finally 1 average rating from professional movie critics which may also be a decimal.

The program should then output the movie name and running time in hours and minutes. This should be followed by the average website rating, the average focus group rating, the average movie critic rating (as doubles), and an overall movie rating (as an int).

The overall movie rating should be computed as a weighted average. Count the average website rating as 20% of the overall rating, the average focus group rating as 30% of the overall rating, and the average movie critic rating as 50% of the overall rating. The overall rating should be rounded to the nearest integer (NOT just truncated to the integer below).

When you write the code to produce your program's final output, take extra care to ensure all the labels used are exactly as shown in the sample run, including the colon after each label. The program which grades your solution will look for the values after these labels, so if they don't match exactly your solution may not be graded correctly.

Sample Run:
```java
e computed as a weighted average. Count the average website rating as 20% of the overall rating, the average focus group rating as 30% of the overall rating, and the average movie critic rating as 50% of the overall rating. The overall rating should be rounded to the nearest integer (NOT just truncated to the integer below).

When you write the code to produce your program's final output, take extra care to ensure all the labels used are exactly as shown in the sample run, including the colon after each label. The program which grades your solution will look for the values after these labels, so if they don't match exactly your solution may not be graded correctly.

Sample Run:

Please enter the movie name
AP CSA: The Movie!

Please enter the running time in minutes.
135

Please enter ratings from the movie review website.
75
99
10

Please enter ratings from the focus group.
84.5
92.3

Please enter the average movie critic rating.
87.58

Title: AP CSA: The Movie!
Running time: 2h15
Average website rating: 61.333333333333336
Average focus group rating: 88.4
Average movie critic rating: 87.58
Overall movie rating: 83
```


Consider three **milestones** (tasks, checkpoints, etc) to reach in the process of developing this program.
