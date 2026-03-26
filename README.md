# 🚆 Railway Reservation System

A console-based Railway Reservation System built in Java that allows users to view available trains, check seat availability, book tickets, and cancel reservations.

---

## 📁 Project Structure
```
cogni/
└── Reservation.java        # Main entry point
```

---

## ✨ Features

- View all available trains with details
- Check seat availability for a specific train
- Book a ticket by train number and passenger name
- Cancel an existing ticket
- Display all booked tickets

---

## 🚂 Available Trains (Pre-loaded)

| Train Name           | Departure Time | Seats | Train Number |
|----------------------|----------------|-------|--------------|
| Mumbai - Delhi       | 13:05          | 50    | 1010         |
| Delhi - Jaipur       | 07:00          | 50    | 2013         |
| Prayagraj - Delhi    | 10:00          | 50    | 3045         |

---

## ▶️ How to Run

### Prerequisites
- Java JDK 8 or above installed
- A terminal / command prompt

### Steps
```bash
# 1. Navigate to the project directory
cd cogni

# 2. Compile the Java files
javac Reservation.java

# 3. Run the program
java cogni.Reservation
```

---

## 🖥️ Menu Options
```
Railway Reservation System Menu:
1. Display Available Trains
2. Check Seat Availability
3. Book a Ticket
4. Cancel a Ticket
5. Display Booked Tickets
6. Exit
```

---

## 📌 Usage Example
```
Enter your choice: 3
Enter Train Number: 1010
Enter Passenger Name: John Doe
Ticket booked successfully for John Doe

Enter your choice: 4
Enter Passenger Name to Cancel: John Doe
Ticket canceled successfully for John Doe
```

---

## ⚠️ Limitations

- Data is **not persisted** — all bookings are lost when the program exits
- Seat availability check counts total bookings across all trains (not per train)
- Duplicate passenger names may cause unintended cancellations

---

## 🛠️ Built With

- **Language:** Java
- **Package:** `cogni`
- **Data Structures:** `ArrayList`

---

## 📄 License

This project is open source and available for educational purposes.
