---
title: Project 1 The Random Quote Machine
summary: Selecting a random quote from an array, and displaying it on the screena
date: 2019-08-25
tags:
  - javaScript
  - tech
  - developer
---

The goal of this project to display a Random Quote selected from an array.

In this post with you will learn about the Math.floor, Math.random, and 

First we need to great the array of quotes! I picked 5 Disney Quotes. 

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/fmc8rx4ycfs1kewtjxxh.PNG)


Now, we create a function to randomly select one of the quotes.

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/yku68pdrl9dofdouu22j.PNG)

## getRandomQuote()
We have 3 variables number, randomQuote, and source. 

The number variable uses Math.floor and Math.random. 

Math.random takes a random number better 0 and 1. Math.floor takes that number and rounds it down to the whole number returned.

randomQuote takes the number that was stored in the number variable, and stores the quote that is in that associated with number in the quote array.

source is used to get the information stored in the in the quote.source location.


![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/z6ch26ipvhuijtks4m7d.PNG)

## printQuote()
This function is what prints out the quote we got from getRandomQuote, and displays it on the screen. 


 





