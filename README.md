🚗 Car Rental System
Welcome to the Car Rental System! This Java application allows users to rent and return cars seamlessly. Below is an overview of the project's structure and functionality.

📋 Features

Add Cars: Add cars to the rental system with details like ID, brand, model, and base price per day.
Add Customers: Register new customers in the system.
Rent Cars: Rent a car for a specified number of days if available.
Return Cars: Return a rented car to make it available again.
Rental Summary: Display rental information including customer details and total price.

🛠️ Usage
Running the Application:

Execute the Main class to start the car rental system.
Menu Options:

1. Rent a Car:
Enter your name.
Choose an available car by its ID.
Specify the number of rental days.
Confirm the rental to proceed.

3. Return a Car:
Enter the car ID to return.

5. Exit:
Exit the system.

📂 Classes
Car: Represents a car with properties like ID, brand, model, base price per day, and availability.

Customer: Represents a customer with properties like ID and name.

Rental: Represents a rental transaction with properties like car, customer, and rental days.

CarRentalSystem: Manages the cars, customers, and rentals. Contains methods to add cars and customers, rent and return cars, and display the menu.

🚀 Getting Started
Setup: Ensure you have Java installed.
Compile: Compile the Java files.
Run: Execute the Main class to start the system.

// compile
javac Main.java
java Main

💻 Example
// Create the car rental system
CarRentalSystem rentalSystem = new CarRentalSystem();

// Add cars
rentalSystem.addCar(new Car("C001", "Toyota", "Camry", 60.0));
rentalSystem.addCar(new Car("C002", "Honda", "Accord", 70.0));
rentalSystem.addCar(new Car("C003", "Mahindra", "Thar", 150.0));

// Start the menu
rentalSystem.menu();


📞 Support
For any issues or queries, please open an issue on this repository or contact the maintainers.

Enjoy your car rental experience! 🚙✨
