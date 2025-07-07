# ToDo_list!
# ✅ Django Task Manager

A full-featured **Task Management Web Application** built with Django. This project demonstrates **CRUD functionality** (Create, Read, Update, Delete) with clean, dynamic templates and user-friendly interface.

---

## 📌 Features

- 📝 Create new tasks with a title and completion status
- 👁️ View all tasks
- ✏️ Update existing tasks
- 🗑️ Delete tasks with confirmation
- ✅ Mark tasks as completed
- 💡 Dynamic URLs for updating and deleting tasks
- 🔐 CSRF protection for all forms

---

## 📂 Project Structure

todo/
├── tasks/
│ ├── migrations/
│ ├── templates/
│ │ ├── delete-task.html
│ │ ├── tasks.html
│ │ └── update-task.html
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── forms.py
│ ├── models.py
│ ├── tests.py
│ ├── urls.py
│ └── views.py
├── todo/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── db.sqlite3
└── manage.py

