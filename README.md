# Expense Reimbursements Application

## Project Description

A Web Application built using Angular and Java/Spring that abstracts away the pain of manual scheduling!

Deployed: http://team-reston-shift-scheduler.s3-website.us-east-2.amazonaws.com/

## Technologies Used

- Java
- Spring Framework
- Spring ORM
- Spring MVC
- Hibernate
- AWS RDS
- PostgreSQL 42.2.18
- Jenkins
- AWS EC2
- Angular 2+
- TypeScript
- HTML/CSS
- Log4J
- DevOps
- JUnit
- Mockito 1.8.4


## Features

List of features ready and TODOs for future development
- After logging in, users can view their weekly schedule and daily shifts. Additionally, users are able to view a bulletin board with messages from managers, send and receive private messages, as well as update their personal information and daily availability.
- After logging in, managers can view their weekly schedule and daily shifts as well as set the daily shifts of users. Additionally, managers are be able to view a bulletin board with messages from other managers and post messages to all other users. Finally, managers can also send and receive private messages as well as update their personal information and daily availability. 

To-do list:
* Password Encryption
* Forgot Password functionality
* Drop and Trade Shift
* View recent important messages and message notifications
* Specific teams

## Installation

Start by cloning the entire repository to your local machine. 

Frontend Installation:

Head to the `p2-RESTon-angular` directory and fun the command "npm i" to install all of the required packages.
After all necessary packages have been installed, run the command "ng serve -o" to see the front-end portion of the application.

Backend Installation:

Although there are several ways to deploy the back-end portion of this application, the currently deployed version of the application leverages docker/jenkins.
If/when you deploy the back-end, ensure that the front-end API calls (found within the `/services` folder of the Angular application) are pointing to your deployed URL.

## Usage

Welcome to Shiftly!

Upon logging in, you'll be presented with a bulletin board that features all messages by managers.

![Bulletin](https://i.ibb.co/vY7cpTC/bulletin-board.png)

Users can also send private messages to other users.

![DMs](https://i.ibb.co/1sdF4ZY/DMs.png)

By heading to "Schedules", you'll be able to see the weekly schedule for yourself and your team.

![Weekly](https://i.ibb.co/JctBSJS/week-schedule.png)

Additionally, by clicking into a specific day, you'll be able to see the daily view of the schedule.

![Daily](https://i.ibb.co/JvPjKn2/daily-schedule.png)

Finally, you can click on the profile icon at the top right to update your personal information and your daily availability.

![SetAvailability](https://i.ibb.co/HFfsqss/availability.png)

## License

This project uses the following license: MIT

