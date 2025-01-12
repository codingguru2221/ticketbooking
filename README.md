# Ticket Booking System

## Overview
The Ticket Booking System is a console-based application developed in C++ that allows users to create accounts, log in, and book tickets for trains, buses, and planes. The system manages user data and booking information through file handling, providing a simple yet effective way to manage travel reservations.

## Features
- **User Account Management**: 
  - Create a new account with a username, password, and personal information.
  - Log in to your account to access booking features.
  - Reset forgotten passwords using personal information.

- **Ticket Booking**:
  - Book tickets for various modes of transportation: trains, buses, and planes.
  - View available options with details such as routes, timings, and prices.
  - Select seat types (e.g., sleeper, non-sleeper, AC) during the booking process.

- **Data Storage**:
  - User credentials and booking information are stored in text files (`store.txt` for user data and `gstore.txt` for seat numbers).
  - The application handles file operations for reading and writing data.

- **Input Validation**:
  - Validates user inputs, ensuring mobile numbers are 10 digits and dates are correctly formatted.

## Technologies Used
- **Programming Language**: C++
- **File Handling**: Standard file I/O operations for data storage and retrieval.

## Getting Started
To run the Ticket Booking System, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ticket-booking-system.git
   cd ticket-booking-system
   ```

2. **Compile the Code**:
   Use a C++ compiler to compile the `main.cpp` file.
   ```bash
   g++ main.cpp -o ticket_booking_system
   ```

3. **Run the Application**:
   Execute the compiled program.
   ```bash
   ./ticket_booking_system
   ```

## Usage
- Upon running the application, users will be prompted to select an option: create an account, log in, or reset a password.
- After logging in, users can choose to book tickets for trains, buses, or planes.
- Follow the on-screen instructions to complete the booking process.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please create a pull request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by various ticket booking systems and user management applications.
- Thanks to the open-source community for their resources and support.
