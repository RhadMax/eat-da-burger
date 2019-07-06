# Eat Da Burger
---

### Description
A UCSD Extension Coding Bootcamp homework assignment using NodeJS, ExpressJS and Express-Handlebars, mySQL, and also Heroku as a deployment platform with a little help from the JawsDB by Amazon to make use of a remote database.

---

### Purpose
In this assignment we are taking advantage of technologies like Heroku and JawsDB with mySQL to not only deploy an application to be hosted online via a cloud platform, but also with an integrated mySQL database so that it has persistent information that will persist beyond the scope of the Heroku hosting dyno's runtime. In other words, live hosted databases, baby!

---

### Overview
In this application we make use of html templates with help from handlebars via the express-handlebars node package. We also make use of the MVC paradigm of project management to structure both out file setup, and the content of our script files. We have a homebrewed ORM that is non-database specific, a model script file that ties the ORM to our specific database usage, and then a controller script file to manage our routes. The last little bit of script to handle the router action comes from yet another script file located under our public assets directory, burgers.js. For a project with such small scope the MVC structure may seem like overkill, but that serves as an added purpose for this assignment, by giving us a chance to practice its implementation.

Oh, yeah... and the app is about burgers. You can eat dem. :)

---

### Usage
This application's usage is super simple, as the front end is hosted online and requires no setup of any kind by any user who wishes to engage in some digital burger consumption. 

The app can be found [here](https://eat-da-burger-max.herokuapp.com/)

Simply click the "Eat it!!" buttons to consume a burger on the left hand side of the page, after which it is offically devoured and cannot be interacted with but will visible on the right hand side. You can also add as many new burgers as you want by filling out the text field at the bottom and clicking "Add Burger".

---

### Technologies
### Technologies
This application makes use of the following technologies:

1. Javascript
2. NodeJS
3. GitHub
4. Heroku Cloud Hosting Platform
5. npmJS Packages
    * expressJS
    * mySQL
    * express-handlebars
6. JawsDB via Heroku using mySQL

---

### Credits
This application was developed by me, Max Patten. I made use of skills and references taught to and provided to me by the UCSD Extension Full Stack Coding Bootcamp. The description of its intended functionality were provided to me by the Bootcamp along with reference material and a substantial amount of starting code via similar in class activities which I chose to use as a baseline.