Airline Management System
Welcome to the Airline Management System, a web-based application designed to streamline airline operations, including flight booking, passenger management, and flight scheduling. This project demonstrates full-stack development and testing skills, built to simulate real-world airline reservation systems. It was developed to enhance my portfolio for roles requiring development and testing expertise, such as the Testing and Development position at Nykaa.
Table of Contents

Features
Tech Stack
Setup Instructions
Running Tests
Deployment
Screenshots
Contributing
Contact

Features

Flight Search: Users can search for flights based on date, source, and destination.
Booking System: Customers can book tickets, select seats, and view itineraries.
Admin Dashboard: Admins can manage flights, schedules, and passenger details.
Passenger Management: Create, update, or delete passenger records.
Responsive UI: User-friendly interface accessible on desktop and mobile.
Automated Testing: Unit and integration tests ensure system reliability.

Tech Stack

Frontend: HTML, CSS, JavaScript, Bootstrap (or React, if applicable)
Backend: Java, Spring Boot (or PHP/Node.js, based on common airline systems)
Database: MySQL (or SQLite/PostgreSQL)
Testing: JUnit (for Java), PHPUnit (if PHP), or Selenium for UI testing
Tools: Git, Maven (if Java), Docker (optional for deployment)

Setup Instructions
Follow these steps to run the project locally.
Prerequisites

Python 3.9+ (if Python-based backend)
Node.js (if using JavaScript-based frontend)
Java 11+ (if Java-based backend)
MySQL (or your database choice)
Git
VS Code (recommended editor)

Installation

Clone the Repository:
git clone https://github.com/nikhal99/Airline-Management-System.git
cd Airline-Management-System


Backend Setup:

If Java/Spring Boot:
Install Maven: mvn --version to verify.
Configure MySQL:
Create a database: CREATE DATABASE airline_db;
Update application.properties with your database credentials:spring.datasource.url=jdbc:mysql://localhost:3306/airline_db
spring.datasource.username=root
spring.datasource.password=your_password




Run: mvn spring-boot:run.


If PHP:
Import the provided database_file.sql into phpMyAdmin.
Update database credentials in config.php.
Run a local server: php -S localhost:8000.




Frontend Setup:

If HTML/CSS/JS:
Open index.html in a browser or serve via a local server (e.g., VS Code Live Server).


If React:
Navigate to the frontend folder: cd frontend.
Install dependencies: npm install.
Start the app: npm start.




Database Setup:

Import the SQL schema (e.g., database_file.sql) into MySQL:mysql -u root -p airline_db < database_file.sql


Verify tables (e.g., flights, passengers) exist.



Running the Application

Backend: Ensure the server is running (e.g., http://localhost:8080 for Spring Boot).
Frontend: Open http://localhost:3000 (React) or http://localhost:8000 (PHP/HTML).
Access features:
Customer: Search flights, book tickets.
Admin: Log in to manage flights (use default admin credentials if provided).



Running Tests
The project includes automated tests to ensure reliability.

Backend Tests:

If Java: mvn test (uses JUnit).
If PHP: phpunit tests/.
Example: Tests verify flight search and booking APIs.


Frontend Tests:

If React: cd frontend && npm test (uses Jest).
Tests check UI components like the search bar.


UI Tests:

Run Selenium tests: python -m pytest tests/test_selenium.py.
Requires ChromeDriver (download from chromedriver.chromium.org).



Deployment
The application is deployed for live access:

Frontend: [Netlify URL] (e.g., https://nikhal-airline-system.netlify.app)
Backend: [Render URL] (e.g., https://airline-system.onrender.com)
GitHub Repository: https://github.com/nikhal99/Airline-Management-System

To deploy yourself:

Backend (Render):
Push code to GitHub.
Create a Render Web Service, set runtime (e.g., Java), and use mvn spring-boot:run (or equivalent).


Frontend (Netlify):
Push frontend code to GitHub.
Deploy via Netlify, linking your repo.



Screenshots
Search flights and book tickets.Manage flights and passengers.  
Note: Add screenshots to the screenshots/ folder and update paths above after capturing them.
Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a branch: git checkout -b feature/your-feature.
Commit changes: git commit -m "Add your feature".
Push: git push origin feature/your-feature.
Open a Pull Request.

Please include:

Meaningful commit messages.
Tests for new features.
Updated README if needed.

Contact

Author: Nikhal 
GitHub: nikhal99

For issues or suggestions, open an issue on GitHub.

Thank you for exploring the Airline Management System!
