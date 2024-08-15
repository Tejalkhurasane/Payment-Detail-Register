##Overview
This project is a web application that allows users to perform CRUD (Create, Read, Update, Delete) operations on payment details. The frontend is built using Angular, while the backend is developed using .NET Web API.

##Features
Create Payment Details: Add new payment details including card number, cardholder name, expiration date, and CVV.
Read Payment Details: View a list of all saved payment details.
Update Payment Details: Edit existing payment details.
Delete Payment Details: Remove payment details from the database.

Technologies Used
Frontend (Angular)
Angular: A TypeScript-based open-source web application framework.
Angular CLI: A command-line interface tool to scaffold and manage Angular applications.
Bootstrap: For responsive design and UI components.

Backend (ASP.NET Core Web API)
ASP.NET Core: A cross-platform framework for building web APIs.
Entity Framework Core: An ORM framework for working with databases.
SQL Server: For database management.

##Prerequisites
For the Backend
.NET SDK (version X.X or higher)
SQL Server
Visual Studio (optional but recommended)

For the Frontend
Node.js (version X.X or higher)
Angular CLI

#API Endpoints
GET /api/paymentdetails: Get all payment details.
GET /api/paymentdetails/{id}: Get payment details by ID.
POST /api/paymentdetails: Create new payment details.
PUT /api/paymentdetails/{id}: Update payment details by ID.
DELETE /api/paymentdetails/{id}: Delete payment details by ID.
Angular Components
AppComponent: The root component.
PaymentDetailsComponent: Displays the list of payment details.
PaymentDetailFormComponent: Form for creating and updating payment details.
