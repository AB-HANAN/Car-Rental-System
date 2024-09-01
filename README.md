# Car Rental System in Python

## Overview

This Python script is a simple text-based Car Rental System that allows users to rent cars, return cars, and view the total cost of their rentals. The program manages three different car models (KIA, Camry, and Pajero), tracks their availability, calculates rental costs, insurance options, and includes tax in the total payment.

## Features

- **Car Rental**: Allows the user to select a car model, choose the number of rental days, and opt for either liability or full insurance. The system calculates the total cost, including a 5% tax on the rental price.
  
- **Car Return**: Users can return a previously rented car, which updates the availability of that car model.

- **Total Payout**: Users can view the overall rental cost, tax, insurance cost, and the grand total of their rentals.

## Program Flow

1. **Main Menu**:
   - Option 1: Car Rental
   - Option 2: Car Return
   - Option 3: Print the total payout
   
2. **Car Rental**:
   - The user selects a car model from the available options.
   - The user enters the number of days they wish to rent the car.
   - The user selects the type of insurance (Liability or Full).
   - The system calculates and displays the rental cost, insurance cost, tax, and the grand total.

3. **Car Return**:
   - The user selects the car they wish to return.
   - The system updates the availability of the car.

4. **Total Payout**:
   - The user can view the total rental cost, insurance cost, tax, and the grand total.

## Variables and Functions

### Global Variables

- `starting_tax1`: Initial tax value.
- `starting_insurance_cost`: Initial insurance cost.
- `starting_total_rental_cost`: Initial total rental cost.

- `kia`, `camery`, `pajaero`: Variables to track the availability of each car model.
- `rental_cost_1`, `inc_cost_1`, `price1`, `tax`, `li_1`, `fi_1`: Variables to store the rental cost, insurance cost, and other related values for the KIA.
- `price2`, `li_2`, `fi_2`: Variables for the Camery.
- `price3`, `li_3`, `fi_3`: Variables for the Pajaero.
- `grand_total`: The final calculated total of the rental, including tax and insurance.

### Functions

- **`car_rental()`**: Handles the car rental process, including the selection of the car, rental days, and insurance type. It calculates and displays the total cost.
  
- **`car_return()`**: Handles the car return process, updating the availability of the cars.

- **`total_payout()`**: Displays the overall rental cost, tax, insurance cost, and grand total.

- **`entry()`**: Displays the main menu and directs the user to the selected function (rental, return, or payout).

## How to Run

1. Ensure you have Python installed on your system.
2. Save the script to a `.py` file (e.g., `car_rental_system.py`).
3. Run the script using a Python interpreter (e.g., `python car_rental_system.py`).
4. Follow the on-screen instructions to interact with the car rental system.

## Future Enhancements

- **Persistent Data Storage**: Currently, the car data (availability, rental costs, etc.) resets each time the program runs. Implementing persistent storage (e.g., using a database or file) would allow the program to retain information between sessions.
- **User Authentication**: Adding a user login system could personalize the experience and track rentals for individual users.
- **Enhanced UI**: Developing a graphical user interface (GUI) would improve the user experience.

## License

This project is open-source and free to use under the MIT License.

---

Feel free to modify this README as per your project requirements!
