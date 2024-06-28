# PulseLifeDonors
## Hosted at https://ethanburke.pythonanywhere.com/

## Overview

Introducing a specialized Database Management System (DBMS) tailored for Blood Donation, this project addresses the critical need for efficient management and coordination in the blood donation ecosystem. The system seamlessly connects donors, blood banks, donations, and recipients, creating a comprehensive solution to streamline the blood donation process.

## Entities

### 1. Donors

At the core of the system, donors' information is stored, including personal details, blood type, contact information, health status, and donation history. Donors can easily register, schedule appointments, and track their contributions, fostering a sense of engagement and commitment to the cause.

### 2. Blood Banks

Blood banks play a pivotal role in managing and distributing blood. Information includes inventory levels, location, contact details, and capacity. The DBMS assists blood banks in monitoring and maintaining an adequate supply of blood, facilitating timely responses to emergencies.

### 3. Donations

Each blood donation is recorded as a unique entity, encompassing details such as the donation date, quantity, blood type, test results, and the staff responsible. This allows for thorough tracking, quality assurance, and efficient allocation of donated blood.

### 4. Recipients

Recipient profiles encompass their medical condition, contact information, and transfusion history. The system enables rapid matching of recipients with compatible donors, potentially saving lives in critical situations.

## Features

- **Donor Engagement:** The system ensures donors are recognized, engaged, and appreciated for their contributions. It streamlines the process of blood donation, making it easier for individuals to participate, schedule appointments, and understand their eligibility.

- **Recipient Matching:** For recipients in need of blood, the DBMS expedites the search for compatible donors, ensuring a swift response to medical emergencies.

- **Optimized Inventory Management:** Blood banks benefit from optimized inventory management, minimizing waste and enhancing their ability to meet the needs of healthcare providers.

## How to Use

To get started, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/blood-donation-dbms.git
   cd blood-donation-dbms
   ```
2. **Install Dependencies:**
   ```bash
   pip install Flask Flask-MySQL
   ```
3. **Configure Database:**
    Set up a MySQL database named dbmsproj.
   Update the MySQL configuration in the app.config section of the code.
4. **Run the Application:**
   ```bash
   python app.py
   ```
5. **Access the Application:**
   Open your web browser and go to http://localhost:8080/
