# Expense Reimbursements Application

## Project Description

A Web Application built using Java Servelets, Apache Tomcat, and UIKit which allows for the handling of expense reimbursements.

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

![home](https://i.ibb.co/mywKjHh/exspensly.png)

To start, register a new user either at the bottom of the landing page (Call to Action) or by clicking "Login" then "Create a new account".

![SetAvailability](https://i.ibb.co/HFfsqss/availability.png)

After registering we can proceed to logging in.

![Bulletin](https://i.ibb.co/vY7cpTC/bulletin-board.png)

Upon logging in, users will be able to see historical reimburstment requests, sort requests, and/or create a new request.

![Daily](https://i.ibb.co/JvPjKn2/daily-schedule.png)

Now that a ticket has been submitted, a Financial Manager will need to either approve/reject it. In the mean time, you'll notice that the reimburstment request now shows at the bottom. If reimburstment request history becomes too hectic, the you can always sort reimburstments to quickly find requests.

![DMs](https://i.ibb.co/1sdF4ZY/DMs.png)

You can log in as a financial manager by using the following credentials:
Email: m@m.com
Password: test123

Upon logging in as a manager, the view will look similar to normal users with the exception of a few buttons.
Managers, just like normal users, can create new requests, see historical requests, and sort through historical requests.

However, managers can also approve/reject pending requests and search for all requests by a specific user by their email.

![Weekly](https://i.ibb.co/JctBSJS/week-schedule.png)

## License

This project uses the following license: MIT

