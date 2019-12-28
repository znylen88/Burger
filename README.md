# Burger
Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

## Objective
Create a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. Be sure to follow the MVC design pattern; use Node and MySQL to query and route data in your app, and Handlebars to generate your HTML.

## Description
This project was created using newly learned material related to creating servers, using MySql, and inquier prompts. It focuses heavily on user input to view, add, and update material via user prompts. The prompt answers work in conjunction with MySql methods such as "update" and "insert" to achieve this goal. Overall, the general backbone of the application was fairly straightforward to set up, however I did encounter some hangups. I still cant figure out how to best render out employee roles (which are set as an ID in the employee table) as an actual job title found within the role's table. This has to be achieved using the join method but I have yet to determine how to use it in this scenario. I will continue to update this project to fully achieve all the objectives set forward in the project ReadMe.

## Usage
1. In the navbar, search "https://sleepy-harbor-18988.herokuapp.com/", this is the app's unique web address hosted via Heroku.

2. Once the page loads, you will see various burgers loaded to the page, either listed as "all gone" or still needing to be "devoured".

3. You can play around with these two buttons and change the burger status to either "all gone" or "devour it" if it still needs to be eaten.

4. There is also an input area where the user can create a new burger and give it the status of "devoured" or "haven't touched". This will give the created burger a specific button corelating to this chosen status.

5. The created data remains persistent even when the page is refreshed or exited out of. 

6. Now go CREATE SOME BURGERS!


## Below is a screenshot of Add/View department functionality in terminal:

 ![App Function](Demo-Add-New-Burger.png)

## Below is a screenshot of Add/View role functionality in terminal:

 ![App Function](Add-View-Roles.png)
 
## Below is a screenshot of Add/View employee functionality in terminal:

 ![App Function](Add-View-Employees.png)
 
 ## Below is a screenshot of the Update employee role functionality in terminal:
 
 ![App Function](Update-Employee-Role.png)

