# 🚌 Bus Booking System

A complete **Bus Booking Management System** built using **C# Windows Forms (.NET)** and **SQLite**.  
The system simulates a real-world bus reservation platform with seat selection and booking management.

## 👨‍💻 Author

**ANAS A A KHAMAYSA**  **2210213581**
**ABDALHAMID ALBEIK**  **2210213579**
**ABDALJAWWAD M.A. TARADEH**  **2210213586**
Computer Engineering Student  
Interests: Cybersecurity & Information Security

---

## 📌 Project Overview

The Bus Booking System allows admins and users to manage buses, expeditions, and seat reservations in an organized and user-friendly way.

---

## 🛠️ Technologies Used

- C# (.NET Windows Forms)
- SQLite Database
- ADO.NET
- DataGridView
- Charts (System.Windows.Forms.DataVisualization)

---

## 📂 Database Tables

- Users  
- Admins  
- Buses  
- Drivers  
- Cities  
- Expeditions  
- Seats  
- Bookings  

Each bus contains **40 fixed seats**.

---

## 👥 User Roles

### Admin
- Manage buses, drivers, cities, and expeditions
- View all bookings
- View statistics and charts
- Manage seat availability

### User
- Register and login
- View available expeditions
- Select seats visually
- Book seats
- View booking history
- Export booking data (TXT / CSV)

---

## 🎯 Main Features

- Age validation (18+)
- Email validation
- One-seat selection at a time
- Booked seats shown in red
- Selected seat shown in green
- Prevent duplicate bookings
- Bus & driver availability validation
- DataGridView row selection control
- Export data to TXT and Excel CSV
- Charts for seat usage and statistics

---

## 📊 Charts

- Bus seat usage percentage
- Booking statistics per bus
- Dynamic data loaded from database

---

## 📁 Exporting Data

- TXT files
- Excel CSV files
- Export works on selected rows only

---

## ▶️ How to Run

1. Open the project in Visual Studio
2. Make sure SQLite is installed
3. Run the application
4. Database file: `BusDatabase.db`

---

## 🔐 Default Admin Account

Username: admin1
Password: 123


---

## 📌 Notes

- Built using WinForms
- Seat buttons designed in the form designer
- Uses parameterized SQL queries
- Safe database connection handling

---

## 🚀 Future Improvements

- PDF export
- Web version
- Payment integration
- Advanced reporting

---

## ⭐ License

This project is for educational purposes.
