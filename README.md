# budget-app
This is a repository of front-end budget app.
Technologies used:javascript.html,css
# HOW TO USE
![Screenshot from 2020-09-08 19-50-49](https://user-images.githubusercontent.com/62547559/92496520-daf5d380-f215-11ea-9e93-82fe4bd88d6e.png)
Enter your description and value,if you put "+" sign it will navigate to income and negative sign will navigate to expense.
your total available budget can be seen on top of the page
Version of javascript used:ES5;

In JS file of this project  i divided tasks into 3 parts(which you can see on opening app.js file):




1.UI Controller:this is a callback function which deals with displaying of data.

2.Budget Controller:this is a callback function which deals with operations to perform(like caculation,deletion of item from backend of app) and returning data to UI controller;



3.Global Controller:both of above functions were called in this function with some set of event listeners,finally application starts by calling init function.
