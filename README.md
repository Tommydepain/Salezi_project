FNAC Strapi Backend API
=======================
 
This project is a Strapi-based backend application connected to a SQLite database, designed to manage API functionalities for FNAC's sellers. This README describes how to launch the API and its features, as well as how to use the provided Postman collection.
 
Prerequisites
-------------
 
*   Node.js
*   npm
*   SQLite
*   Postman
 
Installation and Setup
----------------------
 
1.  **Clone the Git repository:**
   
    bashCopy code
   
    `git clone [URL_OF_GITHUB_REPO]`
   
2.  **Install dependencies:**
   
    Copy code
   
    `npm install`
   
   
   
3.  **Start the Strapi server:**
   
    arduinoCopy code
   
    `npm run develop`
   
 
   
 
Your Strapi server should now be running on `http://localhost:1337`.
 
Database Configuration
----------------------
 
The SQLite database is configured by default. Check and modify configurations in the `database.js` file.
 
API Features
------------
 
*   **Collections / Single Types / Components:**
    *   Create and manage collections for products, sellers, etc.
*   **Roles and Permissions:**
    *   Configure roles and permissions for different users.
*   **Custom Strapi Dashboard:**
    *   Display information about stock and sales.
 
Using the Postman Collection
----------------------------
 
1.  Import the Postman collection JSON file into your Postman application.
2.  Test and explore the different routes of the API.
 
Going Further
-------------
 
If you have extra time, consider adding elements related to stock and sales on the dashboard, using data provided by the API:
http://localhost:1337/documentation/v1.0.0 
 
Contributions
-------------
 
Contributions to the project are welcome. Please follow standard contribution guidelines for submissions.
Dispose d’un menu contextuel