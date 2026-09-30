# Project Statement

## Problem Statement

Traditional cinema booking processes often rely on manual handling or complex graphical applications that require significant resources. There is a need for a lightweight, straightforward command-line application that allows customers to browse available movies, check showtimes, select ticket quantities with automated price calculation, and maintain a summary of booked tickets during a session without unnecessary complexity.

## Scope of the Project

The scope of the **Movie Ticket Booking System** covers standard user interactions within an interactive Command Line Interface (CLI):

* **In-Scope:**
  * Displaying a static catalog of movies with assigned prices.
  * Showing fixed showtime schedules.
  * Session-based ticket booking workflow (selecting movie, time, and ticket quantity).
  * Real-time total price calculation.
  * Confirmation/cancellation mechanism prior to saving a booking.
  * Viewing active reservations within the current terminal session.
  * Basic input validation to handle non-numeric or invalid numerical selections gracefully.

* **Out-of-Scope:**
  * Persistent database storage (data resets when the application closes).
  * Seat map grid selection (e.g., A1, A2).
  * Online payment gateway integration.
  * User authentication or multi-user account management.

## Target Users

* **Cinema Customers:** Individuals who want a fast, simple text-based interface to view showtimes and mock-book tickets.
* **Students & Beginners:** Developers looking for a clean, foundational reference project demonstrating Python data structures (dictionaries and lists), basic control flow, functions, and standard input handling.

## High-Level Features

1. **User Personalization:** Captures user name upon launch for a customized greeting and exit message.
2. **Catalog Browsing:** Displays current movies and corresponding ticket rates dynamically from structured data.
3. **Showtime Browsing:** Lists available daily screening slots.
4. **Interactive Booking Workflow:** Step-by-step guidance to choose a movie, pick a time slot, specify ticket quantities, review total charges, and confirm or cancel the booking.
5. **Session Reservation History:** Maintains an in-memory list of all successful bookings made during the run, allowing users to view a summary at any time.
6. **Robust Input Handling:** Catches type conversion errors (e.g., entering text instead of numbers) to prevent system crashes.