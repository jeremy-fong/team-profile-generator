# Team Profile Generator

## Table of Contents
1. [Title](#title)
2. [Project](#project)
3. [Description](#description)
4. [Installation](#installation)
5. [Usage](#usage)
6. [User Story](#user-story)
7. [Acceptance Criteria](#acceptance-criteria)
8. [Video Preview of Project](#video-preview-of-project)
9. [Source](#source)

## Title :
### Team Profile Generator

## Project :
### *Team Profile Generator*

## Description :
* This project uses inquirer@8.2.4, NodeJS, and Jest
* This project will generate an index.HTML file according to the information the user provided 

## Installation :
The user needs to install node for this project. 

## Usage :
- Open the index.js in the terminal, then enter node index.js in the command-line.
- The user will then input information according to the questions asked.
- Based on the information the user provided, a team profile index.HTML will be created in the dist folder.

## User Story :
```md
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```

## Acceptance Criteria :
```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
```


## Video Preview of Project :
[Video Preview](https://drive.google.com/file/d/1GCLnTe3E6DDYM5PoCQ-_pRlO8XdvlNSk/view)

## Source :
- GitHub Link: https://github.com/jeremy-fong/team-profile-generator