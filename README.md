# Budget Tracker

## Table of Contents
- [Description](#description)
- [Deployed Application](#deployed-aplication)
- [User Story](#user-story)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Questions](#questions)

## Description
A Mobile-First, Progressive Web Application (PWA) Budget Tracker that allows a user to track income and expenses online and offline. I added offline capabilities and online data storage to this application. Site data is managed by an added service worker and IndexDB enables local storge for offline use or if internet connection fails. When the user regains online capabilities, the data created from work done in offline mode is sent to the database. The Heroku Site's data is hosted on MongoDB Atlas. By clicking the plus sign in the url bar you can install an icon of the site on your machine.

When the user inputs an expense or deposit, they will receive a notification that they have added an expense or deposit. When the user reestablishes an internet connection, the deposits or expenses added while they were offline are added to their transaction history and their totals are updated. 


### [Deployed Application]


## User Story

```
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```
## Installation
`npm install`
  
## Usage
`npm start`

## Testing
No current testing

## Contributions
* Mallory Korpics https://github.com/mallynnk

## Questions
✉️ Contact me at: [email](mailto:mallory.korpics0@gmail.com) with any questions. 