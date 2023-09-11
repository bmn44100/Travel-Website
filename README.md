![Sasa Travel](https://github.com/bmn44100/Travel-Website/blob/main/sasa%20travel.jpg)


# Sasa Travel

The idea behind the project is Sasa Travel. A tour and travel platform for tourists and anyone who wants to travel across East Africa.

## Introduction

The project idea came out of inspiration from nature and the beauty of the African continent and what it has to offer.
Kenya has many tourist attractions and has some of the most attractive destinations in Africa. As a result there are many travel agencies, catering for tourists traveling to various destinations. Beach tourism, eco-tourism, cultural tourism, and sports tourism are all part of the tourism sector in Kenya and East Africa.
This project/website aims to bridge the gap in tours and travel operations.

[Here is a link to a Youtube video of a demo of the app](https://youtu.be/DyuDOAcpEJo)

[Read more about Sasa Travel](https://www.linkedin.com/pulse/sasa-travel-tour-platform-bruno-njeru)

## Installation/Deployment

### Prerequisites

These are the minimum requirements for getting the project up-and-running.

#### PHP

PHP is a server-side programming language that can be embedded into HTML and be used to create dynamic websites and interactive web applications. Since the project is developed in PHP you'll need to have PHP installed on your machine.

[Download and install PHP.](https://www.php.net/downloads.php)

#### XAMPP

XAMPP helps you create and develop your own applications using web server technologies. XAMPP is an open-source localhost-based server with packages that offer several functionalities. That includes the Apache web server, PHP and the MySQL database. This allows you to create the environment you need to run Sasa Travel on your local machine.

[Download and install XAMPP.](https://www.apachefriends.org/download.html)

Once the download has completed, go to your Downloads folder and double-click on the installer to start the installation. To get XAMPP running you also need to install Java SE Development Kit [(JDK)](https://www.oracle.com/java/technologies/downloads/).


#### MySQL

MySQL is a relational database management system (RDBMS) based on Structured Query Language (SQL) and is the primary relational data storage we interact with for data operations.

[Download and install MySQL.](https://dev.mysql.com/downloads/installer/)

#### Git

Git is used for version control and updating the code repository. To clone the project repository from GitHub you'll need to install Git.

[Download and install Git.](https://git-scm.com/downloads)

#### npm/Node.js

npm is the standard package manager for Node.js and JavaScript programming language and lets you develop applications and websites in JavaScript.

[Download and npm/Node.js](https://nodejs.org/en/download)

### Running the website locally

Once XAMPP has finished installing, in a terminal session:

Change the working directory to the root directory of XAMPP local repositories by entering the following command:

```shell
cd C:\Program Files\xampp\htdocs
```

Clone the project repository by entering the following command:

```shell
git clone https://github.com/bmn44100/Travel-Website.git
```
Change to the root directory of the project repository:

```shell
cd C:\Program Files\xampp\htdocs\Travel-Website
```

Open mysql and enter your password when prompted:

```shell
mysql -u username -p
```
Run a CREATE DATABASE command to create a new database and select the database as the current database:

```mysql
CREATE DATABASE IF NOT EXISTS hotel_db;

USE hotel_db;

exit
```
Load the project data from the SQL dump file (hotel_db.sql) to the database (hotel_db):

```shell
mysql hotel_db < hotel_db.sql
```
Start XAMPP (make sure to run as admin) and enable the service modules (Apache and MySQL). At this point, open a web browser and navigate to http://localhost/Travel_Website/project/ to view the website running locally from your local copy of the repository or http://localhost/booking_webstie/project/admin/dashboard.php to get to the admin panel.

If you want to modify the project's source code, you’ll need a text editor/IDE like Visual Studio Code in order to test any changes you make to the website in your browser before committing them to the codebase.

## Author

[Bruno Njeru](#https://www.linkedin.com/in/bruno-njeru/)
