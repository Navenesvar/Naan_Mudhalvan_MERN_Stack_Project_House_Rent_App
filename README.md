# House Rent App (MERN Stack)
This is a House Rent application built using the MERN stack (MongoDB, Express, React, Node.js) that allows three types of users: Admin, Owner, and Renter. The app provides functionalities such as managing users, properties, and bookings for the Admin, while Owners can add/edit properties and Renters can book properties.

## Features
### Renter/Tenant
Create an account and log in using email and password.
View all available properties on the dashboard.
Click on a property to get detailed information about the property and owner.
Fill in a small form to express interest in renting the property.
Track booking status, which initially appears as "Pending" and can be updated by the property owner.
### Admin
Approve users as Owner to allow them to add properties.
Monitor and manage all properties, bookings, and users (Renter and Owner).
Enforce platform policies, terms of service, and privacy regulations.
### Owner
Get approval from the Admin to activate the Owner account.
Perform CRUD operations on properties (Add, Edit, Delete).
Change property availability and status.
### Getting Started
### Prerequisites
Before you can run the app, make sure you have the following installed on your system:

Node.js (LTS version preferred)
MongoDB (locally installed or use a cloud database like MongoDB Atlas)
## Steps to Start the App
### Step 1: Clone the Repository
#### Clone the repo to your local machine:
git clone https://github.com/Navenesvar/Naan_Mudhalvan_MERN_Stack_Project_House_Rent_App.git
### Step 2: Backend Setup
#### Navigate to the backend directory:
cd Naan_Mudhalvan_MERN_Stack_Project_House_Rent_App/backend
#### Run the following commands
npm install
npm start
The backend will run on http://localhost:8000 as per configuration.
### Step 3: Frontend Setup
#### Navigate to the frontend directory:
cd Naan_Mudhalvan_MERN_Stack_Project_House_Rent_App/frontend
#### Run the following commands
npm install
npm start
The frontend will run on http://localhost:3000 by default.

### Technologies Used
Frontend: React.js, Material UI, Axios
Backend: Node.js, Express, MongoDB
Authentication: JWT (JSON Web Token) for user authentication
State Management: React hooks (useState, useEffect)
