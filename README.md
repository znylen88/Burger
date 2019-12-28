# Burger
Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

## Objective
Create a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. Be sure to follow the MVC design pattern; use Node and MySQL to query and route data in your app, and Handlebars to generate your HTML.

## Description
This project was created using MySQL, Node, Express, Handlebars and a homemade ORM. Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured. Each burger in the waiting area also has a "Devour it!" button. When the user clicks it, the burger will move to the right side of the page. In addition, the app will store every burger in a database, whether devoured or not. Overall, this app was fun and enjoyable to work on and helped me hone in on newly learned coding skills. The app doesn't fully follow the design template as I added a slightly different functionality to the app. While in the instructions the demo doesnt allow the user to change the status of the burger once it has been devoured, my app allows the user to toggle the burger between uneaten and devoured. The app itself could be improved with the addition of DELETE functionality which would allow the user to not only to remove a created burger from the screen but also from the database behind the scenes.

## Usage
1. In the navbar, search "https://sleepy-harbor-18988.herokuapp.com/", this is the app's unique web address hosted via Heroku.

2. Once the page loads, you will see various burgers loaded to the page, either listed as "all gone" or still needing to be "devoured".

3. You can play around with these two buttons and change the burger status to either "all gone" or "devour it" if it still needs to be eaten.

4. There is also an input area where the user can create a new burger and give it the status of "devoured" or "haven't touched". This will give the created burger a specific button corelating to this chosen status.

5. The created data remains persistent even when the page is refreshed or exited out of. 

6. Now go CREATE SOME BURGERS!


## Below is a screenshot of the loaded homepage of the app:

 ![App Function](https://github.com/znylen88/Burger/blob/master/public/assets/js/Demo-Original-Burgers.png)

## Below is a screenshot of ADD burger functionality:

 ![App Function](https://github.com/znylen88/Burger/blob/master/public/assets/js/Demo-Add-New-Burger.png)
 
## Below is a screenshot of MOVING burgers to the right of the screen once "devoured":

 ![App Function](https://github.com/znylen88/Burger/blob/master/public/assets/js/Demo-Move-To-Right-Of-Screen.png)
 

