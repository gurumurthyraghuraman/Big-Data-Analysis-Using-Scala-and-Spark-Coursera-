Big-Data-Analysis-Using-Scala-and-Spark-Coursera-

Solutions to Programming Assignments of the Course Big Data Analaysis Using Scala and Spark(Coursera)

1. Wikipedia(Assignment 1) Description:
In this assignment, we'll use our full-text data from Wikipedia to produce a rudimentary metric of how popular a programming language is, in an effort to see if our Wikipedia-based rankings bear any relation to the popular Red Monk rankings.

Steps to Run:
Go to src/main/resources/wikipedia and unzip the file "wikipedia.dat.zip".
Now run the scala Program.

2. Stackoverflow(Assignment 2) Description:
The overall goal of this assignment is to implement a distributed k-means algorithm which clusters posts on the popular question-answer platform StackOverflow according to their score. Moreover, this clustering should be executed in parallel for different programming languages, and the results should be compared.

Steps to Run:
Go to src/main/resources/stackoverflow and unzip the file "stackoverflow.csv.zip".
Now run the scala Program.

3. Timeusage(Assignment 3) Description:
Our goal is to identify three groups of activities:
    primary needs (sleeping and eating),
    work,
    other (leisure).

And then to observe how do people allocate their time between these three kinds of activities, and if we can see differences between men and women, employed and unemployed people, and young (less than 22 years old), active (between 22 and 55 years old) and elder people.

At the end of the assignment we will be able to answer the following questions based on the dataset:
    how much time do we spend on primary needs compared to other activities?
    do women and men spend the same amount of time in working?
    does the time spent on primary needs change when people get older?
    how much time do employed people spend on leisure compared to unemployed people?

To achieve this, we will first read the dataset with Spark, transform it into an intermediate dataset which will be easier to work with for our use case, and finally compute information that will answer the above questions.

Steps to Run:
Go to src/main/resources/timeusage and unzip the file "atussum.csv.zip".
Now run the scala Program.
