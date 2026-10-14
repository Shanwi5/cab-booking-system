# Cab Booking System

A full-stack web application that allows customers to book cabs, drivers to manage rides, and administrators to manage users and cabs.

## Features

- User registration and login
- Role-based access for customers, drivers, and admins
- Cab booking and cancellation
- Automatic distance and fare calculation
- Cab availability management
- Booking history
- Driver dashboard to accept, start, and complete rides
- Admin dashboard to manage users and cabs
- JWT-based authentication

## Tech Stack

**Frontend:** React, Vite  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** JSON Web Tokens (JWT)

## Project Structure

```text
cab-booking-system/
├── client/          # React frontend
├── server/          # Node.js backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── middleware/
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd cab-booking-system
```

### 2. Set up the backend

```bash
cd server
npm install
```

Create a `.env` file in the server directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5173
```

Start the backend:

```bash
npm run dev
```

### 3. Set up the frontend

Open a new terminal:

```bash
cd client
npm install
npm run dev
```

Open the local URL displayed by Vite, usually `http://localhost:5173`.

## API Modules

| Module | Functionality |
|---|---|
| Authentication | Registration, login, user profile |
| Cabs | View, create, update, and manage cabs |
| Bookings | Create, view, cancel, and update rides |
| Users | Admin user management and role updates |

## User Roles

- **Customer:** Book cabs, view booking history, and cancel bookings.
- **Driver:** Manage cab availability and update ride status.
- **Admin:** Manage users, roles, and cabs.

## Future Enhancements

- Online payment integration
- Live GPS tracking
- Email and SMS notifications
- Ride ratings and reviews

## Author

**Shanwi B M**

GitHub: Add your GitHub profile link  
LinkedIn: Add your LinkedIn profile link
