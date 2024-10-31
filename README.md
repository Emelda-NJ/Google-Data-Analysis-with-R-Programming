# Google-Data-Analysis-with-R-Programming
R-Scripts

# Basic concepts of R
functions, comments, variables, data types, vectors, and pipes.

* Functions are a body of reusable code used to perform specific tasks in R. Functions begin with function names like print or paste, and are usually followed by one or more arguments in parentheses. 
  An argument is information that a function in R needs in order to run.

  Example, the print function

  print("Coding in R.")

* A variable is a representation of a value in R that can be stored for use later during programming. Variables can also be called objects.
For example, if you want to filter a dataset, just assign a variable to the function you used to filter the data.

  A variable name should start with a letter and can also contain numbers and underscores. So the variable 5penguin wouldn't work well because it starts with a number. 
  Also just like functions, variable names are case-sensitive. Using all lower case letters is good practice whenever possible.

* Comments are helpful when you want to describe or explain what's going on in your code.

  Comments should be used to make an R script more readable. A comment shouldn't be treated as code, so we'll put a # in front of it. Then we'll add our comment. Here's an example of a variable.

  #Here's an example of a variable.

* The assignment operator example: <-. It assigns the value to the variable. It looks like an arrow, which makes sense, since it's pointing from the value to the variable.

  first_variable <- "This is my variable."

  second_variable <- 12.5

* A vector is a group of data elements of the same type stored in a sequence in R. You can make a vector using the combined function. In R this function is just the letter c followed by the values you want in your vector inside parentheses. Example:

  vec_1 <- c(13, 48.5, 71, 101.5, 2)

  This time when we type our variable and press enter, it returns our vector. We can use this vector anywhere in our analysis with only its variable name vec_1. 
The values in the vector will automatically be applied to our analysis.

* A pipe is a tool in R for expressing a sequence of multiple operations.
  A pipe is represented by a % sign, followed by a > sign, and another % sign. It's used to apply the output of one function into another function. Pipes can make your code easier to read and understand.
