# Car Workshop Service Booking System

## Project Overview
This project is a **Car Workshop Service Booking System** designed to digitalize
vehicle service management processes in a workshop environment. The system
supports customer data management, vehicle records, service booking,
technician assignment, and payment processing through an integrated database
system.

This project was developed as a **group final project** for the Database course.

---

## Key Features
- Customer, vehicle, and service booking management
- Role-based access (Admin & Customer)
- Automated service workflow using database triggers
- Service scheduling and booking history
- Interactive service reports

---

## System Architecture
- Backend implementation using **Java (DAO Pattern)**
- Centralized database connection (MySQL)
- Business logic supported by SQL Views, Triggers, and Stored Procedures

---

## Database Implementation
### Tables
- users
- pelanggan
- mobil
- teknisi
- booking_servis
- jenis_servis
- detail_servis
- transaksi_servis

### SQL Components
- **Triggers** for automatic technician status updates and booking completion
- **Views** for monitoring active service bookings
- **Stored Procedures** for service time estimation

---

## How to Run the Program
1. Compile the program:
   ```bash
   javac -cp ".:mysql-connector-java-8.0.xx.jar" Main.java
