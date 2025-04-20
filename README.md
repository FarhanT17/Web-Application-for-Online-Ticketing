🎟️ OnlineTicketBooking
Online Movie Ticket Booking with Java Spring Boot
This project is an application that simulates the activity of booking movie tickets based on available schedules and ticket quotas. The application is built using Java with the Spring Boot framework. For the user interface, it uses Thymeleaf, HTML, and CSS.

🔒 Application Limitations:
The system supports only one cinema

Customer data is pre-registered

Ticket data and quotas are predefined

The app only supports ticket ordering, payment processing is out of scope

The app focuses on user-side activity only

🧩 Features and Flow:
Users log in with their email and password

If login is successful, the app shows a form to book tickets; if not, an error message is displayed

After login, the user's details are automatically loaded

Users select a movie schedule from a dropdown

The system shows only schedules with upcoming showtimes (past dates are filtered out)

Users enter the number of tickets to book

On successful booking:

A receipt with the booking details is displayed

Ticket quota is automatically updated

If the booking fails due to:

Trying to book for a showtime that’s already passed: an error message is shown

Exceeding the ticket quota: an error message is shown

A sample SQL file CreateTable.sql and insert query file are provided for setting up the database

Note: The default password for login is 123456
