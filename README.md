# bookMyShow
![Screenshot (100)](https://github.com/user-attachments/assets/b47ede3b-0537-4f25-9c4c-f8c7d200b157)


Overview

This project is a movie booking application built using the MERN stack (MongoDB, Express.js, React, Node.js). It enables users to easily browse available movies, select showtimes, choose seats, and complete bookings. Additionally, users can view their booking history to keep track of past reservations.

Features

Movie Selection: Allows users to browse and select movies from a list of available options.

Time Slot & Seat Selection: Provides flexibility to choose preferred showtimes and seats.

Streamlined Booking Process: Users can book their chosen movie and seat quickly with minimal steps.

Booking History: Displays a record of previous bookings for easy reference.


Tech Stack

Frontend: React with Context API and local storage for state management.

Backend: Node.js and Express.js for server-side operations and API handling.

Database: MongoDB for data storage, ensuring that booking information and seat availability are well managed.


Setup and Installation

1. Clone the Repository:

git clone https://github.com/yourusername/movie-booking-app.git
cd movie-booking-app


2. Install Backend Dependencies:

cd back-end
npm install


3. Install Frontend Dependencies:

cd ../front-end
npm install


4. Set Up Environment Variables:

Create a .env file in the backend directory and add the following:

MONGO_URI=your_mongodb_connection_string
PORT=8080



5. Run the Application:

Backend:

cd backend
npm start

Frontend:

cd ../frontend
npm start



6. Open in Browser:

The frontend should be running on http://localhost:3000

The backend should be running on http://localhost:8080




Usage

1. Browse Movies: Select a movie from the available list.


2. Choose Showtimes and Seats: Pick your preferred time slot and seats.


3. Book Your Ticket: Confirm your selection to book.


4. View Booking History: Access a record of your previous bookings.
