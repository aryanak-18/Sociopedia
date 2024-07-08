# Sociopedia

Sociopedia is a full-stack dynamic web application designed for multimedia sharing and social interaction. Users can create profiles, share content, follow content feeds, and engage in comment threads. The application is built using modern web technologies including ReactJS for the frontend and Express with NodeJS for the backend, along with MongoDB for data storage.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User profiles to view saved user information.
- Multimedia sharing including images and videos.
- Content feeds to keep up with user activities.
- Comment threads to enhance user engagement.
- Secure user authentication.
- Light and Dark modes.

## Technologies

- **Frontend:** ReactJS
- **Backend:** NodeJS, Express
- **Database:** MongoDB

## Installation

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB set up and running.

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aryanak-18/Sociopedia.git
   cd Sociopedia
   ```

2. **Install dependencies:**
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the `server` directory and add the following variables:
   ```plaintext
   MONGO_URL='<Your MongoDB connection string>'
   JWT_SECRET='<Your JWT secret>'
   ```
   <br/>
   
   Create a `.env` file in the `client` directory too and add the following variables:
   ```plaintext
   REACT_APP_BACKEND_URL=http://localhost:3001
   ```

4. **Run the application:**

   Open two terminal windows or tabs.

   - In the first one, navigate to the `server` directory and start the backend server:
     ```bash
     cd server
     npm start
     ```

   - In the second one, navigate to the `client` directory and start the frontend server:
     ```bash
     cd client
     npm start
     ```

   The application should now be running locally on `http://localhost:3000`.

## Usage

- **Sign up/Login:** Create an account or log in using your credentials.
- **Feed:** Browse through content shared by users.
- **Share:** Post multimedia content to your feed.
- **Engage:** Comment on posts to interact with other users.
- **Themes:** Switch between Light and Dark modes.
<br/>

---


