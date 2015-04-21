---
title       : DataProducts Project
subtitle    : BMI Calculator
author      : DavidAh
job         : self
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction to BMI
The Body Mass Index (BMI) is a number that provides calculated from a person's height and weight that provides a fairly reliable indicator if the person is overweight or not:  
   * BMI does not measure body fat directly.
   * Research has shown that BMI correlates to direct measures of body fat.
   * BMI can be considered an alternative for direct measures of body fat. 

BMI is an inexpensive and easy-to-perform method of screening for weight categories that may lead to health problems.

---

## BMI Calculation
The BMI Table below provides an explanation of the BMI number and the corresponding weight status.
### BMI Table

```
##  BMI           Weight Status
##  "<18.5"       "Underweight"
##  "18.5 - 24.9" "Normal"     
##  "25.0 - 29.9" "Overweight" 
##  "> 30.0"      "Obese"
```
### BMI forumala

   BMI = weight(lbs)  /  ( height(inches)**2 ) * 703

Once you've calculated your BMI, you compare your BMI against the rows of the table to determine your weight status.

---

## BMI Application
The BMI Applicaiton is a simple web app that allows a user to quickly calculate their BMI using any web enabled device. 

```r
weight = 180
height_in_inches = 6 * 12
BMI = ( weight / (height_in_inches ^2) ) * 703
print(BMI)
```

```
## [1] 24.40972
```

---

## References
http://www.cdc.gov/healthyweight/assessing/bmi/index.html



