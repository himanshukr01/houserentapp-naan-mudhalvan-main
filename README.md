# **House Rent App Using the MERN Stack**

A modern web application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) that allows users to list, search, and rent houses. This application provides a seamless experience for both renters and landlords with features such as user authentication, property listing management, and search functionality.



---

## **Overview**

This **House Rent App** allows users to:
- **Landlords**: List their properties with detailed information, images, and pricing.
- **Renters**: Browse available properties, filter by location, price, and other criteria, and apply to rent.
- The app includes a **JWT authentication system** for secure logins and access control.

---

## **Table of Contents**

- [Installation](#installation)
- [Usage](#usage)
- [Frontend and Backend Description](#frontend-and-backend-description)
- [Screenshots](#screenshots)
- [Project Report](#project-report)
- [Demo Video](#demo-video)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## **Installation**

To set up the project locally, follow the steps below:

### **1. Clone the Repository**

```bash
git clone https://github.com/yourusername/house-rent-app.git
2. Navigate to Project Directory
bash
Copy code
cd house-rent-app
3. Install Dependencies
For both frontend and backend dependencies, follow these steps:

Frontend (React)
bash
Copy code
cd client
npm install
Backend (Node.js/Express)
bash
Copy code
cd server
npm install
4. Run the Application


Frontend
bash
Copy code
cd client
npm start
Backend
bash
Copy code
cd server
nodemon index.js
Now, the application should be running at:

Frontend: http://localhost:3000
Backend: http://localhost:5000
Frontend and Backend Description
Frontend (React.js)
The frontend of the House Rent App is built using React.js, which allows for a fast and interactive user interface. It handles all the user interactions, display of property listings, and manages the client-side routing using React Router.

Key Features:
User Authentication: Using JWT tokens to handle login and registration for users.
Property Listings: Allows users to view, filter, and search for available properties.
Add Property: Landlords can add their properties with details like name, price, description, and images.
Responsive Design: The frontend is fully responsive, ensuring an optimal user experience across devices.
Technologies used:

React.js: For building the user interface.
React Router: For navigating between pages without reloading.
Axios: For making HTTP requests to the backend API.
Bootstrap / Tailwind CSS: For styling the application.
Backend (Node.js/Express.js)
The backend of the app is built using Node.js with the Express.js framework. It serves as the API that interacts with the database and handles requests from the frontend. The backend manages all logic related to the property listings, user authentication, and database interactions.

Key Features:
User Authentication: Secured with JWT tokens to manage user sessions and ensure that only authenticated users can access restricted routes.
Property Management: Landlords can create, update, and delete property listings, while renters can browse the available properties.
Database Interaction: The backend interacts with MongoDB, storing user information, property data, and user interactions.
RESTful API: The backend exposes a RESTful API for the frontend to interact with, using standard HTTP methods (GET, POST, PUT, DELETE).
Technologies used:

Node.js: For the backend server.
Express.js: To handle HTTP requests and create a RESTful API.
MongoDB: For database storage of users and property listings.
JWT: For user authentication and session management.
Multer: For handling file uploads, like property images.
Screenshots
Here are some screenshots of the application:

Login Page

Dashboard View

Property Listing Page

Project Report
For a detailed explanation of the project, including system architecture, features, and challenges faced, refer to the Project Report.

Demo Video
Watch the demo video for a full walkthrough of the project:

Watch the Demo

Alternatively, you can download the demo video from the repository:

bash
Copy code
cd demo_video
open project-demo.mp4
License
This project is licensed under the MIT License.

Acknowledgments
Technologies Used:

MongoDB, Express.js, React.js, Node.js
JWT for authentication
Multer for file uploads
Special Thanks To:

[Mentor's Name, if applicable]
[Classmates or collaborators, if any]
Inspiration:

[Any inspiration or tutorial sources you followed]
Contact
For any questions, feedback, or collaboration opportunities, feel free to reach out:

GitHub: @yourusername
Email: your.email@example.com
markdown
Copy code

### Key Changes:
1. **Frontend Description**: Explains that the frontend uses **React.js** for building the user interface and managing user interactions. Includes key features like **user authentication**, **property listings**, and **responsiveness**.
2. **Backend Description**: Details the backend architecture, which uses **Node.js** and **Express.js** to handle requests and interact with the **MongoDB** database. It includes features like **JWT authentication**, **property management**, and a **RESTful API**.
3. **Technologies Used**: Lists the technologies used for both the frontend and backend (React.js, Node.js, Express.js, MongoDB, JWT, etc.).

### Folder Structure:

house-rent-app/ ├── client/ # React frontend files ├── server/ # Node.js/Express backend files ├── images/ # Folder for screenshots │ ├── login-page.png │ ├── dashboard-view.png │ └── property-listing.png ├── docs/ # Folder for the project report │ └── project-report.pdf ├── demo_video/ # Folder for the demo video │ └── project-demo.mp4 ├── LICENSE # License file (e.g., MIT License) ├── README.md # This README file └── .gitignore # Git ignore file for unnecessary files

vbnet
Copy code

This version now provides clear descriptions of the **frontend** and **backend** parts of your application, highlighting the key features and technologies used. Let me know if you need any further adjustments!






NOTE: 
CHECK THIS REPO AND SEE MY  PROJECT REPORT  IN GITHUB FOLDER:
 :https://github.com/durgeshkumarraj/houserentapp-naan-mudhalvan/new/main?filename=README.md
VIDEO DEMO LINK:
https://drive.google.com/file/d/1biN_fh08MAAA-ZITkwoahZMWTRmtJFI7/view?usp=drivesdk



