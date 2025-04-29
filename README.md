# 🚗 Car Rental System - Java OOP Project

## 📌 Project Overview

The **Car Rental System** is a console-based application built using **Java** and follows core **Object-Oriented Programming (OOP)** principles. The project is designed to simulate a basic car rental service, enabling users to browse available cars, rent vehicles, return them, and view rental history.

This project demonstrates a modular and maintainable software structure using classes, encapsulation, inheritance, and file handling (or optional database integration). It is ideal for learning Java OOP while developing a real-world application scenario.

---

## 🎯 Project Goals

- Simulate operations of a real-world car rental service
- Practice OOP concepts such as classes, inheritance, and encapsulation
- Create a menu-driven interface for users and admins
- Enable persistent storage of data (optional)

---

## ⚙️ Core Features

- 👤 **User Registration & Login** (Optional)
- 🚗 **List Available Cars**
- 📋 **View Car Details**
- 🛒 **Rent a Car**
- 🔄 **Return a Car**
- 📜 **View Rental History**
- 🗃️ **Admin Panel** to Add/Remove Cars *(Optional)*
- 🧾 **File-based or Database-based Data Persistence** *(Optional)*

---

## 🧱 Object-Oriented Design (Classes)

- `Car.java` – Contains details about each car (model, make, year, status, price, etc.)
- `Customer.java` – Represents a customer renting a car
- `Rental.java` – Holds rental records, linking customers and cars with dates
- `CarRentalService.java` – Main logic for listing, renting, and returning cars
- `Main.java` – Entry point and menu-driven interface
