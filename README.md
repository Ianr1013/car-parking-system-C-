# Car Parking Reservation System

A simple console-based Car Parking Reservation System implemented in C++. This system allows users to manage car parking, calculate charges, and keep track of parking records.

## Features
- **Car Arrival:** Add details of arriving cars, including driver name, car number, hours of stay, and time slot.
- **View Records:** Display details of all cars currently parked.
- **Parking Charges:** Calculate parking charges based on the hours of stay and VIP status.
- **Car Departure:** Remove records of cars that depart from the parking lot.
- **Secure Access:** Login functionality to ensure only authorized users can access the system.

## Requirements
- C++ Compiler
- Windows OS (uses `conio.h` for console input and output)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-parking-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-parking-system
   ```
3. Compile the program using a C++ compiler, such as `g++`:
   ```bash
   g++ car_parking.cpp -o car_parking
   ```

## Usage
1. Run the program:
   ```bash
   ./car_parking
   ```
2. Enter the login password (default is `pass`).
3. Use the menu to navigate the features:
   - **Option 1:** Register the arrival of a car.
   - **Option 2:** View all parked cars.
   - **Option 3:** Calculate and view parking charges for all cars.
   - **Option 4:** Mark a car's departure and delete its record.
   - **Option 5:** Exit the program.

## Code Overview
### Classes
- **`car`:** Contains attributes such as driver name, car number, hours of stay, and time slot. Includes methods to:
  - Input car details.
  - Calculate parking charges.
  - Display car details.

### Key Functions
- **`login()`:** Handles secure login with password validation.
- **`delete_record()`:** Deletes a car's record upon departure.
- **`main()`:** Implements the menu-driven user interface.

## Sample Output
```
		 ====== CAR PARKING RESERVATION SYSTEM ======
		  1. Arrival of a Car
		  2. Total no of cars Arrived
		  3. Total parking charges of all cars with details
		  4. Departure of the car
		  5. Exit Program
		 Select Your Choice:
```

## Contributing
Feel free to fork this repository and contribute to improving the project. Submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Original project idea from [code-projects.org](https://code-projects.org).

---
Happy Parking! 🚗
