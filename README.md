# Airline-Reservation-SQL-Live-Project

A beginner-friendly, one-file MySQL 8 schema for an Airline Reservation System:
- Core tables (airports, aircrafts, seats, flights, instances, customers, passengers, bookings, tickets, payments)
- Triggers to maintain totals & booking status
- Views for availability and booking summaries
- Procedures for seat seeding, flight search, and seat assignment
- Sample data and demo queries

## Requirements
- MySQL 8.0+
- A MySQL user with permissions to create databases

## Quick Start

```bash
# 1) Clone and run the SQL
git clone https://github.com/ShaikhKhalil/Airline-Reservation-SQL-Live-Project.git
cd Airline-Reservation-SQL-Live-Project

# Run the script
mysql -u <user> -p < sql/airline_reservation.sql
