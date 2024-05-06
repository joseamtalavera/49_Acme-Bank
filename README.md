# Acme Bank Project

In this project, you’ll protect a banking application from SQL Injection and Cross-Site Scripting (XSS) attacks, as well as insecure JavaScript.

## About Acme Bank

Welcome to Acme Bank! Acme Bank is a small credit union that provides assistance with deposits, loans, and a wide array of other financial services.

While the skeleton of their web app has been completed, there are certain vulnerabilities that were overlooked.

## Project Goals

In this off-platform project, you will secure the application by:

- Protecting it against Cross-Site Scripting (XSS) Attacks by using helmet, securing cookies, validating and normalizing data with express-validator, and implementing alternative methods to prevent DOM-Based XSS attacks.
- Preventing SQL injection attacks by using prepared statements as well as validating input.
- Preventing Cross-Site Request Forgery (CSRF) attacks by implementing csurf middleware and updating certain view pages to secure any cross-site request vulnerabilities.

## Desktop requirements

- Have Node downloaded on your local machine
- Have a code editor of your choice installed
- Have an empty browser window ready to go
- Have a terminal window open
- Have a DB browser like DBBrowser installed to view the .db file