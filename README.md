# Project Concept
This project is a group project from my mobile app development course at Western Washington University. The project is made completely from scratch, our team was composed of three people. The goal 
was to create a full-stack mobile app project for android, while using Android Jetpack Compose. The project is a complete calorie tracker for users, users can add items to designated, view all items 
added to a meal, delete items. The user can exit the app, and upon reentry all changes will be saved. Calories are reset at the end of each day. Users can add items via custom entry and barcode entry. Many 
more features are implemented, the most notable being users can view graphs for metrics on how much weight has been gained or loss over a span of days, months, years.

# My Part (files)
I worked mostly on item entry. This means implementing the display page for items added, working on the database to store items for leaving and entering app, google camera (barcode scanner), API requests to get 
nutrition associated with barcode values, etc. . . . 

## Instrumented/Unit Testing
All of my pages have implemented testing that can be run with gradle, these tests check to make sure navigation is working, overview is updating values, delete is deleting values, custom entry works for only
correctly entered values, etc. . . .

## Concepts
API requests, Google camera, Queries, MySQL, Relational Databases, Jetpack Compose, Kotlin, Full-Stack, Instrumented Testing, Unit Testing

## Demonstrations
Upon running the app this page will be displayed created by one of my teamates, to begin my part click on the "+" on any of the meals will begin my part.

![alt_text](/app/src/main/res/drawable/HomePage.png)

This page is used to display all food items for the breakfast meal, currently no items have been added so nothing is displayed.

![alt_text](/app/src/main/res/drawable/addfoodnoitems.png)

After clicking "Add", it will bring the user to a page to add items with two options

![alt_text](/app/src/main/res/drawable/AddingType.png)

Clicking on "Custom Entry" will bring the user to this page where the user can manually fill in on values (Error handeling is implemented)

![alt_text](/app/src/main/res/drawable/CustomEntry.png)

The user will then be redirected back to the add option page, if they were to then choose "Barcode Entry" this barcode scanner will show up where they can add a barcode like below.

![alt_text](/app/src/main/res/drawable/BarcodeEntry.png)

Upon the Barcode being scanned the user will be redirected back to this page where they change how many servings they consumed (Error handeling implemented, default 1 serving)

![alt_text](/app/src/main/res/drawable/barcodeentryserving.png)

If the user goes back to the overview page all changes will be displayed

![alt_text](/app/src/main/res/drawable/AddFooditems.png)

Lastly, these changes are also reflected in my teamates home page

![alt_text](/app/src/main/res/drawable/homepagechanges.png)





