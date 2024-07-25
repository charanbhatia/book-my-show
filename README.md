# Book My Show - Movie Booking System

## Overview

Book My Show is a full-stack movie booking system built using the MERN (MongoDB, Express, React, Node.js) stack. This project provides a seamless user experience for browsing movies, selecting showtimes, and booking tickets online.

## Features

- User authentication and authorization
- Browse movies and view details
- Select showtimes and book tickets
- Secure payment processing using Stripe
- User profile management
- Admin panel for movie and showtime management

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **State Management**: Redux
- **Payment Processing**: Stripe
- **Authentication**: JSON Web Tokens (JWT)

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/charanbhatia/book-my-show.git
   cd book-my-show
   ```

2. Install dependencies for both frontend and backend:
   ```
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the backend directory and add the following:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. Start the backend server:
   ```
   cd backend
   npm start
   ```

5. Start the frontend development server:
   ```
   cd frontend
   npm start
   ```

6. Open your browser and navigate to `http://localhost:3000` to view the application.

