📝 Flask Blog Website
A full-stack blog application built with Python (Flask), showcasing CRUD operations, user authentication, role-based access, and deployment on Render.


🚀 Features
🔐 User Authentication – Register, login, and manage sessions
👥 User Roles
Users: Can view posts and comment
Admin: Can create, edit, and delete posts
💬 Comments System – Users can comment on posts
🗄️ Database Relationships – Users ↔ Posts ↔ Comments
⚡ CRUD Operations – Create, Read, Update, Delete functionality implemented
🌐 Deployed on Render – Accessible online anytime
👉 Live Demo: Blog Website


🛠️ Tech Stack
Backend: Python, Flask, SQLAlchemy
Frontend: HTML, CSS, Bootstrap, Jinja Templates
Database: SQLite (can be extended to PostgreSQL/MySQL)
Deployment: Render


📂 Project Structure
├── app.py              # Main Flask app
├── static/             # CSS, JS, images
├── templates/          # HTML templates (Jinja)
├── models.py           # SQLAlchemy models
├── forms.py            # Flask-WTF forms
├── requirements.txt    # Dependencies
└── README.md           # Project documentation

⚙️ Installation
Clone the repository
git clone https://github.com/your-username/flask-blog-website.git
cd flask-blog-website

Create a virtual environment & activate it
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

Install dependencies
pip install -r requirements.txt

Run the application
flask run

Open in your browser → http://127.0.0.1:5000/


🎯 Future Improvements
Add JWT-based authentication
REST API for mobile/SPA integration
Pagination for posts & comments
Profile pages for users


🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.


👤 Vaibhav
LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/vaibhav-vaibhav/)

🔥 If you like this project, don’t forget to star the repo!
