# Angular Payment Manager App

## Overview
Angular Payment Manager App is a .NET project designed to be used with an Angular application for managing payments. It provides functionality related to payment processing, tracking, and management.

## Getting Started
1. **Clone the Repository:**
   - Clone this repository to your local machine:
     ```
     git clone https://github.com/your-username/angular-payment-manager-app.git
     ```

2. **Open the Project in Visual Studio:**
   - Navigate to the project directory and open the solution file (`angular-payment-manager-app.sln`) in Visual Studio.
   - In the Solution Explorer, locate the `PaymentDetailsAPI` project.
   - Right-click on the project and select "Set as Startup Project."
   - Build and run the project.

3. **Run the Angular Application:**
   - Open a terminal or command prompt and navigate to the `src/AngularApp` directory within the project.
   - Install Angular dependencies (assuming you have Node.js and npm installed):
     ```
     npm install
     ```
   - Start the Angular development server:
     ```
     ng serve
     ```
   - Visit http://localhost:4200 in your web browser to access the application.

## Database Configuration
1. **Create an SQL Database:**
   - Open SQL Server Management Studio.
   - Create a new database (e.g., "PaymentManagerDB").
   - Note the name of the SQL Server instance (e.g., "HYPERABDULLAH\\SQLEXPRESS").

2. **Configure Connection String:**
   - Open the `appsettings.json` file in the backend repository.
   - Locate the `DevConnection` field.
   - Set the `Server` value to the name of your SQL Server instance (e.g., "Server=HYPERABDULLAH\\SQLEXPRESS").
  
   
