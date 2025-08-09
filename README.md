# Trip Planner MERN Application

## Overview

Trip Planner is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) designed to help users plan, organize, and manage their trips effortlessly. The app allows users to browse destinations, filter cuisines, save favorite places, and manage trip details in a user-friendly interface.

This project also integrates **Firebase** for authentication and real-time database services, enhancing security and scalability.

---

## Features

- User authentication and authorization via Firebase Authentication  
- Interactive trip planning dashboard  
- Filter options for cuisines and destinations  
- Data persistence with MongoDB and Mongoose  
- Responsive UI built with React.js  
- RESTful API backend powered by Node.js and Express.js  

---

## Technologies Used

| Frontend        | Backend           | Database     | Authentication & Hosting  |
|-----------------|-------------------|--------------|---------------------------|
| React.js        | Node.js + Express | MongoDB      | Firebase Authentication   |
| React Router    | REST API          | Mongoose ORM | Firebase Realtime Database |

---

## Firebase Configuration

To connect your app with Firebase services, you need to create a Firebase project and add the following configuration to your frontend code (preferably via environment variables):

```js
// Example: firebaseConfig.js or environment variables
const firebaseConfig = {
  apiKey: "YOUR_API_KEY_HERE",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};

export default firebaseConfig;
