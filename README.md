# ERSPP

## Project Description 

The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement.

## Technologies Used

- JDK 1.8
- log4j 2.14
- javalin 3.13
- jackson 2.9
- mongo-java-driver 3.12.8
- junit 5.7
- react 17.0

## Features

- secure login
- view reimbursement history
- submit a reimbursement request
- view account info
- edit account info

## Getting Started

- run the following commands in your terminal: 

``` 
git clone https://github.com/huntercbuxton/project1.git

cd project1/proj1-client

yarn start 

```

- open the backend project located in the project1/Project1 folder using intellij
- run the App.main method  

## Usage

the web client has a login (use your account's email address, not username, to log in) for employee accounts.  Once logged in, the user has three main pages, available by clicking the links in the navigation bar at the top of the screen.  On the 'dashboard' they can view a summary of important info. On the 'tools' page they can see their reimbursement request history and the status of each request, and submit a new reimbursement request if needed. On the 'account' page, they can view and edit their personal account info (name, password, etc).

## License

none

