# Event Management System

A simple **Flask + MySQL** web application that allows users to register for events and enables admins to create and manage events.  
This project demonstrates backend development, authentication, CRUD operations, and database integration.

---

##  Features
- User signup & login  
- Role-based access (**Admin / User**)  
- Admin panel to:
  - Create events  
  - Edit events  
  - Delete events  
  - View registrations  
- User can:
  - View upcoming events  
  - Register for events  
  - View own registrations  
- MySQL database integration  
- Clean project structure for learning & interview preparation  

---

## Tech Stack
- **Backend:** Python, Flask  
- **Database:** MySQL  
- **Frontend:** HTML, CSS, JavaScript  
- **Tools:** Virtualenv, Git  

---

##  Project Structure

event-management-system/
│── app.py
│── auth.py
│── db.py
│── templates/
│ ├── login.html
│ ├── register.html
│ ├── events.html
│ └── admin_dashboard.html
│── static/
│── data/
│── README.md


---

## ⚙️ Installation & Running
### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/event-management-system.git
cd event-management-system

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Configure MySQL

Create database:

CREATE DATABASE event_db;


Update your DB credentials inside the project (if required).

4️⃣ Run the application
python app.py


Open in browser:

http://127.0.0.1:5000

🧪 Sample Demo Credentials

Admin login:

Email: admin@example.com
Password: admin123


User login:

Email: user@example.com
Password: user123

🗄️ Database Tables
users

id

name

email

password

role

events

id

title

description

date

capacity

registrations

id

user_id

event_id

 Future Enhancements

Switch to SQLAlchemy ORM

Add password hashing

Add full admin dashboard UI

Add email notifications

Add pagination & search

📩 Contact

If you want to improve this project or need help running it:
📧 shaikshabir967@gmail.com

📜 License

This is an open-source project for learning and practice.
