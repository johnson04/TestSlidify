---
title       : My First Slidify Presentation
subtitle    : -- Developing Data Product

framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
url:
    lib: ./libraries
    assets: ./assets
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## On this slide we plot some Gaussian random numbers


```r
x <- rnorm(100,0,1)
plot(x)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 

--- 

## On this slide we plot some binomial random numbers


```r
x <- rbinom(100,3,0.6)
plot(x)
```

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2.png) 

---

## On this slide we plot some Poisson random numbers


```r
x <- rpois(100,4)
plot(x)
```

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3.png) 

---

## On this slide we finish this presentation


<font size=12>Thank you very much for your time and patience!</font>

