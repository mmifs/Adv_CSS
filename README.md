# 02 Advanced CSS: Portfolio

Welcome to this week's Challenge! This is an even-numbered week, so you won't be given any starter code. Instead, you'll create a web application from scratch! This week, you'll build a portfolio page, which you can add to as the course progresses. 

A portfolio of work can showcase your skills and talents to employers looking to fill a part-time or full-time position. An effective portfolio highlights your strongest work as well as the thought processes behind it. Students who have portfolios with deployed web applications (meaning they are live on the web) are typically very successful in their career search after the boot camp. This last point can’t be stressed enough: having several deployed projects is a minimum requirement to receive an initial interview at many companies. 

With these points in mind, in this Challenge you’ll set yourself up for future success by applying the core skills you've recently learned: flexbox, media queries, and CSS variables. You'll get to practice your new skills while creating something that you'll use during your job search. It’s a win-win that you'll likely be grateful for in the future!

**Note**: If you don't have enough web applications to showcase at this point, use placeholder images and names. You can change them to real applications as you create them later in the course.

Let’s look at what a user story written from the perspective of a hiring manager might look like. As you might remember, we follow the AS AN / I WANT / SO THAT format.

## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```

## Acceptance Criteria

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

The following animation shows the web application's appearance and functionality:

![portfolio demo](./Assets/02-advanced-css-homework-demo.gif)

## Review

You are required to submit BOTH of the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository that contains your code. Give the repository a unique name and include a README file that describes the project.

- - -
© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.


________________________________________________

Completion Notes per requirement

GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them *my first name appears in the top left corner of the web page, i did not include my full name as personal information is not required for the purposes of the challenge as per Hilmi "feel free to use dump data"*
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section *the nav bar functions as intended, although the page is not big enough to accurately scroll to any section but the bio (first link)*
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications *the "My Work" link on the nav bar performs this function*
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others *the RUN BUDDY application image represents my first and therefore larger application image
WHEN I click on the images of the applications
THEN I am taken to that deployed application *this function works as intended*
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport *the robot gladiators application and password generator will adjust to a column rather than a row on screens smaller than 1400px*

________________________________________________

Some limitations/additions/changes to be made in the future follow:

* The code is not optimized and should be refactored
* Most of the links on the page only lead to a "coming soon" webpage
* The linked image for run buddy application appears to cover most of the div section, whereas this is not intended and should only cover the image itself and the title above the image