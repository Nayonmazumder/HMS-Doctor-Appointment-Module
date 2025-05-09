# HMS- DOCTOR APPOINTMENT BOOKING MODULE 

<br/>
<p align="center">
  <a href="https://github.com/Nayonmazumder/HMS-Doctor-Appointment-Module">
    <img src="static/img/logo.png" alt="Logo"  height="80">
  </a>

  <h3 align="center">HMS- DOCTOR APPOINTMENT BOOKING </h3>

  <p align="center">
    HMS- DOCTOR APPOINTMENT BOOKING MODULE (USING DJANGO)
    <br/>
    <br/>
    <a href="https://hms-doctor-appointment-module.onrender.com">View Demo</a>
    .
    <a href="https://github.com/Nayonmazumder/HMS-Doctor-Appointment-Module/issues">Report Bug</a>
    .
    <a href="https://github.com/Nayonmazumder/HMS-Doctor-Appointment-Module/issues">Request Feature</a>
  </p>
</p>

## Table Of Contents

- [Appointment Management](#hospital-management)
  - [Table Of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
  - [Built With](#built-with)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Live Demo](#live-demo)
  - [Conception](#conception)
  - [Screenshots](#screenshots)
  - [Seed Database](#seed-database)

## About The Project

The HMS-Doctor Appointment Module (Using Django) project is designed to streamline the interaction between doctors and patients. Doctors have the capability to upload blogs or save them as drafts, allowing them to share valuable medical information and insights. Additionally, the system enables doctors to manage appointments by checking, accepting, or canceling them. This ensures efficient scheduling and communication between healthcare providers and patients.

For patients, the project offers a user-friendly interface for registration and login. Once logged in, patients can access the blog section to read and comment on doctors' posts. The appointment booking feature allows patients to choose a specific doctor based on filters and schedule appointments. Patients can also view their past appointments, creating a comprehensive and accessible record of their medical history. Overall, this Hospital Management system enhances communication and accessibility in the healthcare process for both doctors and patients.

## Built With

**FRONT-END :**
- HTML
- CSS 
- JS
- Bootstrap
- jQuery

**BACK-END :**
- Python
- Django
- SQLite

## Getting Started

To get started with the HMS-Doctor Appointment Module (Using Django), follow the instructions below.

### Prerequisites

Make sure you have the following prerequisites installed on your machine:

- Python

### Installation

1. Clone the repository to your local machine:

```bash
   git clone https://github.com/Nayonmazumder/HMS-Doctor-Appointment-Module.git  
```

2. Create virtual environmenet  :  
```bash
   virtualenv env
   or  
   python -m venv env
```
then start the environmenet :  
```bash
  env\Scripts\activate
```

3. Navigate to the project directory:
```bash 
cd HMS-Doctor-Appointment-Module
```

4. Setup a Virtual Environment :
```bash
pipenv shell
```

5. Install the required dependencies:
```bash
pip install -r requirements.txt
```

7. Apply migrations to set up the database:
```bash 
python manage.py migrate
```

## Usage

1. Start the development server:  
```bash
python manage.py runserver 
```

3. Open your web browser and visit http://localhost:8000 to access the Hospital Management System.

4. Follow the on-screen instructions to register/login as a doctor or patient.

5. Explore the features, including blog management, appointment scheduling, and more.

## Live Demo
Check Website Online here : [HMS-Doctor Appointment Module](https://hms-doctor-appointment-module.onrender.com)


## Conception
1. Database Schema
![db](screenshots/db.png)

2. Use Case Diagram : 
![usecase](screenshots/usecase.PNG)

## Screenshots
- Login Page : 
![login](screenshots/login.PNG)

- Register Page : 
![register](screenshots/register.PNG)

- Profile Page : 
![profile](screenshots/profile.PNG)

- Blogs : 
![blogs](screenshots/blogs.PNG)

- Upload Blog Page : 
![upload_blog](screenshots/upload_blog.PNG)

- Draft Blogs Page : 
![draft_blog](screenshots/draft_blog.PNG)

- Doctor Appointments Page : 
![doctor_app](screenshots/doctor_app.PNG)

- Patient Book Appointments Page : 
![patient_book_app](screenshots/patient_book_app.PNG)

- Patient Confirm Appointments Page : 
![patient_confirm_app](screenshots/patient_confirm_app.PNG)

- Patient View Appointments Page : 
![patient_view_app](screenshots/patient_view_app.PNG)


## Seed Database
```bash
python manage.py loaddata seed/categories.json 
python manage.py loaddata seed/specialities.json
python manage.py loaddata seed/status.json
python manage.py loaddata seed/time.json
```
