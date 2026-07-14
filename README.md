<img width="1919" height="1095" alt="image" src="https://github.com/user-attachments/assets/eb5d3a73-aef0-4242-a9b1-bdec21c664eb" /><img width="1919" height="1095" alt="image" src="https://github.com/user-attachments/assets/d6d7c2f4-18fa-416f-baa6-791d4022868f" />
# 🏨 Hotel Reservation System

A sleek, modern, and user-friendly desktop application built entirely in **Java** using **Swing** and **AWT** to streamline hotel room bookings and reservation management. The application features a custom-designed, dark-themed GUI (Graphical User Interface) that provides a smooth and intuitive experience for both guests and hotel administrators.A Java Swing desktop application for hotel bookings. <br>


## ✨ Features

* **🔒 Secure User Authentication**: Custom Sign-In and Sign-Up screens with a secure password field and welcoming pop-up dialogue alerts (`JOptionPane`) upon successful login.
* **📊 Modern Navigation Dashboard**: A centralized hub featuring clean button controls to easily browse rooms, view reservation details, cancel bookings, or process refunds.
* **🛌 Dynamic Room Search & Booking**: 
    * Real-time tracking of room availability status (e.g., *Available*, *Booked*).
    * Dynamic display of room categories (Standard, Deluxe, etc.) and standard nightly rates.
* **📅 Booking Ledger**: A clear table view displaying active reservations with essential details such as unique **Reservation IDs**, room numbers, check-in/check-out dates, and total booking costs.
* **💸 Refund & Cancellation System**: 
    * Select active reservations from a list to cancel them instantly.
    * Features a **one-click 50% refund processing** pipeline, allowing administrators or users to easily trigger and process policy-compliant refunds.

---

## 🛠️ Tech Stack & Libraries

* **Language**: Java (JDK 8 or higher)
* **GUI Framework**: Java Swing & AWT (Abstract Window Toolkit)
* **UI Theme**: Custom Dark Mode Styling

---

## 📂 Project Structure

```text
src/
├── controller/      # Handles business logic and UI event listeners
├── model/           # Data models (User, Room, Reservation classes)
├── view/            # Swing GUI frames and panels (Login, Dashboard, Booking, etc.)
└── database/        # Database connectivity and helper files
