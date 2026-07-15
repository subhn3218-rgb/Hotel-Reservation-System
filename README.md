
# 🏨 Hotel Reservation System

A sleek, modern, and user-friendly desktop application built entirely in **Java** using **Swing** and **AWT** to streamline hotel room bookings and reservation management. The application features a custom-designed, dark-themed GUI (Graphical User Interface) that provides a smooth and intuitive experience for both guests and hotel administrators.A Java Swing desktop application for hotel bookings. <br>


## ✨ Features

* **🔒 Secure User Authentication**: Custom Sign-In and Sign-Up screens with a secure password field and welcoming pop-up dialogue alerts (`JOptionPane`) upon successful login.
* <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/03effacd-16d8-4dd6-9dc6-1d8bea26f1b5" />
* <img width="958" height="563" alt="image" src="https://github.com/user-attachments/assets/4831ba8e-1ca7-498c-ba33-f723f1cde3d2" />
<br>
* **📊 Modern Navigation Dashboard**: A centralized hub featuring clean button controls to easily browse rooms, view reservation details, cancel bookings, or process refunds.
* <img width="959" height="564" alt="image" src="https://github.com/user-attachments/assets/fc9c6ed5-04a5-44bf-84ce-fd2163b75d41" />
<br>
* **🛌 Dynamic Room Search & Booking**: 
    * Real-time tracking of room availability status (e.g., *Available*, *Booked*).
    * Dynamic display of room categories (Standard, Deluxe, Suite etc.) and standard nightly rates.
    * <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/7a08395b-5884-4c90-8de2-cf56f7a0ae26" />
    <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/6fdcbb95-0e67-4c93-afc6-09addbb5a934" />
<br>
* **📅 Booking Ledger**: A clear table view displaying active reservations with essential details such as unique **Reservation IDs**, room numbers, check-in/check-out dates, and total booking costs.
* <img width="959" height="559" alt="image" src="https://github.com/user-attachments/assets/afa33a76-699a-43aa-a105-e0c21cff4231" />
  <br>
* **💸 Refund & Cancellation System**: 
    * Select active reservations from a list to cancel them instantly.
    * Features a **one-click 50% refund processing** pipeline, allowing administrators or users to easily trigger and process policy-compliant refunds.
      <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/726c112b-40ad-4f09-862f-201c2b364406" />
      <img width="959" height="563" alt="image" src="https://github.com/user-attachments/assets/8041c574-5536-466b-98b2-000296fbf0cf" />
<img width="959" height="561" alt="image" src="https://github.com/user-attachments/assets/3d520f44-396f-494e-becc-a934b4095c21" />
<br>
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

---


