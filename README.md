# Eat Healthy - Smart Nutrition Management System

A Django-based web application for managing and tracking your daily nutrition intake. This application helps users maintain a healthy diet by providing personalized nutrition recommendations and meal planning features.

## 🎯 Features

- **User Authentication**: Secure registration and login system
- **Meal Logging**: Log daily meals and snacks with nutritional information
- **Nutrition Tracking**: Real-time tracking of calories, macronutrients (proteins, carbs, fats), and micronutrients
- **Personalized Recommendations**: Get diet recommendations based on your health goals
- **Meal Database**: Access to a comprehensive database of food items and their nutritional values
- **Progress Visualization**: Charts and graphs to track your nutritional progress over time
- **Dietary Plans**: Choose from pre-built healthy eating plans

## 🛠️ Technology Stack

- **Backend**: Django, Python
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite/PostgreSQL
- **Libraries**: Render (for deployment)

## 📋 Installation & Setup

### Prerequisites
- Python 3.8+
- pip
- Virtual Environment

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/Vallabh409/eat-healthy.git
cd eat-healthy
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Create a superuser:
```bash
python manage.py createsuperuser
```

6. Start the development server:
```bash
python manage.py runserver
```

7. Access the application at `http://localhost:8000`

## 📁 Project Structure

```
eat-healthy/
├── backend/                 # Django backend
│   ├── settings.py         # Django settings
│   ├── urls.py            # URL configuration
│   └── wsgi.py            # WSGI configuration
├── app/                    # Django app
├── templates/             # HTML templates
├── static/               # CSS, JavaScript, images
├── requirements.txt      # Python dependencies
└── manage.py            # Django management script
```

## 💡 Usage

1. Create an account and log in
2. Set your health goals and dietary preferences
3. Add meals to your daily log
4. View nutritional summaries and recommendations
5. Track your progress over time

## 🚀 Deployment

This project is configured for deployment on Render:

1. Push your code to GitHub
2. Connect your repository to Render
3. Deploy following Render's Django deployment guide

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Vallabh Bashyakarla**
- GitHub: [@Vallabh409](https://github.com/Vallabh409)
- LinkedIn: [Vallabh Bashyakarla](https://www.linkedin.com/in/vallabh-bashyakarla)

## 📧 Contact

For questions or suggestions, feel free to reach out!

---

**Made with ❤️ for healthy living**
