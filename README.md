# myEcommerceORM
## Description
- This project will take a working Express.js API and configure it to use Sequelize to interact with my MySQL database
## Table of Contents
  - [Installation](#installation)
  - [Required Task](#required-task)
  - [User Instruction](#user-instruction)
  - [Command line code](#command-line-code)
  - [Credits](#credits)
  - [License](#license)
  - [Tests](#tests)
  - [Deploying to Heroku](#deploying-to-heroku)

## Installation

- Here are the installation process :
  - [1] Here is the repo for this application https://github.com/thalim-glam/Express_noteTaker 
  - [2] Clone the repository or download the zip folder.
  - [3] Open the source code in your code editor.
  - [4] Open the integrated terminal or git bash to test the application.
  - [5] Please refer to [Tests](#tests) section for further information regarding testing.

## Required Task 

- The frontend is included in the starter code
- Student HW is to build the back end, connect the two, and then deploy the entire application to Heroku.
- User Story 
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
- Acceptance criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## User Instruction

  - Click here for the repository: https
  - Click here for Readme file: https
  - Click here for the Heroku-deployed link :  
  - When the Note Taker page loads, click on the "Get started".
  - Enter text into the "Title" and "Text" fields and click "Save Note".
  - To access previous notes, click on the saved notes on the left.
  - To clear form click the "Clear Form" button.
  - Here is a sample screenshots of my application :
    - Walkthrough Video link: https://drive.google.com/file/d/1nA77FflJy1JEgvdCwOdFIknbdtt6UufC/view
    - Initial Page ![Screenshot of Initial Page](./public/images/initial_page.png)
    - Existing notes ![Screenshot of Showing existing notes](./public/images/showing_exiting_note.png)
    - Saving New note ![Screenshot of Saving new note](./public/images/saving_new_note.png)
    - Deleting Note (BONUS) ![Screenshot of Deleting previously saved note](./public/images/deleted_note.png)

## Command line code

I used the following command lines:
- npm run start [ You may need this to start the server ]
- npm i express [To install modules if you do ot see it ]
- git status
- git add -A
- git commit -m "Comment goes here"
- git branch
- git pull origin main
- git push
- git checkout main
- git checkout -b feature/add-branch

## Credits

Apart from me :D the credit also goes to my Instructor, TAs, Tutor, Classmates, and 
- Google (my best buddy)
- Geeks for Geeks
- Stack Overflow
- MDN web doc
- Class Recordings
- Tutorials Teacher

## License
 ![Github license](https://img.shields.io/badge/license-MIT-blue.svg) 

## Tests

To test this application please type, 
  - npm i [To install node modules ]
  - npm i express [To install express ]
  - npm run start [ To start the server ]
  - Open web browser and type http://localhost:3001
  - You can also use Innsomnia/postman to test the application
  - Click here for deployed Heroku link : https://ucbth-ch11-d97ba2745641.herokuapp.com/

## Deploying to Heroku
:) This is suggested in the Heroku website.
:) Therefore using it for testing purpose.
:) Please feel free to click the button below 

```
$ heroku create
$ git push heroku main
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Done By: Tasneem Halim 😎
