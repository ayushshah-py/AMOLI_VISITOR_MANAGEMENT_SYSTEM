# AMOLI_VISITOR_MANAGEMENT_SYSTEM

# 🛂 Visitor Management System

A Django-based web application to streamline and secure the process of managing visitor check-ins and check-outs for offices, institutions, or any organization. This system helps keep track of visitor details, purpose, time logs, and hosts they meet — providing both convenience and security.

## 🚀 Features

* 🔐 **User Authentication** – Admin and Receptionist login with role-based access.
* 📝 **Visitor Registration** – Register visitors with photo, contact, and visit details.
* 🕒 **Check-in / Check-out Logging** – Track when visitors enter and leave the premises.
* 👥 **Host Notification** – Notify the host about the visitor (email or dashboard).
* 📊 **Dashboard Overview** – Graphs and metrics on visitor traffic.
* 🔍 **Search & Filter** – Easily find visitors based on name, date, or host.
* 📁 **Export Reports** – Export visitor data to CSV or PDF.
* 📆 **Visit History** – View past visits by any visitor or to any host.
* 🧾 **Digital Pass Generation** – QR-based visitor pass for entry validation (optional).

## 🏗️ Tech Stack

* **Backend:** Python, Django
* **Frontend:** HTML, CSS, JavaScript, Bootstrap
* **Database:** SQLite (default), can be switched to PostgreSQL/MySQL
* **Other Tools:** Django Admin, Django ORM, Pillow (for image processing)

## 📸 Screenshots

### LOGIN VIEW
![LOGIN](https://github.com/ayushshah-py/AMOLI_VISITOR_MANAGEMENT_SYSTEM/blob/main/LOGIN%20VIEW.png?raw=true)

### DASHBOARD VIEW
![DASHBOARD](https://github.com/ayushshah-py/AMOLI_VISITOR_MANAGEMENT_SYSTEM/blob/main/DASHBOARDS%20VIEW.png?raw=true)

### DEPARTMENTS VIEW
![DEPARTMENTS](https://github.com/ayushshah-py/AMOLI_VISITOR_MANAGEMENT_SYSTEM/blob/main/DEPARTMENTS%20VIEW.png?raw=true)

### USERS VIEW
![USERS](https://github.com/ayushshah-py/AMOLI_VISITOR_MANAGEMENT_SYSTEM/blob/main/LIST%20OF%20USERS.png?raw=true)

### VISITORS VIEW
![VISITORS](https://github.com/ayushshah-py/AMOLI_VISITOR_MANAGEMENT_SYSTEM/blob/main/LISTV%20OF%20VISITORS%20.png?raw=true)

### DAY REPORTS VIEW
![DAY REPORTS](https://github.com/ayushshah-py/AMOLI_VISITOR_MANAGEMENT_SYSTEM/blob/main/DAILY%20REPORTS%20VIEW.png?raw=true)

### DAY REPORTS PRINT VIEW
![DAY REPORTS PRINT VIEW](https://github.com/ayushshah-py/AMOLI_VISITOR_MANAGEMENT_SYSTEM/blob/main/DAILY%20VISITORS%20LOGS%20REPORT%20PRINT%20VIEW.png?raw=true)

### LIST OF VISITORS PRINT VIEW
![LIST OF VISITORS PRINT VIEW](https://github.com/ayushshah-py/AMOLI_VISITOR_MANAGEMENT_SYSTEM/blob/main/LIST%20OF%20VISITORS%20PRINT%20VIEW.png?raw=true)

## 📂 Project Structure

```
visitor-management-system/
│
├── visitor_management/     # Main Django project
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── visitors/               # App for handling visitor operations
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   └── templates/
│       └── visitors/
│
├── static/                 # Static files (CSS, JS)
├── media/                  # Uploaded visitor photos
├── db.sqlite3              # Database file (if using SQLite)
└── manage.py
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/visitor-management-system.git
cd visitor-management-system
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser

```bash
python manage.py createsuperuser
```

### 6. Run the Server

```bash
python manage.py runserver
```

Visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## 🧪 Usage

* Login as Admin or Receptionist.
* Register incoming visitors with name, photo, mobile, host, purpose, etc.
* Automatically log check-in time.
* On exit, log check-out and update records.
* View history and export data from dashboard.

## ✅ Future Improvements

* 🔔 Email/SMS notifications to host.
* 🧾 QR code check-in and ID scanning.
* 🌐 Multi-location support.
* 📱 Mobile responsive or PWA version.
* 🛡️ Role-based detailed permissions.

## 🧑‍💻 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

## 🙋‍♂️ Author

* **AYUSH SHAH** – [GitHub](https://github.com/yourusername)
