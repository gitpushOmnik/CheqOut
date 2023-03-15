# CheqOut

## A To-Do List Application

This is a beautiful To-Do List application created using Swift and Realm frameworks. The gradient color scheme implemented in this application is one of the most unique features of them along with varying and bright color schemes. This To-Do list application contains 2 major sections: Categories and Items. A category can be added to the application using the '+' button present at the top right corner of the application. The categories can also be searched using the Search Bar implemented at the top. Moreover, the categories can be deleted by using a tap-delete feature or by using a slide-delete feature. Every category is assigned a specific color which remains persistent throughout the application. Every category then has several different items. These items are implemented using Table View and the cell color of the table view matches the color of the category that it belongs to. Therefore, we see a gradient of colors in a specific category as we go on adding items. Every item cell, once completed, can be tapped on to add a checkmark on the right side of the cell. The cells can be added with a '+' sign at the top right corner of the screen as well as searched using the Search Bar similar to the category View. An item cell can be deleted using the single tap-delete feature or by slide-delete feature. To obtain the gradient color feature, Chameleon Framework is used. Data is persisted across the application with the help of Realm data. Realm helps in useful in storing the data inside the application even if the OS is updated and it is also easier to use and implement as compared to Core Data.

## Application features

### Home Page

The Home Page contains categories with random colours assgned to it which are persisted even after closing the application. This is the magic of the Realm framework

<img src="https://github.com/gitpushOmnik/CheqOut/blob/main/CheqOut/README%20Images/IMG_2696.jpg" width="275" height="600">

### Adding a Category

<img src="https://github.com/gitpushOmnik/CheqOut/blob/main/CheqOut/README%20Images/RPReplay_Final1678838799.gif" width="275" height="600">

### Tapping into a Category Cell

