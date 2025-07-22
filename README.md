This project was built using only core Java without any external frameworks or databases. Here's a breakdown of the methods and logic I implemented:

🧑‍💼 Customer Management
addCustomer() – To add a new customer with their name, ID proof, contact number, etc.

viewCustomers() – Displays all registered customers in a formatted manner.

🛏️ Room Booking System
bookRoom() – Books a room for the customer based on their preferences and availability.

checkAvailability() – Checks if rooms are available before booking.

cancelBooking() – Cancels an existing room booking and updates status.

💰 Billing & Duration
generateBill() – Calculates the total amount based on number of days stayed and room charges.

calculateStayDuration() – Computes total stay days between check-in and check-out.

📄 File Handling (if used)
saveToFile() – (Optional) Saves booking data to a file for future use.

readFromFile() – (Optional) Loads data from file when the app is restarted.

🖥️ User Interaction
displayMenu() – Provides a menu-driven interface to navigate between options.

handleUserInput() – Takes input using Scanner and handles wrong entries safely.

🔁 Control Flow
Used loops, conditionals, and switch-case statements to manage the menu and program flow efficiently.

Made use of Arrays/ArrayList to store customer and room data in memory.
