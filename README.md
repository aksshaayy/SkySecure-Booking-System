Flight Booking System for Airlines (Java Web Application) ✈️
This is a responsive web-based flight booking system designed for Turkish Airlines, using the Model View Controller (MVC) architecture. The system is built with Java Servlets and Java Server Pages (JSPs). Additionally, user authentication and authorization are managed using Tomcat Roles. The application is secured against SQL Injection and Cross-Site Scripting (XSS) attacks to ensure a safe user experience.

Technologies Used
Frontend: HTML, CSS, JavaScript, jQuery, Bootstrap, JSPs, and AJAX (for flight search functionality)
Backend: Java Servlets, Java-based Models, Microsoft Access (Database)
Web Services: SOAP Web Services (for retrieving seat pricing and availability)
Security: Prevention of SQL Injection and Cross-Site Scripting (XSS), with role-based access control using Tomcat
User Roles
The application implements the following roles:

Airline Admin
Airline Manager
Customer
Workflow and Features
This application allows a single airline to offer seats for online booking. The main steps in the workflow are as follows:

Airline Admin sets seat prices for three seat types:
First Class
Business Class
Economy Class
The admin can create and update the attributes for each seat type.
The total number of seats per flight can be set by the admin.
Airline Manager reviews the seat configurations made by the admin upon login.
The manager approves seat prices or any changes before they are visible to customers.
Only approved seats are available for customers to purchase.
Customers can book seats based on real-time availability.
The system tracks seat availability dynamically, and once all seats are sold, customers can no longer purchase them.
Customers can specify:
Departure and arrival cities
Travel dates
The number of travelers
Once a customer selects a seat and completes the booking process, an itinerary is displayed.
The customer is redirected to a payment page showing the total price. Once they confirm payment, the seat is marked as sold.
An email containing the flight itinerary is sent to the customer upon successful booking.
