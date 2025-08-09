# Food Recommendation System (MERN Stack)

## Overview

This Food Recommendation System is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The app helps users discover personalized food recommendations based on their preferences, browse various cuisines, and explore dishes tailored to their tastes.

The project also integrates Firebase for authentication and real-time updates, making the app secure and interactive.

---

## Features

- User signup and login with Firebase Authentication  
- Personalized food recommendations based on user preferences  
- Browse and filter cuisines and dishes  
- Save favorite dishes and build custom food plans  
- Responsive UI with React.js  
- RESTful API backend using Node.js and Express.js  
- Data stored and managed with MongoDB and Mongoose  

---

## Technologies Used

| Frontend        | Backend           | Database     | Authentication & Hosting  |
|-----------------|-------------------|--------------|---------------------------|
| React.js        | Node.js + Express | MongoDB      | Firebase Authentication   |
| React Router    | REST API          | Mongoose ORM | Firebase Realtime Database |

---

## Firebase Configuration

To connect with Firebase services, configure your Firebase keys in your frontend (via environment variables recommended):

```js
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
