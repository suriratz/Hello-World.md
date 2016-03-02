x <- 1:10

> x
 [1]  1  2  3  4  5  6  7  8  9 10

# modulo division
> x %% 2 == 0
 [1] FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE


is.even <- function(x) x %% 2 == 0

> is.even(x)
 [1] FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE


> is.odd <- function(x) x %% 2 != 0

> is.odd(x)
 [1]  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE  TRUE FALSE
