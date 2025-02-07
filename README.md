<<<<<<< HEAD
Features & Functionality

Admin Panel

User Management

Signup/Login (No approval required).

Manage doctors: Register, view, approve, reject, or delete doctors who apply for jobs in the hospital.

Manage patients: Admit, view, approve, reject, or discharge patients when treatment is completed.

Appointments & Billing

View, book, approve, or reject patient appointment requests.

Generate and download invoice PDFs based on medicine cost, room charges, doctor fees, and other charges.

Doctor Panel

Job Application & Access Control

Apply for a job in the hospital (Approval required by admin before login access is granted).

View only assigned patient details (Name, Mobile, Symptoms).

View a list of discharged patients.

Manage appointments assigned by the admin.

Delete appointments after attending them.

Patient Panel

Registration & Access Control

Create an account to get admitted to the hospital (Approval required by admin before login access is granted).

View assigned doctor details (Specialization, Mobile, Address).

Track appointment status (Pending/Confirmed by admin).

Book new appointments (Approval required by admin).

View and download invoice PDFs (Only after discharge by admin).

Installation & Setup Guide

Prerequisites

Ensure Python 3.7.6 is installed (Select "Add to Path" during installation).

Open the terminal and execute the following commands:



Security Concerns & Recommendations

Current Issues

Admin Account Vulnerability:

Anyone can register as an admin. It is recommended to disable open admin signup and use a superuser creation process instead.

Doctor-Patient Dependency:

A patient cannot be admitted unless at least one doctor is available in the hospital. Ensure doctors are added before admitting patients.

User Password Updates:

On doctor/patient profile update pages, passwords must be updated manually, which may cause inconvenience. Implement a password reset mechanism.

Suggested Improvements

Implement role-based authentication with Django Admin Permissions.

Use email verification during signup to prevent unauthorized account creation.

Add captcha verification to prevent bot signups.

Implement a password reset feature for better security.

This system provides a comprehensive hospital management solution, ensuring seamless administration while maintaining security and efficiency.
=======
# Hospital-Mangement
>>>>>>> 4fa4c3ae9c1dbeaed60802bef24a7247392a7b09
