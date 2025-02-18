**Additional Resources:**

-   [R for Data Science Chapter 4: Workflow
    basics](https://r4ds.had.co.nz/workflow-basics.html)
-   [RDocumentation.org](%5Bdocumentation%20website%5D(https://www.rdocumentation.org/))

## Questions

<br>

**1. What arguments can you use for the `mean` function in R?**

Hint: you can access the help file for any function in R by typing a
question mark before its name: ?mean in the console

<br>

**2. Extract the third element of the vector using numerical indexing.**

``` r
random_vector <- c("R","is","great")
```

<br>

**3. Use R code to identify the data type of `some_vector`. What is the
largest number in this vector? How about the mean value?**

Hint: you’ll have to research some new functions in r to do this- try
Google or one of the tutorials linked on the syllabus.

``` r
some_vector <- c(25555,342343,123123123,4234234,53243234,54324234,5421111,12312312,111231,
                     1231231,12312312,12312312,123123,898972,789872,2343,23423423,2343221,23423,
                     14444,44324222,2342341,124231111,22233345,1111233333,1231231,1231231)
```

<br>

\*\*4. For the remainder of this quiz, we’ll look at a dataframe called
`congress` that describes characteristics of U.S. elected officials. We
will use this dataset for many subsequent questions in these bootcamp
quizzes as well. Run the code below to download the dataset from a
Github site.

``` r
load(url('https://dssoc.github.io/datasets/congress.RData'))
```

<br/>

**4. How many rows and columns does the `congress` dataframe have? Use a
function to show its data type. You must use R code to generate these
values.**

<br>

**5. What is the average age of all congress members? What is the data
type of the `birthyear` column?**

<br>

**6. How much older is Sherrod Brown (a member of congress) compared to
the average of members of congress? How about Dianne Feinstein?**

<br>

**7. Who are the oldest members of congress?**

<br>

Thanks to Devin Cornell and Taylor Brown for helping to create these
quizzes!
