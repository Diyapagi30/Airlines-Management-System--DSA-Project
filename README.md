# ✈️ Travel Management System

A simple **C++ console-based project** that simulates a Travel Management System allowing users to register, login, and book flights between major Indian cities. The system uses the **Bellman-Ford algorithm** to find the cheapest route between two cities, even if no direct flight is available.

---

## 🚀 Features

- ✅ User Registration and Login System (with file handling)
- ✅ Display available cities
- ✅ Book tickets for multiple passengers
- ✅ Choose between direct or cheaper connecting flights
- ✅ Generates E-Tickets with passenger details
- ✅ Uses Bellman-Ford Algorithm for finding cheapest travel path
- ✅ Saves ticket info to file for persistence

---

## 📌 Cities Covered

- Delhi
- Mumbai
- Chennai
- Kolkata
- Kerala
- Hyderabad
- Pune
- Goa
- Bangalore
- Amritsar
- Jaipur
- Patna
- Puducherry
- Srinagar
- Bhopal

---

## 🛠️ How It Works

### 1. User Authentication
- Create an account or log in using a username and password.
- Data is saved in a file `login.txt`.

### 2. Booking Flights
- Choose source and destination cities.
- System checks for direct flight or computes minimum cost via other cities.
- Uses Bellman-Ford algorithm to update cost matrix.

### 3. Passenger Info & E-Ticket
- Enter passenger details.
- Confirm booking and receive an E-Ticket.
- Info saved to `ticket.txt`.

---

## 💻 Technologies Used

- Language: C++
- Algorithm: Bellman-Ford
- File Handling: `fstream`
- Data Structures: Arrays, Structs, Classes

---

## 📂 File Structure

```plaintext
.
├── travel_management.cpp   # Main program file
├── login.txt               # Stores usernames and passwords (auto-created)
├── ticket.txt              # Stores ticket booking details (auto-created)
└── README.md               # Project documentation
