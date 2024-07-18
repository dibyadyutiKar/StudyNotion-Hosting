# StudyNotion Edtech Project

StudyNotion is an EdTech platform built to provide an engaging and efficient learning experience. The platform is built with modern technologies like ReactJS, TailwindCSS, NodeJS, Express, and MongoDB. It includes features such as course tracking with Chart.js, payment processing through RazorPay, and unique profile picture generation with Dicebear's API. The frontend is hosted on Vercel.

## Table of Contents
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Hosting](#hosting)

## Getting Started

To get a local copy of the project up and running, follow these steps:

### Prerequisites

Make sure you have Node.js and npm installed on your machine. You can download Node.js from [here](https://nodejs.org/).

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/dibyadyutiKar/StudyNotion-Hosting.git
    ```
2. Navigate to the project directory:
    ```bash
    cd studynotion
    ```
3. Install the dependencies:
    ```bash
    npm install
    cd server
    npm install
    cd ..
    ```

## Available Scripts

In the project directory, you can run the following commands:

### `npm run start`

Starts the frontend in development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

### `cd server && npm start`

Starts the backend server.
Open [http://localhost:4000](http://localhost:4000) to view the backend API in the browser.

### `npm run dev`

Runs both the frontend and backend concurrently in development mode.

## Project Structure

studynotion/

├── node_modules/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.js
│   ├── index.js
│   └── ...
├── server/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── index.js
│   └── ...
├── .gitignore
├── package.json
├── README.md
└── ...

## Technologies Used

### Frontend

React JS
Tailwind CSS
Chart.js

### Backend

NodeJS
Express
MongoDB

### Other tools

Razorpay for payment processing
Cloudinary 

## Hosting 

### You can view the project at https://study-notion-hosting-frontend-blush.vercel.app/


