## Hotel Reservation - JAVA
This app allows users to book reservations and allows the admin to track and manage the database.

# Prerequisite
* IntelliJ
* JDK 17


# User Scenarios
1. Creating a customer account: Name, Phone, Email
2. Searching for rooms: output available rooms based on checkin and checkout data.
3. Booking a room 
4. View reservations

# Admin Scenarios
1. Displaying all customers accounts
2. Viewing all of the rooms in the hotel
3. Viewing all of the hotel reservations
4. Maintaining the system 

# Error Handle
* RegEx is used to check the input email format (name@domain.com)
* No crashing: validate all user input
* No unhandled exceptions: used try catch blocks