# Fee Report System

## Overview
The **Fee Report System** is a comprehensive software solution designed to automate and streamline the fee management process in educational institutions. This system replaces traditional manual fee tracking methods with an efficient electronic solution, ensuring accuracy, transparency, and efficiency. Built using **Java and MySQL**, the system allows administrators, students, and parents to manage fee-related activities with ease.

## Features
- **Student Enrollment:** Register and manage student details.
- **Fee Calculation & Payment Tracking:** Automate fee calculations and monitor payments.
- **Detailed Reporting:** Generate reports on fee status, overdue payments, and revenue.

## Technologies Used
- **Backend:** Java (JDK 8 or later)
- **Database:** MySQL
- **Frontend:** Java Swing (for desktop application)

## Installation and Setup
### Prerequisites
Ensure you have the following installed:
- **Java Development Kit (JDK)** (8 or later)
- **MySQL Server** (5.7 or later)
- **IDE:** Eclipse/IntelliJ IDEA/NetBeans

### Database Configuration
1. Create a MySQL database:
   ```sql
   CREATE DATABASE fee_report_system;
   ```
2. Create necessary tables (Refer to `db_schema.sql` for table structures).
3. Configure database connection in `config.properties`:
   ```properties
   db.url=jdbc:mysql://localhost:3306/fee_report_system
   db.user=root
   db.password=yourpassword
   ```

### Running the Application
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/fee-report-system.git
   cd fee-report-system
   ```
2. Compile and run:
   ```sh
   java -jar target/FeeReportSystem.jar
   ```

## Usage
- **Admin Dashboard:** Manage students, payments, reports, and notifications.
- **Student/Parent Portal:** View fee status, make payments, and download receipts.
- **Reports:** Generate and export financial reports.

## Output Screenshots
![image](https://github.com/user-attachments/assets/8bb12589-5168-4ddc-9ee1-89cd272c5771)
![image](https://github.com/user-attachments/assets/e7ee6d5b-005f-48a9-9552-6e83db9c3063)
![image](https://github.com/user-attachments/assets/21e5b5d4-a045-456e-855b-3d70c6e296a2)






