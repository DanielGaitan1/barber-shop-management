# BarberManager (Barber OS)

##  Project Overview
**Context:** Software Engineering Capstone Project
**Role:** Documentation and Presentation of the Project, Backend Architect, Database Contribution,

A comprehensive full-stack management system designed to streamline barbershop operations, enabling appointment scheduling, inventory tracking, and staff management.

> ** Academic Disclaimer:** This repository contains the source code developed by our student team. My primary contributions focused on **Database Architecture (MariaDB/SQL)**, **Backend Logic (Flask)**, and **Technical Documentation/Demos**.

---

##  Project Demos & GenAI Integration
I utilized **Generative AI tools** to produce documentation and video assets, accelerating the presentation workflow.

###  System Walkthrough
*(Videos located in the `/demos` folder)*

| Appointment Booking | Inventory Management |
| :---: | :---: |


https://github.com/user-attachments/assets/ede56432-3794-405a-a2da-385b20a46a99



https://github.com/user-attachments/assets/9fc12633-2833-4511-aaad-5f93b2707b56




*> Note: If videos do not play directly, please view them in the [demos/](./demos/) folder.*

---

## 🛠 Technical Stack
* **Language:** Python 3.8+
* **Backend Framework:** Flask
* **Database:** MySQL / MariaDB (Schema in `/sql`)
* **Frontend:** HTML5, Bootstrap 5.3, FontAwesome 6.4
* **Database Management:** DBeaver

---

## 🗄 Database Architecture (My Contribution)
I led the design of the relational schema to ensure data integrity for critical business operations. Key relationships include:
* **Appointments:** `Users` ↔ `Barbers` ↔ `Services`
* **E-commerce:** `Products` ↔ `Orders` ↔ `Inventory`

### 📄 Documentation
* [**📂 View System Architecture & Diagrams**](./docs/)
* [**📖 User Manual**](./docs/)

---

##  Key Features
* **🗓️ Appointment Scheduling:** Real-time slot reservation system.
* **💈 Staff Management:** Admin tools to manage barbers and schedules.
* **🏪 Inventory Control:** Product tracking and online store functionality.
* **📊 Reporting:** Sales and operation reports generation.
* **🔒 Security:** Role-based authentication and data sanitization.

---

## ⚙️ Installation (Local Dev)

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/DanielGaitan1/barber-shop-management.git](https://github.com/DanielGaitan1/barber-shop-management.git)
    ```

2.  **Set up Virtual Environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Windows: venv\Scripts\activate
    pip install -r requirements.txt
    ```

3.  **Database Setup:**
    ```bash
    mysql -u root -p < backup-barberManager.sql
    ```

4.  **Run Application:**
    ```bash
    python main.py
    ```

---
*Developed by Daniel Gaitan & Team | Software Engineering II*
