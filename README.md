# Tech  Blog

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [Tests](#tests)
* [License](#license)
* [Questions](#questions)

## Description
This is a blogging application that allows developers to publish blog posts and to view and comment on other's posts as well.  This application was written with the intent of creating a full-stack application without starter code.  The application was written in Javascript and utilizes multiple npm packages for the back-end and vanilla CSS and Foundation for the front-end.  The application follows the Model-View-Controller paradigm and uses Sequelize and MySQL for the database for the Models, Express-Handlebars for the Views, and Express to create the API for the Controllers.  The application further uses Express-Session and Connect-Session-Sequelize to add authentication and DotEnv and Bcrypt to hash passwords.  The front-end user inteface was designed using Foundation cards for post data then styled with vanilla CSS.  

## Installation
To run this application, please do the following: 

1. Clone the application's respository from GitHub onto your local drive.  The GitHub URL is: https://github.com/raymondjestrada/homework-week-14-tech-blog.  
2. Set up the ```npm``` package by running the following command in the root directory of the application: 
    
 
`npm install`
   
    
This will download the application's dependencies into your root directory.  You should now have a folder called `node_modules` and a file called `package-lock.json`.  The `package.json` file dependencies should include bcrypt, connect-session-sequelize, dotenv, express, express-handlebars, express-session, mysql2, and sequelize.

3. A `.env` file will need to be created with the following code:

`DB_NAME='tech_blog'`
`DB_USER='root'`
`DB_PW='your-mysql-password-here'`

4. A `.gitignore` file should be created to include your `.env` and the `node-modules` folder if you intend to push your code to a public repository.

## Usage
Once installation is complete, enter the following into the command line:
1.  Run the application by typing the following into the command line at the root directory of the application:

   `npm run start`
    
The application will start and indicate the server is running.

2. Once the server is running:
* Route testing can be completed through Insomnia Core to test out the API routes in the `Controllers` folder.  
* User Interface testing can be completed at the local host URL `http://localhost:3001/`

The live version of this application should look like:
![image](https://user-images.githubusercontent.com/87677207/152344855-3fc084fd-1f8a-47f7-b7f5-aee2cbfc85c4.png).

The live version should be at https://stark-depths-39218.herokuapp.com/.


## Contributing


## Tests
This application uses Insomnia Core as a testing method at link http://localhost:3001/

## License


## Questions
Please contact me through [Github](https://github.com/raymondjestrada) for any questions or comments.

  
