**ZoomBazaar**
**Full Stack E-Commerce Website with Angular and Spring Boot**
ZoomBazaar is an e-commerce platform designed to provide a seamless shopping experience. Built using modern Java and web development technologies, this application integrates robust backend features with a dynamic, user-friendly frontend.

Technologies Used
-Angular 16.2.1: Front-end framework for single-page web applications. -TypeScript 5.1.6: Adds static typing with optional type annotations to JavaScript. -Spring Boot 3.1.2: Back-end framework for Java-based web applications. -Java 17.0.8: Object-oriented programming language. -MySQL 8.0.17: Relational database management system. -Okta 2.1.6: Cloud-based identity and access management platform.

**Features**
User-friendly interface with easy navigation for product browsing
Secure user authentication and authorization with Okta
Dynamic product listings and shopping cart functionality
Scalable backend using Spring Boot and Hibernate
RESTful API design for seamless frontend-backend communication
Role-based access control with Spring Security
Responsive design with Bootstrap for compatibility across devices
Prerequisites 🛠️ -Node.js and npm: Required for managing Angular dependencies. -Angular CLI: Install globally for Angular application management. -Code Editor: Choose from Visual Studio Code or IntelliJ. -Java Development Kit (JDK): Compatible with JDK 8, 11, or 16+.

**Setup Instructions**
Clone the Repository:
git clone <repository-url>

**Installation **📥 -Clone the repository: git clone https://github.com/Asif12as/OwN-IT--E-Commerce.git -Navigate to the db-scripts directory: cd 01-stater-files/db-scripts -Execute each SQL script using MySql Workbench to create the database schema and tables. -Navigate to the back-end directory: cd 02-backend/spring-boot rest api -Open the project in IntelliJ IDE and let Maven automatically build and install dependencies. -Navigate to the front-end directory: cd frontend/angular-ecommerce -Install Angular CLI: npm install -g @angular/cli -Install front-end dependencies from package.json. Usage 🚀

**2.Backend Setup:** Configure your database settings in application.properties. Build the backend with: mvn clean install

Then run the backend: mvn spring-boot:run

Frontend Setup: Navigate to the Angular project directory: cd frontend
Install dependencies: npm install

Run the Angular development server: ng serve

Configure Okta Authentication: Update the Okta client settings as per your Okta app configuration.

Contributing This project was a team effort led by Ravi Prakash, with valuable contributions from Guddu Kumar, Md. Asif, Dharmendra Kumar, and Vipin Thakre.
