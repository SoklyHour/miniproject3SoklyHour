# miniproject3SoklyHour

### INF601 - Advanced Programming in Python
### Sokly Hour
### Mini Project 3


## Overview
The Fitness Tracker is an Flask application allowing users to track all their fitness activities, including posting workout progress, editing workout progress, deleting workout progress, and observing progress over time in their accounts. Some key features of the application include:

**User Authentication**: The user has a safe and secure login/register system in place where they can create their own accounts, ensuring their data is secure and only they may access it.

**Dynamic Blog Feature**: The users can share their workout achievements and journey of fitness in a dedicated blog section, which creates a community-like ambiance for the people to motivate one another.

**Responsiveness**: The application is built with Bootstrap, making it quite responsive and user-friendly on any device. The design is not only visually appealing but also functional, with a **Bootstrap modal** integrated on the "About Us" page for user engagement.

**SQLite Database**: The application is to be based on a SQLite database, which will store records of the users' information and the records of activities. There should at least be two related tables: one for user information and one for workout records. This should be linked with a foreign key.

**Multi-page Application**: The application consists at least five  pages such as Fitness Tracker page, Login page, Logut page, Registar page, Contact page, About us page and Tips Page.

# Fitness Tracker Application

## Getting Started

Follow these steps to set up and run the Flask application.

### 1. Dependencies

First, install the required dependencies by running:

```bash
pip install -r requirements.txt
```
This will install all the necessary Python packages for the application.
### 2. Setup Database

Once the dependencies are installed, initialize the database by running:

```bash
flask --app flaskr init-db
```
This command will set up the necessary database tables.
### 3. Executing the Program
After setting up the database, you can run the application by executing the following command:
```bash
flask --app flaskr run
```
This will start the Flask development server. The application will be accessible at:
```bash
http://127.0.0.1:5000/
```

## Authors

Contributors names and contact info

SoklyHour
[@SoklyHour](https://www.linkedin.com/in/soklyhour/)


## Acknowledgments
Inspiration, code snippets, etc.
* [flask](https://flask.palletsprojects.com/en/3.0.x/tutorial/)
* [bootstrap](https://getbootstrap.com/)
* [ChatGPT]()