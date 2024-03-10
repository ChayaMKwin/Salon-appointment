# Salon Appointment Scheduler

This repository contains the PostgreSQL database dump and a Bash script for managing salon appointments. The system allows customers to book appointments for various services offered by the salon.

## Files Included

- PostgreSQL Database Dump: A dump of the PostgreSQL database structure used to store appointment, customer, and service information.
- Bash Script (`schedule_appointment.sh`): A command-line script to interact with the database for booking appointments.

## Database Structure

The database consists of three main tables:

- `appointments`: Stores the appointment details.
- `customers`: Stores customer information.
- `services`: Stores the services offered by the salon.

Each table is designed with a primary key and sequences for auto-incrementing ID values. The database is owned by the user `freecodecamp`.

## Getting Started

### Prerequisites

- PostgreSQL (The dump was created with version 12.9)
- Bash environment (Linux/Unix or WSL on Windows)
- The PostgreSQL command line tools installed and accessible in your PATH
