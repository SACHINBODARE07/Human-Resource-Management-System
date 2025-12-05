# HRMS System 

### **_Human Resource Management_** System Using Node.js and MySQL

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/RedDotz20/IM24_db_HRMS_System.git
Or click Clone or download and select Download ZIP to get this repository.

Database Setup
1. Create or Select a MySQL Database
sql
Copy code
CREATE DATABASE databasename;
USE databasename;
2. Create employees Table
sql
Copy code
CREATE TABLE employees (
  id INT NOT NULL AUTO_INCREMENT,
  firstName VARCHAR(255) NULL,
  lastName VARCHAR(255) NULL,
  age INT NULL,
  sex VARCHAR(1) NULL,
  phoneNumber VARCHAR(255) NULL,
  PRIMARY KEY (id)
);
Environment Variables
Create a .env file in the server directory:

bash
Copy code
cd server
touch .env
Add the following configuration in .env:

ini
Copy code
HOST=your_database_host
USER=your_database_user
PASSWORD=your_database_password
DATABASE=your_database_name
Install Dependencies
bash
Copy code
npm install
Run the Server
Development Build
bash
Copy code
npm run dev
Production Build
bash
Copy code
npm run build
npm run preview
Notes
Make sure MySQL is running and accessible with the credentials provided in .env.

This project covers basic CRUD operations for employee management.

You can extend this system by adding features like authentication, role-based access, and reporting.

pgsql
Copy code

If you want, I can **also create a polished version that includes a short description, features list, tech stack, and screenshots**—making it LinkedIn or GitHub ready.  

Do you want me to do that?






You said:
where is my links


ChatGPT said:
Ah! You want your portfolio, GitHub, and LinkedIn links added in the README so it’s fully personalized. Here's an updated version of your HRMS System README with your links included:

markdown
Copy code
# HRMS System - IM24 Final Project

### **_Human Resource Management_** System Using Node.js and MySQL

This project is developed as a part of the IM24 subject requirements.  
Created by **[Sachin Bodare](https://sachinbodare-portfolio.netlify.app/)**

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/RedDotz20/IM24_db_HRMS_System.git
Or click Clone or download and select Download ZIP to get this repository.

Database Setup
1. Create or Select a MySQL Database
sql
Copy code
CREATE DATABASE databasename;
USE databasename;
2. Create employees Table
sql
Copy code
CREATE TABLE employees (
  id INT NOT NULL AUTO_INCREMENT,
  firstName VARCHAR(255) NULL,
  lastName VARCHAR(255) NULL,
  age INT NULL,
  sex VARCHAR(1) NULL,
  phoneNumber VARCHAR(255) NULL,
  PRIMARY KEY (id)
);
Environment Variables
Create a .env file in the server directory:

bash
Copy code
cd server
touch .env
Add the following configuration in .env:

ini
Copy code
HOST=your_database_host
USER=your_database_user
PASSWORD=your_database_password
DATABASE=your_database_name
Install Dependencies
bash
Copy code
npm install
Run the Server
Development Build
bash
Copy code
npm run dev
Production Build
bash
Copy code
npm run build
npm run preview
Tech Stack
Backend: Node.js, Express.js, MySQL

Database: MySQL

Environment Management: dotenv

Features
CRUD operations for employee management

Easily extendable for authentication and role-based access

Simple and clear MySQL-based data storage

Contact & Links
Portfolio: https://sachinbodare-portfolio.netlify.app/

GitHub: https://github.com/sachinbodare

LinkedIn: https://www.linkedin.com/in/sachinbodare/
