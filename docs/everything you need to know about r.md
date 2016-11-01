# Everything you need to know about R

In this post I maintain all useful references for someone want to write nice R code.

## Google’s R Style Guide at google

R is a high-level programming language used primarily for statistical computing and graphics. The goal of the R Programming Style Guide is to make our R code easier to read, share, and verify. The rules below were designed in collaboration with the entire R user community at Google.

## Installing R packages at r-bloggers

https://www.r-bloggers.com/installing-r-packages/

This is a short post giving steps on how to actually install R packages.

## Managing your projects in a reproducible fashion at nicercode

https://nicercode.github.io/blog/2013-04-05-projects/

Managing your projects in a reproducible fashion doesn’t just make your science reproducible, it makes your life easier.

## Creating R Packages

http://cran.r-project.org/doc/contrib/Leisch-CreatingPackages.pdf


This tutorial gives a practical introduction to creating R packages. We discuss how object oriented programming and S formulas can be used to give R code the usual look and feel, how to start a package from a collection of R functions, and how to test the code once the package has been created. As running example we use functions for standard linear regression analysis which are developed from scratch

## How to write trycatch in R

http://stackoverflow.com/questions/12193779/how-to-write-trycatch-in-r

Welcome to the R world 😉

## Debugging with RStudio

https://support.rstudio.com/hc/en-us/articles/200713843-Debugging-with-RStudio

RStudio includes a visual debugger that can help you understand code and find bugs.

## Optimising code

http://adv-r.had.co.nz/Profiling.html#performance-profiling

Optimising code to make it run faster is an iterative process:

Find the biggest bottleneck (the slowest part of your code).
Try to eliminate it (you may not succeed but that’s ok).
Repeat until your code is “fast enough.”
This sounds easy, but it’s not.