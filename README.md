# Mart Management System (MMS)

## 📌 Project Overview

The **Mart Management System** is a software solution designed to computerize and automate daily mart operations. The system assists owners and investors by streamlining stock control, billing, and employee management into a single, efficient platform.

## 🏗 System Architecture

This project follows a **Three-Tier Architecture** to ensure high performance, security, and scalability:

1. 
**Presentation Layer (Client Tier):** The front-end user interface containing role-based buttons and input forms.


2. 
**Business Logic Layer (Application Tier):** The "heart" of the application that handles data processing, input validation, and business rules like discount calculations and inventory alerts.


3. 
**Data Layer (Database Tier):** Responsible for secure data storage and retrieval of product, sale, and employee records.



---

## 🚀 Key Features

### 📦 Stock Management (Manager Access)

* 
**Inventory Records:** Add and update products including supplier details, purchase/sale prices, and expiry dates.


* 
**Intelligent Alerts:** Automated notifications for low stock levels and upcoming product expirations to prevent financial loss.


* 
**Search & View:** Real-time availability checks to assist in buying decisions.



### 💳 Billing System (Employee Access)

* 
**Sales Processing:** Fast checkout interface with support for QR scanning.


* 
**Automated Calculations:** Application layer logic calculates totals and applies discount percentages automatically.


* 
**Inventory Integration:** Stock quantities are automatically decremented in the database upon every successful sale.



### 👥 Employee & Business Management (Owner Access)

* 
**Staff Records:** Comprehensive management of employee profiles, qualifications, and legal documentation.


* 
**Performance Tracking:** Attendance and sales performance monitoring for bonus and promotion evaluation.


* 
**Reporting:** Generation of daily, weekly, and monthly sales and profit reports for business self-evaluation.



---

## 🌿 Branching Strategy

We utilize the **Git Flow** model to maintain code integrity:

* **`main`**: Production-ready, stable code.
* **`develop`**: Integration branch for new features.
* **`feature/`**: Temporary branches for specific modules (e.g., `feature/billing-logic`).

---

## 💻 Setup & Installation

This project is built using C# and the .NET framework as indicated by the solution file.

1. **Clone the Repository:**
```bash
git clone https://github.com/your-username/mart-management-system.git

```


2. **Open the Solution:**
Launch `MMS.slnx` in Visual Studio.


3. **Restore Dependencies:**
Build the solution to automatically restore NuGet packages defined in `MMS.csproj`.


4. **Database Configuration:**
Ensure your local SQL server is running and update the connection string in the Application Layer settings to point to your `Product` and `Employee` tables.


5. **Run Application:**
Press `F5` to start the application. Use the **Login Interface** to access role-specific features.



---

## 🛠 Project Board Status

* **Done:** Repository setup, Architecture design, README documentation.
* **In Progress:** Core Three-tier logic implementation and Database connectivity.
* **To-Do:** QR Scanning integration and Expiry notification email logic.

---

## 📝 Contributors

* **[Haseeb Ahmad]** - Group Lead
* **[Maira Waheed]**
* **[Iqra Abdul Malik]**
* **[Muhammad Faeiq]**
