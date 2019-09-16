# Movie Ratings

For this assignment, write a program that will aggregate a set of movie ratings for a new film, entitled AP CSA: The Movie! Your program will compute an overall movie rating as a weighted average of ratings from a popular movie review website, ratings given by a private focus group, and movie critic ratings.

For input, the program should accept 3 ratings from a movie review website (as ints), 2 ratings from a focus group (as doubles), and 1 average rating from professional movie critics (as a double).

The program should then output the average website rating, the average focus group rating, the average movie critic rating, and the overall movie rating (as doubles).

The overall movie rating should be computed as a weighted average. Count the average website rating as 20% of the overall rating, the average focus group rating as 30% of the overall rating, and the average movie critic rating as 50% of the overall rating.

If you notice that your overall rating is off by a very small amount, this may be due to roundoff error, which we will discuss in an upcoming lesson. Visit the student forum on Piazza for some tips on avoiding roundoff error on this assignment.

Sample Run:
```java
Please enter ratings from the movie review website.
75
99
10

Please enter ratings from the focus group.
84.5
92.3

Please enter the average movie critic rating.
87.42

Average website rating: 61.333333333333336
Average focus group rating: 88.4
Average movie critic rating: 87.42
Overall movie rating: 82.49666666666667
```

Consider three **milestones** to reach in the process of developing this program.
