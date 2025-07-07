# 🏥 Hospital Management System in PHP CodeIgniter

A complete Hospital Management System developed using **PHP with CodeIgniter** and **MySQL**. This web-based application is designed to manage hospital operations including patients, doctors, nurses, pharmacists, appointments, reports, bed allotments, invoices, and more.
In particular, this Online Hospital Management System project in PHP CodeIgniter focuses mainly on keeping track of the patient’s activities. To be more precise, the system helps to keep track of hospitals’ doctors, patients, nurses, departments, and so on. Also, the system contains all the report management and bed allotments. In addition, the system allows for managing medicine categories, billings, and more. Evidently, this project contains an admin panel with a doctor, patient, nurse, accountant, and pharmacist panel. In an overview of this web application, a nurse has a minor role and control over the system. He/she can manage patients, view appointments, and report. Also, the user can manage bed ward, allotments, and blood banks where the nurse can add names of donors with blood details.

---

## 📋 About the Project

This project primarily focuses on maintaining all activities and workflows of a hospital. It includes user panels such as:

- Doctor Panel  
- Patient Panel  
- Nurse and Pharmacist Panel  
- Accountant Panel  
- Set up Doctor’s Department  
- Doctor Management  
- Patient Management  
- Make Appointments  
- Manage Prescriptions  
- Nurse Management  
- Pharmacist Management  
- View Payment History  
- Invoice Management  
- Set up Bed Numbers  
- Bed Allotment  
- Admit Patients, Admit History  
- Manage Patient Report  
- Diagnosis Report  
- Add Medicine Records  
- Blood Bank Management  
- Update User Profile  
- System Settings  
- Notice Management  


Each role has specific responsibilities in the system to ensure smooth hospital operations. The admin oversees everything but cannot modify clinical data — ensuring data integrity.

---


## 🚀 Features

### ✅ Admin Panel
An administrator has full control over the system. He/she can manage departments, patients, doctors, pharmacists, and so on. Here, each and every section has its own respective details such as name and other important details. The very first step of the management of this system is to set up departments for the doctors. There are minor fields for the department such as name and description. This whole department section plays an important role in the management of the doctor’s record. As each of these doctors’ records falls under different departments. 
In Addition, the system allows managing doctor’s records. And with it, the administrator can set up personal and login details for each one of them. And the same process goes for the nurse, patient, pharmacist, and accountant management section.
- Full control of the system
- Manage departments, doctors, nurses, patients, pharmacists, accountants
- View appointments, payments, beds, and reports
- Publish notices and update system settings

### ✅ Doctor Panel
- View appointments and manage patients
- Write prescriptions linked to pharmacist and laboratorist

### ✅ Patient Panel
- View appointments, admit history, prescriptions
- Check invoices and payment history

### ✅ Nurse Panel
- Manage patient records
- View appointments, reports, bed allotments
- Maintain blood bank donor list

### ✅ Pharmacist Panel
- Manage medicine categories and stock
- View prescriptions

### ✅ Accountant Panel
- Generate invoices and manage payments
- Mark invoices as paid/unpaid
- View payment history

---

## 🏥 Hospital Functions

- Department Management
- Doctor Scheduling
- Appointments & Prescriptions
- Bed Management and Allotments
- Diagnosis Reports: Operation, Birth, Death
- Blood Bank Management
- Invoice & Billing System
- Notice Board & Calendar
- System Settings and User Profiles



## 📊 System Modules and Functionalities

### 🔍 Monitor Hospital Activities
The administrator can oversee all sections of the system such as:
- Appointment listings
- Completed payments
- Current bed status
- Medicine inventories
- Blood bank records (including donor details)
- Operation, birth, and death reports

> 🔐 Note: The admin **cannot modify** these records — only authenticated role-based users can do so. The admin’s role is to **monitor** and ensure smooth functioning.

---

### 📣 Noticeboard, System Settings, and More
Admins can:
- Post system-wide notices (title, date, description)
- View notices via user dashboards and calendars
- Modify system settings (name, title, contact info)
- Manage and update their own profile and password

---

### 🗓️ Appointment & Prescription Management
This crucial module allows:
- Creating and assigning appointment dates per patient
- Appointments visible in both doctor and patient dashboards
- Doctors to issue prescriptions (case history, medication, notes)
- Prescriptions are shared with both pharmacists and laboratorists

---

### 🛏️ Bed Allotment & Patient Reports
- Bed allotment is managed by the nurse panel
- Patients can be assigned available beds with allotment and discharge dates
- Patient reports can be created for:
  - Operation
  - Birth
  - Death
- Reports contain details like patient name, doctor, date, and description
- Records searchable by keywords

---

### 👨‍⚕️ Patient Panel
Patients can:
- View appointments and selected doctors
- Track admit history (bed, ward, doctor, discharge date)
- View operation history
- Check invoices and payment history

---

### 💊 Pharmacist Panel
Pharmacists can:
- View and manage patient medications
- Create and manage medicine categories
- Add medicines (name, description, category, price, quantity)
- Monitor stock status
- Update profile and change password

---

### 🧾 Invoice & Blood Bank Management
Accountants can:
- Generate invoices (patient, title, description, amount, status)
- Update status (Paid/Unpaid)
- View payment history (only paid)
- Manage blood bank donors and records

---

### 🎨 Dashboard & UI
- Clean and responsive UI with Bootstrap and Vanilla CSS
- Color-coded modules for intuitive navigation
- All users access personalized dashboards based on their role

---



---

## 💻 Technologies Used

| Technology | Description |
|-----------|-------------|
| **Language** | PHP 5.6 |
| **Framework** | CodeIgniter |
| **Database** | MySQL |
| **UI Framework** | Bootstrap |
| **Server** | Apache (via XAMPP) |

---

## 🛠️ Installation Steps

### 1. Requirements
- PHP Version: **5.6 (Do NOT use PHP 7+ or 8+)**
- XAMPP (with Apache & MySQL)

### 2. Setup Instructions

```bash
1. Download & extract the project.
2. Copy the folder to `C:/xampp/htdocs/`
3. Start XAMPP > Start Apache & MySQL
4. Visit: http://localhost/phpmyadmin
5. Create a new database (check project folder for name)
6. Import the `.sql` file from the `/DATABASE FILE` folder
7. Open the browser and go to:
   http://localhost/[project_folder_name]
