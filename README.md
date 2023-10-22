# Travel Management System (TMS) - C++ Project

Welcome to the Travel Management System (TMS) project based on Object-Oriented Programming (OOP) concepts. This system allows customers to book cabs and hotels of their choice. It is implemented in C++ and consists of various classes that handle different aspects of the travel management process.

## Project Overview

The TMS project includes the following features:

1. **Customer Management**: Allows customers to enter their details, such as name, age, contact, address, and gender. The system assigns a unique customer ID to each customer and stores this information for future reference.

2. **Cab Management**: Provides options to rent a standard or luxury cab for a given number of kilometers. The system calculates and displays the cost of the selected cab based on the distance traveled.

3. **Hotel Booking**: Enables customers to book a hotel from a list of available hotels, such as Avendra, EnlightInn, and GreenDesert. The hotels offer various packages, including standard, premium, and luxury. Customers can choose their preferred hotel and package.

4. **Charges Management**: Calculates and generates a receipt for the customer, including the total cost of the hotel and cab services. The receipt is saved to a file for reference.

## How to Use

1. **Customer Management**: 
   - Choose option 1 from the main menu to enter new customer details.
   - Select option 2 to view details of previous customers.

2. **Cab Management**:
   - Choose option 2 from the main menu.
   - Select either a standard or luxury cab.
   - Input the number of kilometers to calculate the cost.
   - Confirm the cab booking.

3. **Hotel Booking**:
   - Choose option 3 from the main menu.
   - Select a hotel from the list of available options.
   - Choose a package (standard, premium, or luxury).
   - Confirm the hotel booking.

4. **Charges Management**:
   - Choose option 4 from the main menu to generate a receipt.
   - The system will calculate the total cost of the hotel and cab services.
   - The receipt will be saved to a file and displayed on the screen.

## Implementation Details

The project is implemented using C++ and organized into several classes, including `Customers`, `Cabs`, `Booking`, and `Charges`. These classes are used to manage different aspects of the travel management process. The main menu and user interaction are handled by the `menu` function.

## System Requirements
- Visual Studio Code .
- A C++ compiler (e.g., g++) to compile and run the project.

## Getting Started

1. Clone or download the project from this GitHub repository.
2. Compile the C++ source code using your preferred C++ compiler.
3. Run the executable to start the Travel Management System.

## Feedback and Contributions

Feel free to provide feedback or contribute to the project by opening issues or creating pull requests on this GitHub repository.

**Note:** This project is designed for educational purposes and can be used as a starting point for building more advanced travel management systems. Enjoy exploring and learning from this codebase!
