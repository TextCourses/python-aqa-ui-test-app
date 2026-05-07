# 🛠️ Django CRUD Application

A simple and clean CRUD (Create, Read, Update, Delete) web application built using Django framework. This project demonstrates the basic functionality of a typical CRUD system with Django's MVT (Model-View-Template) architecture. Ideal for beginners looking to learn Django by building practical applications.

---

## ✅ Features

- Add new Member
- View list of records
- Update records
- Delete records
- Django Admin Interface
- Form validations
- Clean and responsive UI (optional with Bootstrap)

---

## 🧰 Technologies Used

- Python 3.x
- Django 4.x
- SQLite (default database)
- HTML, CSS
- Bootstrap (optional for styling)

---
## 📁 Project Structure
crud_project/
├── crud_app/
│ ├── admin.py
│ ├── apps.py
│ ├── forms.py
│ ├── models.py
│ ├── tests.py
│ ├── urls.py
│ ├── views.py
│ ├── templates/
│ │ └── crud_app/
│ │ ├── base.html
│ │ ├── list.html
│ │ ├── form.html
│ └── static/
├── crud_project/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── db.sqlite3
├── manage.py
└── requirements.txt

---

## ⚙️ Installation

### Step-by-step instructions:

```bash
# Clone the repository
git clone https://github.com/TextCourses/python-aqa-ui-test-app.git
cd python-aqa-ui-test-app

# Create virtual environment
python -m venv env
source env/bin/activate       # On Windows use: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py makemigrations
python manage.py migrate

# Run the development server
python manage.py runserver
```
Visit: http://127.0.0.1:8000

🧪 Usage
Navigate to the homepage to see the list of records.
Use the Add, Edit, and Delete buttons to perform respective operations.
All fields include basic Django form validation.

🔐 Admin Panel
Create a superuser:
```bash
python manage.py createsuperuser
```
Visit http://127.0.0.1:8000/admin and log in.
Route	Description
/ Homepage
/members/	View Members
/editmember/<id>/	Edit a record by ID
/deletemember/<id>/	Delete a record by ID
/admin/	Django admin panel

👨‍💻 Author
Your Abhishek Shakya
GitHub: @thecodewithabhi
Email: abhishakya@codewithabhi.in

🖼️ Screenshots
![snap-3](https://github.com/user-attachments/assets/3ec36aa8-c467-490a-b583-bb515018dd92)
![snap-2](https://github.com/user-attachments/assets/1e47c470-56ff-4656-995d-f6e5ff82ef20)
![snap-1](https://github.com/user-attachments/assets/2a2892b1-5533-4a0f-91f3-1aa409e6164e)
