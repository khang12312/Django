# Learning Management System (Django)

A comprehensive Learning Management System built with Django, designed to provide a seamless educational experience with integrated course management, quiz functionality, and user authentication.

## ✨ Features

### User Management
- User registration and authentication
- Personalized user dashboard
- Profile management

### Course Management
- Browse available courses
- Course enrollment system
- Course content delivery
- Progress tracking

### Quiz System
- Interactive quiz interface
- Multiple question types
- Automated grading
- Results tracking and analysis

## 🛠️ Tech Stack

- **Backend Framework:** Django 4.x
- **Database:** SQLite
- **Frontend:** HTML5, CSS3
- **Authentication:** Django Authentication System

## 📁 Project Structure

```
Django/
├── accounts/            # User authentication and management
├── courses/            # Course-related functionality
├── quiz/              # Quiz system
├── myproject/         # Project configuration
├── manage.py         # Django management script
└── requirements.txt  # Project dependencies
```

## 🚀 Getting Started

### Prerequisites
- Python 3.12 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd Django
   ```

2. Create and activate virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Create a superuser (admin):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Access the application:
   - Main site: http://localhost:8000
   - Admin panel: http://localhost:8000/admin

## 🔧 Configuration

1. Database configuration in `myproject/settings.py`
2. Static files configuration
3. Email settings (if applicable)

## 🔐 Security Features

- CSRF protection
- Password hashing
- User session management
- Form validation

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Irfan Khan**

- GitHub: [Your GitHub Profile]
- LinkedIn: [Your LinkedIn Profile]
- Email: khangdevelopers@gmail.com

## 📞 Support

For support, email khangdevelopers@gmail.com or create an issue in the repository.

---
⭐️ If you found this project helpful, please give it a star!
