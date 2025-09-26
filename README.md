# Task4-REST-API
🚀 Flask REST API with HTML & CSS Frontend
📌 Project Overview

This project demonstrates how to build a REST API using Flask and connect it with a simple HTML + CSS frontend.
It provides CRUD (Create, Read, Update, Delete) operations for managing user data.

You can interact with the API through:

Frontend UI (form + list of users)

API endpoints (via Postman, curl, or any REST client)

🎯 Features

✅ REST API with Flask (GET, POST, PUT, DELETE)
✅ User data stored in in-memory dictionary
✅ Simple HTML form to add users
✅ List of all users displayed dynamically
✅ Styled with CSS for better UI
✅ Frontend communicates with Flask API using JavaScript (fetch API)

🛠️ Tech Stack

Backend: Python (Flask)

Frontend: HTML, CSS, JavaScript (fetch API)

Tools: Postman, Curl (for API testing)

📂 Project Structure
flask_rest_api/
│
├── app.py                # Flask backend (API + frontend serving)
├── templates/
│   └── index.html        # Frontend (HTML)
└── static/
    └── style.css         # CSS styling

⚙️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/flask-rest-api.git
cd flask-rest-api

2️⃣ Install Dependencies
pip install flask

3️⃣ Run the Application
python app.py


The app will start at:
👉 http://127.0.0.1:5000/

🔗 API Endpoints
Method	Endpoint	Description	Example (curl)
GET	/api/users	Get all users	curl http://127.0.0.1:5000/api/users
GET	/api/users/<id>	Get a specific user by ID	curl http://127.0.0.1:5000/api/users/1
POST	/api/users	Create a new user	curl -X POST http://127.0.0.1:5000/api/users -H "Content-Type: application/json" -d '{"name":"Alice","email":"alice@example.com"}'
PUT	/api/users/<id>	Update an existing user	curl -X PUT http://127.0.0.1:5000/api/users/1 -H "Content-Type: application/json" -d '{"email":"new@example.com"}'
DELETE	/api/users/<id>	Delete a user by ID	curl -X DELETE http://127.0.0.1:5000/api/users/1
🎨 Frontend (HTML + CSS)

Open the home page → http://127.0.0.1:5000/

Enter Name and Email in the form.

Click Add User → User is stored in API & displayed in list.

📸 Screenshots
User Form

API Response Example
{
  "1": {
    "name": "Alice",
    "email": "alice@example.com"
  }
}

🚀 Future Improvements

 Replace in-memory storage with SQLite / PostgreSQL

 Add Update & Delete buttons in the frontend

 Add Bootstrap/Tailwind CSS for modern UI

 Add Authentication & JWT tokens

📚 Resources

Flask Documentation

MDN Fetch API

Postman

👨‍💻 Author

Created with ❤️ by Your Name

👉 Do you want me to also add Markdown badges (Python version, Flask version, License, etc.) at the top of README to make it look more professional?

You said:
give cleary to add in readme file with the code i cant so 
ChatGPT said:

Got it 👍 I’ll give you a complete README.md file with proper Markdown formatting and code blocks. You can copy–paste it directly into your README.md file in your GitHub project.

Here’s the full content ⬇️

# 🚀 Flask REST API with HTML & CSS Frontend

## 📌 Project Overview
This project demonstrates how to **build a REST API using Flask** and connect it with a simple **HTML + CSS frontend**.  
It provides CRUD (Create, Read, Update, Delete) operations for managing user data.  

You can interact with the API through:
- **Frontend UI** (form + list of users)
- **API endpoints** (via Postman, curl, or any REST client)

---

## 🎯 Features
✅ REST API with Flask (GET, POST, PUT, DELETE)  
✅ User data stored in **in-memory dictionary**  
✅ Simple **HTML form** to add users  
✅ List of all users displayed dynamically  
✅ Styled with CSS for better UI  
✅ Frontend communicates with Flask API using **JavaScript (fetch API)**  

---

## 🛠️ Tech Stack
- **Backend**: Python (Flask)  
- **Frontend**: HTML, CSS, JavaScript (fetch API)  
- **Tools**: Postman, Curl (for API testing)  

---

## 📂 Project Structure


flask_rest_api/
│
├── app.py # Flask backend (API + frontend serving)
├── templates/
│ └── index.html # Frontend (HTML)
└── static/
└── style.css # CSS styling


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/flask-rest-api.git
cd flask-rest-api

2️⃣ Install Dependencies
pip install flask

3️⃣ Run the Application
python app.py


The app will start at:
👉 http://127.0.0.1:5000/

🔗 API Endpoints
Method	Endpoint	Description	Example (curl)
GET	/api/users	Get all users	curl http://127.0.0.1:5000/api/users
GET	/api/users/<id>	Get a specific user by ID	curl http://127.0.0.1:5000/api/users/1
POST	/api/users	Create a new user	curl -X POST http://127.0.0.1:5000/api/users -H "Content-Type: application/json" -d '{"name":"Alice","email":"alice@example.com"}'
PUT	/api/users/<id>	Update an existing user	curl -X PUT http://127.0.0.1:5000/api/users/1 -H "Content-Type: application/json" -d '{"email":"new@example.com"}'
DELETE	/api/users/<id>	Delete a user by ID	curl -X DELETE http://127.0.0.1:5000/api/users/1
🎨 Frontend (HTML + CSS)

Open the home page → http://127.0.0.1:5000/

Enter Name and Email in the form.

Click Add User → User is stored in API & displayed in list.

📸 Example API Response
{
  "1": {
    "name": "Alice",
    "email": "alice@example.com"
  }
}

🚀 Future Improvements

 Replace in-memory storage with SQLite / PostgreSQL

 Add Update & Delete buttons in the frontend

 Add Bootstrap/Tailwind CSS for modern UI

 Add Authentication & JWT tokens
