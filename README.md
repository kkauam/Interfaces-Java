<h1 align="center">🚗 Car Rental System (Java)</h1>

<p align="center">
  A simple project to practice <b>Interfaces</b> and <b>Object-Oriented Programming</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
</p>

---

## 📖 About

This application simulates a car rental service.  
It calculates the rental price based on duration and applies taxes using an interface.

---

## 🧠 What I Learned

- Using **interfaces** in Java  
- Separation of responsibilities  
- OOP concepts  
- Working with `LocalDateTime` and `Duration`  

---

## ⚙️ Features

- ⏱️ Rental duration calculation  
- 💰 Payment per hour or per day  
- 🧾 Tax calculation:
  - 20% for values up to 100  
  - 15% for values above 100  
- 📄 Displays final invoice  

---

## 🏗️ Project Structure

```bash
src/
 ├── application/
 │    └── Program.java
 │
 ├── model/
 │    ├── entities/
 │    │    ├── CarRental.java
 │    │    ├── Invoice.java
 │    │    └── Vehicle.java
 │    │
 │    └── service/
 │         ├── RentalService.java
 │         ├── TaxService.java
 │         └── BrazilTaxService.java
