# Express.js-Note-Taker

A note taking app that is used to write notes, save notes and delete notes.


# Description 

The main purpose to build to develop a note taker, an application that can be used to write and save notes. The app saves and retrieves user-generated note data from a JSON file using an Express.js back end.

The front end of the application has already been created. It is my responsibility to create the back end, connect the two, and then deploy the completed application to Heroku.


# Installation & Usage

Project clone To install all the required packages, enter the following code in your terminal: npm i 

After you've installed all of the packages, open a terminal and type the following code into the command line: node server.js

This will start the server where the page can be found at localhost:3001. To terminate your server in your terminal, enter: command + c


## User Story

```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```


## Acceptance Criteria

```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page

WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column

WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page

WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes

WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column

WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```

# So far what has been achieved and further improvements?

All requirements above has been achieved.

# To access Github Repository 

1. https://github.com/samira0101/Express.js-Note-Taker.git

To access Application deployed at Heroku

2. 

# Screenshots displaying homepage and saved notes of the application

![](images\notes.png)

![](images\homepage.png)

# References

1. https://www.npmjs.com/package/express
2. https://www.npmjs.com/package/uniqid
3. https://www.w3schools.com/nodejs/nodejs_filesystem.asp
4. https://expressjs.com/
5. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON
6. https://expressjs.com/en/guide/routing.html
7. https://birmingham.bootcampcontent.com/university-of-birmingham/UBHM-VIRT-FSF-PT-11-2021-U-LOL
8. https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide
