# Week-1-assignment
# Write a loop that calculates 12-factorial
> factorial <- function(x)
+ {
+ n <- 1
+ for(i in 1:x){
+ n <- n*((1:x)[i])
+ print(n)
+ }
+ }
> factorial(12)
[1] 1
[1] 2
[1] 6
[1] 24
[1] 120
[1] 720
[1] 5040
[1] 40320
[1] 362880
[1] 3628800
[1] 39916800
[1] 479001600
> # cite code from StackOverFlow url = http://stackoverflow.com/questions/15014719/factorial-for-loop

# Show how to create a numeric vector that contains the sequence from 20 to 50 by 5.
> seq(from = 20, to = 50 , by = 5)
[1] 20 25 30 35 40 45 50
# cite code from Sequence Generation url = http://127.0.0.1:17069/library/base/html/seq.html

# Show how to take a trio of input numbers a, b, and c and implement the quadratic equation.
a <- 1
b <- 3
c <- 2
x1 <- (-1 * b + ((b^2 - (4 * a * c))^0.5))/ (2 * a)
x2 <- (-1 * b - ((b^2 - (4 * a * c))^0.5))/ (2 * a)
print (c(x1, x2))
[1] -1 -2
> # Quadratic Equation from url = http://mathworld.wolfram.com/QuadraticEquation.html
