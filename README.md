# Task Manager App (MERN)

# Overview

The Cloud-Based Task Manager is a web application crafted to simplify team task management. Utilizing the MERN stack (MongoDB, Express.js, React, and Node.js), this platform offers an intuitive interface for effective task delegation, monitoring, and collaboration. It is designed for both administrators and general users, providing a robust set of features to boost productivity and organization.

### Why/Problem?

In fast-paced work environments, efficient task management is essential for team success. Traditional methods like spreadsheets or manual tracking systems are often inefficient and error-prone. The Cloud-Based Task Manager addresses these issues by offering a centralized task management platform that facilitates seamless collaboration and improved workflow efficiency.

### **Background**:

With the increasing prevalence of remote work and distributed teams, there is a significant demand for tools that enhance communication and task coordination. The Cloud-Based Task Manager meets this need by leveraging modern web technologies to deliver a responsive and user-friendly task management solution. The use of the MERN stack ensures scalability, while integrating Redux Toolkit, Headless UI, and Tailwind CSS optimizes user experience and performance.

###

## **Admin Features:**

1. **User Management:**

   - Create admin accounts.
   - Add and manage team members.

2. **Task Assignment:**

   - Assign tasks to one or more users.
   - Update task details and status.

3. **Task Properties:**

   - Categorize tasks as to-do, in progress, or completed.
   - Set priority levels (high, medium, normal, low).
   - Add and manage sub-tasks.

4. **Asset Management:**

   - Upload task-related assets, such as images.

5. **User Account Control:**
   - Disable or activate user accounts.
   - Permanently delete or trash tasks.

## **User Features:**

1. **Task Interaction:**

   - Change task status (in progress or completed).
   - View detailed task information.

2. **Communication:**
   - Add comments or chat within task activities.

## **General Features:**

1. **Authentication and Authorization:**

   - User login with secure authentication.
   - Role-based access control.

2. **Profile Management:**

   - Update user profiles.

3. **Password Management:**

   - Change passwords securely.

4. **Dashboard:**
   - Provide a summary of user activities.
   - Filter tasks by status (to-do, in progress, or completed).

## **Technologies Used:**

- **Frontend:**

  - React (Vite)
  - Redux Toolkit for State Management
  - Headless UI
  - Tailwind CSS

- **Backend:**
  - Node.js with Express.js
- **Database:**
  - MongoDB for efficient and scalable data storage.

&nbsp;

## SETUP INSTRUCTIONS

# Server Setup

## Environment variables

First, create an .env file in the server directory containing the following environment variables:

- MONGODB_URI = `your MongoDB URL`
- JWT_SECRET = `any secure secret key`
- PORT = `8800` or your preferred port number
- NODE_ENV = `development`

&nbsp;

## Set Up MongoDB:

1. Setting up MongoDB involves a few steps:

   - Visit MongoDB Atlas Website

     - Go to the MongoDB Atlas website: [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas).

   - Create an Account
   - Log in to your MongoDB Atlas account.
   - Create a New Cluster
   - Choose a Cloud Provider and Region
   - Configure Cluster Settings
   - Create Cluster
   - Wait for Cluster to Deploy
   - Create Database User
   - Set Up IP Whitelist
   - Connect to Cluster
   - Configure Your Application
   - Test the Connection

2. Create a new database and configure the `.env` file with the MongoDB connection URL.

## Steps to run server

1. Open the project in any editor of choice.
2. Navigate into the server directory `cd server`.
3. Run `npm i` or `npm install` to install the packages.
4. Run `npm start` to start the server.

If configured correctly, you should see a message indicating that the server is running successfully and `Database Connected`.

&nbsp;

# Client Side Setup

## Environment variables

First, create the environment variables file `.env` in the client folder. The `.env` file contains the following environment variables:

- VITE_APP_BASE_URL = `http://localhost:8800` #Note: Change the port 8800 to your port number.
- VITE_APP_FIREBASE_API_KEY = `Firebase api key`

## Steps to run client

1. Navigate into the client directory `cd client`.
2. Run `npm i` or `npm install` to install the packages.
3. Run `npm run dev` to run the app on `http://localhost:3000`.
4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

&nbsp;

By following these setup instructions, you will be able to run and test the Cloud-Based Task Manager on your local machine, enabling you to explore its features and functionality.
