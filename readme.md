# Movie Ticket Booking System

## Overview

The **Movie Ticket Booking System** is a simple, menu-driven Python application designed for managing basic cinema ticket operations in a console environment. It allows users to view available movies, check showtimes, select seats/tickets with cost calculation, confirm their bookings, and review their active reservations during the session.

## Features

* **Browse Movies:** View a catalog of available movies along with their respective ticket prices.

* **View Show Timings:** Check available daily screening slots.

* **Book Tickets:**

  * Select movies and preferred screening times.

  * Specify the required number of tickets.

  * View real-time cost calculation (in Rs.).

  * Confirmation prompt before finalizing reservations.

* **My Bookings:** View a summary of all booked tickets within the current session.

* **Input Validation:** Error handling for numeric selections and invalid inputs.

## Technologies/Tools Used

* **Language:** Python 3.x

* **Development Environment / Tools:** Any Standard Python IDE (VS Code, PyCharm, IDLE) or Command Line / Terminal.

## Steps to Install & Run the Project

### Prerequisites

Make sure you have **Python 3.x** installed on your system.

### Running the Application

1. **Clone or Download the Repository:**
   Save the Python script as `main.py` (or `movie_booking.py`).

2. **Open Terminal / Command Prompt:**
   Navigate to the directory where the file is located:

   ```
   cd path/to/your/folder 
   
   ```

3. **Run the Script:**
   Execute the program using the following command:

   ```
   python main.py
   
   ```

## Instructions for Testing

Follow these manual testing steps to verify all functionality works correctly:

1. **User Welcome & Main Menu:**

   * Run the script and enter your name when prompted. Verify the main menu displays options `1` through `5`.

2. **Test Option 1 (View Movies):**

   * Enter `1`. Verify the list of movies along with prices is displayed.

3. **Test Option 2 (View Timings):**

   * Enter `2`. Verify all available show times are displayed.

4. **Test Option 3 (Book Ticket - Success Path):**

   * Enter `3`. Select a valid movie choice (e.g., `1`), a valid showtime (e.g., `2`), and a valid ticket count (e.g., `2`).

   * Confirm the booking by typing `yes`. Check that the success message appears.

5. **Test Option 3 (Invalid Inputs & Cancellation):**

   * Select an invalid movie/time choice (e.g., `99`) to ensure appropriate error messages appear.

   * Test entering negative or non-integer ticket counts to ensure validation triggers.

   * Go through the booking flow and type `no` at confirmation to test cancellation.

6. **Test Option 4 (My Bookings):**

   * Select `4` to view all successfully confirmed bookings. Verify total amounts match expected calculations.

7. **Test Option 5 (Exit):**

   * Select `5` to ensure the program displays the exit greeting with your name and terminates gracefully.

## Screenshots

```
========================================
       Movie Ticket Booking System
========================================
Enter your name: Alex

1. Movies
2. Show Timings
3. Book Ticket
4. My Bookings
5. Exit
Enter your choice: 1

Movies:
1. Avengers Endgame - Rs. 200
2. Spider Man No Way Home - Rs. 180
3. Interstellar - Rs. 220
4. Inception - Rs. 200
========================================

```