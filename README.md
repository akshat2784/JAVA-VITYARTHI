# Hotel Management System

A simple Java-based Hotel Management System that allows hotel staff to manage room bookings, check-ins, and check-outs efficiently.

## Features

- **Check-in**: Assign guests to available rooms
- **Check-out**: Process guest departures and free up rooms
- **View Available Rooms**: Display all unoccupied rooms
- **Room Management**: Track room occupancy status and guest information

## Classes Overview

### Hotel Class
- Manages the collection of rooms
- Provides methods for check-in, check-out, and displaying available rooms
- Handles room search functionality

### Room Class
- Represents individual hotel rooms
- Stores room number, guest name, and occupancy status
- Provides getter and setter methods for room properties

### HotelManagementSystem Class
- Contains the main method and program entry point
- Provides a user-friendly menu interface
- Initializes the hotel with predefined rooms

## Room Configuration

The system is pre-configured with the following rooms:
- 101, 102, 103 (First Floor)
- 201, 202, 203 (Second Floor)

## How to Use

1. **Compile the Program**:
   ```bash
   javac HotelManagementSystem.java
   ```

2. **Run the Program**:
   ```bash
   java HotelManagementSystem
   ```

3. **Menu Options**:
   - **Option 1**: Check-in a guest
     - Enter room number
     - Enter guest name
   - **Option 2**: Check-out a guest
     - Enter room number to vacate
   - **Option 3**: View all available rooms
   - **Option 4**: Exit the system

## Example Usage

```
--- Hotel Management System by DataFlair ---
1. Check-in
2. Check-out
3. View available rooms
4. Exit
Enter your choice: 1
Enter room number: 101
Enter guest name: John
Guest John checked into room 101.

--- Hotel Management System by DataFlair ---
1. Check-in
2. Check-out
3. View available rooms
4. Exit
Enter your choice: 3
Available Rooms:
Room 102: Available
Room 103: Available
Room 201: Available
Room 202: Available
Room 203: Available
```

## Error Handling

- Prevents check-in to occupied rooms
- Validates room existence
- Prevents check-out from unoccupied rooms
- Handles invalid menu choices

## Technical Details

- **Language**: Java
- **Data Structures**: Arrays for room management
- **Input Handling**: Scanner class for user input
- **Object-Oriented**: Uses encapsulation with private fields and public methods

## Future Enhancements

Potential improvements for this system:
- Add room types (Single, Double, Suite)
- Implement pricing and billing
- Add persistent storage (file/database)
- Include guest contact information
- Add room cleaning status tracking
- Implement admin authentication

This project demonstrates fundamental Java programming concepts including classes, objects, arrays, loops, and conditional statements in a practical hotel management context.

## Project Structure

```
HotelManagementSystem/
├── src/
│   └── HotelManagementSystem.java
├── README.md
└── .gitignore
```

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hotel-management-system.git
   cd hotel-management-system
   ```

2. Compile the Java files:
   ```bash
   javac src/HotelManagementSystem.java
   ```

3. Run the application:
   ```bash
   java -cp src HotelManagementSystem
   ```

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Developed as a learning project for Java programming fundamentals.

