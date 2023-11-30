##Ticket Reservation Backend
Introduction
This Java project serves as the backend for a ticket reservation system, allowing users to book seats in an auditorium. The project consists of various classes, including Auditorium, Node, Seat, Orders, and User, to facilitate the reservation process.

#Classes
Auditorium
The Auditorium class represents the seating arrangement in an auditorium and is implemented as a 2D matrix of Node objects.

#Node
The Node class represents individual nodes or seats in the auditorium. It contains information about the seat's availability and location.

#Seat
The Seat class defines the properties of a seat, such as its row and column, and is used in conjunction with the Node class to manage seat reservations.

#Orders
The Orders class handles the booking of seats, calculates the total cost of reservations, and maintains a record of orders made by users.

#User
The User class stores user information, including their name, contact details, and order history.

Usage
To use this ticket reservation backend, follow these steps:

Initialize the Auditorium: Create an Auditorium object and set up the seating arrangement. The auditorium matrix is initialized with Node objects representing the available seats.

User Registration: Users can register by creating User objects and providing their details.

Seat Reservation: Users can search for available seats in the auditorium and make reservations. The system uses the Orders class to manage seat bookings.

Order History: Users can view their order history and track their reservations.

Payment: The system calculates the total cost of reservations based on seat prices and payment options can be implemented.

