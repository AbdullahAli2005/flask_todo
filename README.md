# Flask Todo App

A simple **Flask-based Todo web application** with task creation, completion toggling, and deletion features. The app uses **SQLite** as its database and **Semantic UI** for styling.

---

## Features

* **Add Tasks** – Create new tasks by entering text.
* **Mark Complete / Incomplete** – Toggle task status with one click.
* **Delete Tasks** – Remove tasks permanently.
* **Responsive UI** – Styled using Semantic UI for a clean and modern look.
* **SQLite Database** – Lightweight, file-based database.

---

## Project Structure

```
project-folder/
│
├── app.py               # Main Flask app
├── site.db              # SQLite database (auto-created)
├── templates/
│   └── base.html         # Main HTML template
├── static/               # (Optional) Static files like CSS/JS if needed
└── README.md
```

---

## Installation & Setup

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/flask-todo.git
cd flask-todo
```

2. **Create Virtual Environment (Optional but Recommended)**

```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

3. **Install Dependencies**

```bash
pip install flask flask_sqlalchemy
```

4. **Run the Application**

```bash
python app.py
```

5. **Open in Browser**

```
http://127.0.0.1:5000/
```

---

## Usage

1. **Add a New Task** – Use the input box and click **Add Task**.
2. **Toggle Status** – Click the refresh icon to mark as complete/incomplete.
3. **Delete Task** – Click the trash icon to remove the task.

---

## Dependencies

* **Flask** – Web framework
* **Flask-SQLAlchemy** – ORM for database operations
* **SQLite** – Built-in Python database
* **Semantic UI** – CSS framework (via CDN)

---

## License

This project is licensed under the MIT License.

---

## Author

**Abdullah Ali**
