# Introduction 

Node.js is a run-time environment which includes everything you need to execute a program written in JavaScript.
It’s used for running scripts on the server to render content before it is delivered to a web browser.

# Installing

In a web browser, navigate to https://nodejs.org/en/download/. Click the Installer button to download the latest default version. The Node.js installer includes the NPM package manager.

# Creating a Node Server

Initialize NPM in our project folder. </br> In the terminal, navigate to the project directory and execute ```npm init``` </br>
This will create a package.json file which is like a configuration file for the project. </br>
Create the ```app.js``` file in the folder which will contain our main code to be executed
## Adding your own scripts:
To the package.json file, edit it as below:
```
 "scripts": {
    "start": "node app.js"
  }
```
## To run the app
In the terminal: ``` npm start```

## Installing 3rd Party Packages
a) Installing it as a development package(To be used in development) : ```npm install --save-dev``` </br>
b) Installing it as a production dependency(To be used in the end project) : ```npm install --save``` </br>
c) Installing it globally (can be accessed anywhere in the machine) : ```npm install --g``` </br>



