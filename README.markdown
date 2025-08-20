# Flask Blog Website

A full-stack blog application built with Python and Flask, featuring user authentication, role-based access, CRUD operations, and deployment on Render.

## ✨ Features

- **🔐 User Authentication**: Secure registration, login, and session management.
- **👥 Role-Based Access**:
  - **Users**: View posts and add comments.
  - **Admins**: Create, edit, and delete posts.
- **💬 Comments System**: Users can comment on blog posts.
- **🗄️ Database Relationships**: Seamless Users ↔ Posts ↔ Comments integration.
- **⚡ CRUD Operations**: Full Create, Read, Update, Delete functionality.
- **🌐 Live Deployment**: Hosted on Render for anytime access.
- **[👉 Live Demo](https://blog-website-j678.onrender.com/)**: Explore the live app!

## 🛠️ Tech Stack

- **Backend**: Python, Flask, SQLAlchemy
- **Frontend**: HTML, CSS, Bootstrap, Jinja Templates
- **Database**: SQLite (supports PostgreSQL/MySQL)
- **Deployment**: Render

## 📂 Project Structure

```
flask-blog-website/
├── app.py                # Core Flask application
├── static/               # CSS, JavaScript, and images
├── templates/            # Jinja HTML templates
├── models.py             # SQLAlchemy database models
├── forms.py              # Flask-WTF form definitions
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

## ⚙️ Setup Instructions

### Prerequisites
- Python 3.8+
- Git

### Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/flask-blog-website.git
   cd flask-blog-website
   ```

2. **Set Up Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate     # Windows
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   flask run
   ```

5. **Access the App**:
   Open [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your browser.

## 🚀 Future Enhancements

- Add JWT-based authentication.
- Build a REST API for mobile/SPA support.
- Implement pagination for posts and comments.
- Create user profile pages.

## 🤝 Contributing

We welcome contributions! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## 👤 Author

**Vaibhav**  
[LinkedIn](https://www.linkedin.com/in/vaibhav-vaibhav/)

## ⭐ Support

If you find this project useful, please give it a star on [GitHub](https://github.com/vaibhav-vai/Blog_Website)! Your support helps keep the project alive.
