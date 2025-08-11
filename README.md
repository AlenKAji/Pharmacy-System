# Pharmacy Management System

A Java + MySQL-based desktop application designed to manage the day-to-day operations of a pharmacy. It helps in maintaining medicine records, tracking stock, managing purchases and sales, and generating reports to improve efficiency and accuracy.

---

## How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AlenKAji/Pharmacy-System.git
   ```

2. **Set Up the Database**
   - Install **WAMP**, **XAMPP**, or any MySQL server.
   - Open **phpMyAdmin** or your MySQL client.
   - Import the `.sql` file from the `database/` folder into MySQL to create the necessary tables.

3. **Open the Project**
   - Use **Eclipse J2EE** or any preferred Java IDE.
   - Ensure **JDK** and **JRE** are installed and configured.

4. **Configure the Database Connection**
   - Update the MySQL username and password in the project’s configuration files if required.

5. **Run the Project**
   - Build and run directly from your IDE.

---

## Login Credentials
```text
ID: 1
Password: admin
```
*These can be modified later via MySQL or through the application’s admin interface.*

---

## Project Overview

The Pharmacy Management System is aimed at helping pharmacists efficiently manage their store operations. The application stores information about available medicines, suppliers, purchases, and sales. It can generate invoices, bills, and reports as per requirements, and it keeps track of expiry dates and stock quantities. The admin can also manage employee accounts and internal communication.

---

## Key Features
- **Login System** – Secure login for admin and employees.
- **Medicine Management** – Add, update, delete medicine records.
- **Purchase & Sales Tracking** – Record incoming stock and sales transactions.
- **Stock Monitoring** – Keep track of quantities and expiry dates.
- **Reporting** – Generate invoices, receipts, and sales reports.
- **Messaging System** – Built-in communication for employees.

---

## Tools & Technologies
- **Frontend:** Java (Swing)
- **Backend:** MySQL
- **Server:** WAMP / XAMPP (or any MySQL server)
- **IDE:** Eclipse J2EE

**Hardware Requirements:**
- Processor: Intel Pentium / AMD equivalent
- Memory: 1GB+ RAM
- Storage: 40GB HDD

**Software Requirements:**
- Operating System: Windows / MacOS / Linux
- Java Development Kit (JDK) & Java Runtime Environment (JRE)
- MySQL Server

---

## Database Design
**ER Diagram**  
![ER Diagram](diagram/ER_diagram.png)

**Relational Schema**  
![Relational Schema](diagram/RelationalSchema.png)

---

## Future Scope
- **Barcode Integration** – Faster billing and expiry tracking with barcode scanning.
- **Cloud Database** – Remote access and backup.
- **Biometric Authentication** – Enhanced security for admin and employees.
- **Advanced Analytics** – Generate insights from sales and purchase trends.
- **Mobile Version** – Companion mobile application for quick access.

---

**Author:** Alen K Aji</br>
**Thanks to https://github.com/syedibrahim**
