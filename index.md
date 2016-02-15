---
title       : Energy Efficiency Calculator
subtitle    : Choose your best borrowing capital option
author      : Kiril Raytchev
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Procedure

1. Input parameters
2. Review results
3. Analyze 
4. Take a decision

--- .class #id 

## Input parameters


```r
projCosts <- 250000
annualSavings <- 75000
equpmentLife <- 10
leaseTerm <- 4
intRate <- 5
```

---

## Review results




```r
    CashFlow
```

```
##    year wasted  payment     saved
## 1     0  75000     0.00     0.000
## 2     1      0 69087.88  5912.119
## 3     2      0 69087.88  5912.119
## 4     3      0 69087.88  5912.119
## 5     4      0 69087.88  5912.119
## 6     5      0     0.00 75000.000
## 7     6      0     0.00 75000.000
## 8     7      0     0.00 75000.000
## 9     8      0     0.00 75000.000
## 10    9      0     0.00 75000.000
## 11   10      0     0.00 75000.000
```

---

## Analyze content and take a decision

Energy Efficiency project delivers annual savings that are able to pay the cost of borrowed capital.
