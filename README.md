# Decision Maker
> Decision Maker is the app for determining and choosing among options based on the the participants’ preferences. We calculate the scores for each of the options based on Borda Count method and select the option has the highest score.

## Final project

Landing page
!["Landing page top"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/Landing.png?raw=true)
!["Landing page middle"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/Landing2.png?raw=true)
!["Landing page bottom"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/Landing3.png?raw=true)
Get started (login Validation)
!["Login"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/login%20Validation1.png?raw=true)
!["Login"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/login%20Validation2.png?raw=true)
Create poll
!["option main"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/Option%20main.png?raw=true)
!["option filled"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/Admin%20option.png?raw=true)
After Created
!["admin page"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/After%20Create.png?raw=true)
Participants (voting page)
!["voting page"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/Voting.png?raw=true)
!["voting result"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/After%20Voting.png?raw=true)
Admin page (voting Result)
!["voting result"](https://github.com/Ethenalee/midterm-decision-maker/blob/master/Screetshot/Voting%20Result.png?raw=true)





## Usage

When determining the answer to a question, people often benefit from the input of their peers. With Decision Maker, getting these invaluable opinions has never been easier.

## Features
* Create a New Poll
  * The creator of a new poll enters their name and email for access to admin privileges and status updates
  * Each poll has a title, options, and optional descriptions
  * When a poll is finished being created, the user is given two links: an administrative link and a submission link
* Email Confirmation
  * Administrative link and submission links are sent to the creator via email
  * Each time a submission is received, the creator is notified with an email
* Vote
  * Upon visiting the submission link, participants must enter their name and a valid email address
  * The participant is subsequently given access to the poll where they can then rank the options via drag and drop functionality
* Obtain Result
  * Poll data are collected and analyzed via Borda Count
  * Scores are displayed in a bar chart on admin page
  * The creator can choose to email the current results to themselves via the “send email” button 

## Dependencies

- body-parser
- chart.js
- cookie-session
- dotenv
- ejs
- express
- knex
- knex-logger
- mailgun-js
- morgan
- node-sass-middleware
- pg
- uuidv4

## Development setup

- Install all dependencies using 'npm install' command

## Release History

* 0.0.1 First release
