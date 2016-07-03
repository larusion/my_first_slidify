---
title       : Olympic Track Times
subtitle    : R Shiny App for Devloping Data Products
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github      :
        user: larusion
        repo: my_first_slidify
knit        : slidify::knit2slides
---

## Olympic Track Times from 1896 to 1964

This app displays the olympic track times in tenths of a second versus over the years that 
they were recorded, i.e., from 1896 to 1964. 



This dataset comes from Package 'cluster.datasets' of CRAN.

References:

Hartigan, J. A. (1975). Clustering Algorithms, John Wiley, New York.

--- .class #id 

## What a user needs to do

The user needs to choose the meters that the athletes ran. 

The options are:

1. 100 m
2. 200 m
3. 400 m
4. 800 m
5. 1500 m
6. 5000 m
7. 10000 m

--- .class #id 



## The winning times in the 100 m

Let's say the user has chosen, the figure below will appear...

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

--- .class #id 


## CURIOUS?




Go check out the app at [https://larusion.shinyapps.io/app-2/](https://larusion.shinyapps.io/app-2/)


