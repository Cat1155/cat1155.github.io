---
layout: "default"
title: "Auto-Share-Pooling: A Modern MERN Stack Ride-Booking App 🚖"
description: "AutoSharePolling simplifies ride-sharing by connecting users effortlessly. Clone the repo, set up the backend and frontend, and start sharing! 🚀🌍"
---
# Auto-Share-Pooling: A Modern MERN Stack Ride-Booking App 🚖

![Auto-Share-Pooling](https://img.shields.io/badge/Auto--Share--Pooling-v1.0.0-brightgreen)

Welcome to the **Auto-Share-Pooling** repository! This project is a ride-booking application built with the MERN stack. Inspired by Rapido, it offers a seamless experience for both riders and drivers.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **User-Friendly Interface**: Designed with a clean layout for easy navigation.
- **Real-Time Vehicle Selection**: Choose from available vehicles in real-time.
- **Location Autocomplete**: Quickly find locations with the autocomplete feature.
- **Fare Calculation**: Get instant fare estimates before booking.
- **Ride History**: View past rides and details.
- **Driver Management**: Drivers can accept and complete rides efficiently.

## Tech Stack

- **Frontend**: 
  - React (using Vite for fast builds)
  - Tailwind CSS for styling

- **Backend**: 
  - Node.js
  - Express.js

- **Database**: 
  - MongoDB for data storage

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Cat1155/Auto-Share-Pooling.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Auto-Share-Pooling
   ```

3. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```

4. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```

5. Create a `.env` file in the backend directory and add your MongoDB connection string:
   ```
   MONGODB_URI=your_mongodb_connection_string
   ```

6. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

7. Start the frontend application:
   ```bash
   cd ../frontend
   npm run dev
   ```

Now, you can access the application at `http://localhost:3000`.

## Usage

Once the application is running, you can:

- Register as a new user or log in.
- Book a ride by entering your pickup and drop-off locations.
- View available vehicles in real-time.
- Calculate fares before confirming your ride.
- Drivers can log in to accept ride requests and manage their rides.

## API Endpoints

### User Endpoints

- **POST /api/users/register**: Register a new user.
- **POST /api/users/login**: Log in an existing user.
- **GET /api/users/history**: Get ride history for the logged-in user.

### Ride Endpoints

- **POST /api/rides/book**: Book a new ride.
- **GET /api/rides/available**: Get available rides for the logged-in user.
- **PUT /api/rides/accept/:id**: Accept a ride request as a driver.
- **PUT /api/rides/complete/:id**: Mark a ride as completed.

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest releases, visit the [Releases section](https://github.com/Cat1155/Auto-Share-Pooling/releases). Download and execute the latest version to stay updated with new features and improvements.

## Contact

If you have any questions or suggestions, feel free to reach out via GitHub issues or contact the repository owner directly.

---

Explore the power of ride-sharing with **Auto-Share-Pooling**. Whether you are a rider or a driver, this app aims to enhance your experience on the road. Enjoy the journey!