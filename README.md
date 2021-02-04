# Expense Reimbursements Application

## Project Description

A Web Application built using Java Servelets, Apache Tomcat, and UIKit which allows for the handling of expense reimbursements.

Deployed: ![http://team-reston-shift-scheduler.s3-website.us-east-2.amazonaws.com/](http://team-reston-shift-scheduler.s3-website.us-east-2.amazonaws.com/)

## Technologies Used

- Apache Tomcat 8.5.60
- UIKit
- Jackson Core (Object Mapper)
- Hibernate 4.3.11.Final
- Java Servlet API 3.1.0
- Log4j API 2.13.0
- PostgreSQL 42.2.18
- JUnit
- Mockito 1.8.4


## Features

List of features ready and TODOs for future development
- After registering or logging in, users can submit tickets specifying an amount, category, and department.
- Financial Managers can approve/deny a reimbursement request. To avoid fraudulant behavior Financial Managers are unable to approve/deny their own reimburstment requests. 

To-do list:
* Complete implementation of receipt (PDF/jpg/png) upload.
* Addition of email confirmation upon new user registration.

## Getting Started
   
In order to see this project in action, you will need a few things:

1) Be sure to have Apache Tomcat 8.5.60 installed.
2) Be sure to have the Java 8 runtime environment installed.

If both of the pre-requisites above are met, go ahead and clone this repo by using the below command:

        git clone https://github.com/Georgeyoo/ExpenseReimburstment.git

Once cloned, copy the .war file located within the /target directory and paste it into your tomcat webapps folder.

Once the .war is run, by default you will be able to view the application at http://localhost:8080/p1/api/landing

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

