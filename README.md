
# Inpt Club Management Web Application

This web application allows students of INPT to view all the available clubs and join them. It provides an easy and convenient way for students to explore different club options and get involved in their areas of interest.

<img width="951" alt="image" src="https://github.com/OssamaLouati/webSecurity_project/assets/92301300/0693fae8-4c1c-49a5-975c-6845de551e01">


## Features

- View a list of all clubs at INPT
- Read detailed descriptions and information about each club
- Join clubs directly through the application

## Vulnerabilities and Security Measures

The original version of this web application had vulnerabilities related to SQL injection and blind SQL injection. These vulnerabilities could have allowed malicious users to manipulate the application's database and potentially gain unauthorized access to sensitive information.

To address these security concerns, the following measures have been implemented:

1. **Prepared Statements:** All database queries have been rewritten to utilize prepared statements. This ensures that user input is properly sanitized and treated as data rather than executable code.

2. **Input Validation:** User input is thoroughly validated and sanitized to prevent any malicious attempts to inject SQL code.

3. **Parameterized Queries:** All dynamic input values used in database queries are passed as parameters, eliminating the possibility of SQL injection through user-provided data.

4. **Secure Development Practices:** Best practices for secure web development have been followed, including the use of strong and secure authentication mechanisms, secure session management, and proper error handling to prevent information leakage.


## Getting Started

To run this web application locally, follow these steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/taouchikhtkhouloud/webSecurity_project.git
   ```

2. Install the required dependencies:

   ```shell
   cd your-repo
   npm install
   ```

3. Set up the database connection and configuration. Make sure to update the database credentials in the configuration file (`config.js`) with your own database details.

4. Run the application:

   ```shell
   nodemon app.js
   ```

5. Access the application in your browser at `http://localhost:3300`.

## Team

We would like to thank all contributors and supporters of this project for their valuable input and feedback.




<img width="206" height="306" alt="Screenshot 2023-04-23 172918" src="https://github.com/OssamaLouati/webSecurity_project/assets/92301300/804c845b-2983-48fd-b6ce-daa53683ac14">

<img width="206" height="306" alt="Screenshot 2023-04-23 172918" src="https://github.com/OssamaLouati/webSecurity_project/assets/92301300/eedf7425-c211-4fc4-adb9-33bee316faa0">



