---
title       : Simple Interest Calcuator Project
subtitle    : Slidify
author      : Shanti Shakya
job         : Engineer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
  user: shantishakya
  repo: SimpleInterestShinyApp
---

## SLide 1

Introduction

As part of Coursera's Developing Data Products course in the Data Science Specialization I have deleoped a simple interest calculator.

Course project requirements

The application must include the following:

Some form of input (widget: textbox, radio button, checkbox, ...)
Some operation on the ui input in sever.R
Some reactive output displayed as a result of server calculations
You must also include enough documentation so that a novice user could use your application.
The documentation should be at the Shiny website itself. Do not post to an external link.


--- .class #id 

## Slide 2

Part of projec:

numericInput - A field to get value for the principal amount  
sliderInput - A slider bar to get value for interest and time periods 
selectInput - A box with choices to select from, in this case - the type of time period: years, quarters or months
actionButton - An Button to calculate and display result

---  

## Slide 3

Application - 

We get input for principal amount,interest,time periods

The simple interest calculation equation is:
A = P + I = P(1 + rt) ; R = r * 100
where:
A = Total amount (Principal + Interest), P = Principal amount, I = Interest amount, r = Rate of interest per year, in decimal; r=R/100, t = Time period invested in years/quarters/months

Afther above calculation the result is displayed


---  

## Slide 4

Code

files in repo:

server.R
ui.R

To execute the application and see the code in action, use:
runApp(displayMode = 'showcase')

---  

## Slide 5

Try out the application on the RStudio shinyapps.io website:
https://shantishakya.shinyapps.io/SimpleInterestProj/


Thank you,
Shanti Shakya
