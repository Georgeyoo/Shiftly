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

Frontend
contained within the p2-client directory with the Angular project files contained within p2-client/project2
Ensure you are opening project folders within the p2-client/project2 folder or you will encounter an error when trying to build or serve
Components should be created within the components folder
Please use bootstrap classes for styling. see linked documentation under Technologies
If new classes must be created, comment what they are for.
You may need to run npm install if this is your first pull. Otherwise Angular will not know where to look for some of the inputs

Backend
contained within the p2-server directory
All project files are contained within the com.ex package

persistence: any persistence objects/daos go here
web: any controllers.
models: any models/POJOS
search-engine: Any files related to the search engine.

Note: You will need to populate the paths to the different text files in the .java file


utilities: any utility classes
config: configuration for any beans

## Usage

Welcome to Expens.ly!

![home](https://i.ibb.co/mywKjHh/exspensly.png)

To start, register a new user either at the bottom of the landing page (Call to Action) or by clicking "Login" then "Create a new account".

![register](https://i.ibb.co/nggYQjH/register.png)

After registering we can proceed to logging in.

![login](https://i.ibb.co/vB72PXJ/login.png)

Upon logging in, users will be able to see historical reimburstment requests, sort requests, and/or create a new request.

![create-ticket](https://i.ibb.co/jZ4GwMk/client.png)

Now that a ticket has been submitted, a Financial Manager will need to either approve/reject it. In the mean time, you'll notice that the reimburstment request now shows at the bottom. If reimburstment request history becomes too hectic, the you can always sort reimburstments to quickly find requests.

![sort-ticket](https://i.ibb.co/Qb5t8sH/sort.png)

You can log in as a financial manager by using the following credentials:
Email: m@m.com
Password: test123

Upon logging in as a manager, the view will look similar to normal users with the exception of a few buttons.
Managers, just like normal users, can create new requests, see historical requests, and sort through historical requests.

However, managers can also approve/reject pending requests and search for all requests by a specific user by their email.

![manager-view](https://i.ibb.co/3FvxLdc/manager.png)

## License

This project uses the following license: MIT

