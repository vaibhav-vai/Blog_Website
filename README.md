Flask Blog Website
A full-stack blog application built with Python and Flask, featuring CRUD operations, user authentication, role-based access, and deployment on Render.
🚀 Features

🔐 User Authentication: Register, login, and manage sessions securely.
👥 User Roles:
Users: View posts and add comments.
Admins: Create, edit, and delete posts.


💬 Comments System: Users can comment on posts.
🗄️ Database Relationships: Manage Users ↔ Posts ↔ Comments relationships.
⚡ CRUD Operations: Complete Create, Read, Update, Delete functionality.
🌐 Deployed on Render: Accessible online anytime.
👉 Live Demo: Check out the live application.

🛠️ Tech Stack

Backend: Python, Flask, SQLAlchemy
Frontend: HTML, CSS, Bootstrap, Jinja Templates
Database: SQLite (extensible to PostgreSQL/MySQL)
Deployment: Render

📂 Project Structure
flask-blog-website/
├── app.py                # Main Flask application
├── static/               # CSS, JS, and image assets
├── templates/            # HTML templates with Jinja
├── models.py             # SQLAlchemy database models
├── forms.py              # Flask-WTF forms
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation

⚙️ Installation

Clone the repository:
git clone https://github.com/your-username/flask-blog-website.git
cd flask-blog-website


Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate     # On Windows


Install dependencies:
pip install -r requirements.txt


Run the application:
flask run


Open in your browser:Visit http://127.0.0.1:5000/


🎯 Future Improvements

Implement JWT-based authentication.
Develop a REST API for mobile/SPA integration.
Add pagination for posts and comments.
Create user profile pages.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork this repository and submit a pull request.

Fork the project.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.

👤 Author
Vaibhav
LinkedIn  
🔥 Support
If you like this project, please give it a ⭐ on GitHub!
