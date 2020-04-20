---
title: Project 2 Pagination
summary: Pagination Example
date: 2020-03-28
tags:
  - projects
  - javaScript
  - tech degree
  - developer
---

# Goal: Display 10 Students per page from a list of students

#### [Live Link](https://enaughton.github.io/Pagination)

#### [Github](https://github.com/enaughton/Pagination)

Looking at the HTML given to us is a bunch of students that in a an unordered List. Each student has a picture, their name and their email. We are using the list of the 54 students. Breaking down the list, we should have 6 pages. 5 Pages with 10 students and then a 6th page with the 4 remaining students.

- Step 1) Create the function showPage()
  This function takes a page number and displays the students, 10 per page.

  the upperIndex and lowerIndex variables take the page number and multply it by 10. the upperIndex subtracts 1 and the lowerIndex subtracts 10

  we use the upperIndex and lowerIndex in a for loop with the length of the student list.

  depending if the `i` value is greater than the lowerIndex but less than the upperIndex we will display the student.

  <img  src="/_includes/assets/images/project2/showPage.PNG" alt="Show Page Function">

- Step 2) Create page links based on how many students are in the list.
  Here we create two variables (div, and ul). the variables create the two HTML elements. Once the variables are created, we move onto append the div element to the body, or add the div to the page. Now that the div is added, we give it the class name `pagination`
  We can append our `ul` variable to the div variable.
  This will add the page numbers to the page based on how many students are in the list.

  <img src="/_includes/assets/images/project2/CreateHTMLelements.png" alt="Creating Div and ul Elements">

- Step 3) Create the function createPageLinks()
  This function takes the variable pageNum which we created earlier, and displays the correct number of pages based on the number students in the list.
  First we create the HTML `li` and store that in a variable called `li`
