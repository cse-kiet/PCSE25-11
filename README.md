Title of Project: [STUDYVERSE]


Team Members:

1- [ANAND RASTOGI]
2- [AVINASH TRIPATHI]
3- [ADITYA KHESARI]


Steps for Execution:
[STEP 1] Clone the Repository
git clone https://github.com/cse-kiet/PCSE25-11.git
cd StudyVerse

[STEP 2] Install Server (Backend) Dependencies
cd server
npm install

[STEP 3] Set Up Environment Variables
Create a .env file in the /server directory with the following (example):
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

[STEP 4] Start the Backend Server
npm run dev

[STEP 5] Install Client (Frontend) Dependencies
In a new terminal window:
cd ../client
npm install

[STEP 6] Start the Frontend React App
npm start
[STEP 7] Open the Application in Browser
Visit:
http://localhost:3000

[OPTIONAL STEP] Production Build (if deploying)
npm run build

![image](https://github.com/user-attachments/assets/fd623cdd-2116-49f5-8806-5bfeb8a758ac)
![image](https://github.com/user-attachments/assets/d7a498e9-c04f-4b26-882e-d4e3f8a4de83)



Checklist:
Final Project Report
Certificate VII Semester (Dated: December 2024).
Certificate VIII Semester (Dated: May 2025).
Synopsis
Final Presentation
Source Code
Database dump (.sql file)
If a web project, then a Docker file for deployment
README (This file)
