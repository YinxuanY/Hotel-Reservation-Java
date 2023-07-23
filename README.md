## Hotel Reservation - JAVA
This app allows users to book reservations and allows the admin to track and manage the database.

# Prerequisite
* IntelliJ
* JDK 17

* Sample 

<img width="473" alt="Screenshot 2023-07-22 at 10 19 51 PM" src="https://github.com/YinxuanYin/Hotel-Reservation/assets/97659868/ebe2e9f0-7678-4955-83c7-8099afeda96c">
<img width="459" alt="Screenshot 2023-07-22 at 10 20 31 PM" src="https://github.com/YinxuanYin/Hotel-Reservation/assets/97659868/0070bd8c-fcbe-4505-8ae2-f7c536cd3278">
[Video](https://github.com/YinxuanYin/Hotel-Reservation/assets/97659868/130bb0ac-58ba-41ce-b569-310ea60053b9)

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