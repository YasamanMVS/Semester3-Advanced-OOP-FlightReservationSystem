# Flight Reservation System

## Description:
The Flight Reservation System is a comprehensive software solution designed for managing airline bookings. This system allows for the management of customer profiles, flight information, and booking records. It supports operations such as adding and removing flights, customers, and managing bookings through a user-friendly console interface.

## Features:
- **Customer Management**: Add, view, and delete customer profiles.
- **Flight Management**: Add, view, delete, and view details of flights.
- **Booking Management**: Create bookings and view all bookings with detailed information.

## Project Structure:
- **`Booking.cs`**: Defines the Booking class with details like customer, flight, booking ID, and date.
- **`BookingManager.cs`**: Manages all bookings and supports operations like creating and viewing bookings.
- **`Customer.cs`**: Represents a customer with attributes like ID, name, phone number, and email.
- **`CustomerManager.cs`**: Manages customers, supporting operations like adding, finding, and removing customers.
- **`Flight.cs`**: Represents a flight with details such as flight number, destination, origin, and seats.
- **`FlightManager.cs`**: Manages flights and supports operations like adding, viewing, and removing flights.
- **`Program.cs`**: Contains the main entry point of the application, handling the user interface for interacting with the system.

## Installation and Setup:
1. **Prerequisites**: Ensure you have .NET 5.0 SDK installed on your system.
2. **Clone the repository**: Download the project files from the repository to your local machine.
3. **Open the project**: Open the `gpFlightReservation.sln` file in Visual Studio.
4. **Build the project**: Compile the project using Visual Studio to make sure all dependencies are correctly set up.
5. **Run the application**: Start the application through Visual Studio to access the functionality via the console interface.

## How to Use:
Navigate through the console menu to access different functionalities:

- Select `1` for customer operations.
- Select `2` for flight operations.
- Select `3` for booking operations.
Each section has its submenu to perform specific tasks like adding, viewing, or deleting records.
