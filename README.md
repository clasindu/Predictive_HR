# PredictiveHR

## 🎯 Overview

PredictiveHR is an intelligent Employee Churn Prediction System developed to help organizations identify employees who are at risk of leaving the company. The system utilizes Machine Learning techniques to analyze employee-related factors and generate accurate churn predictions, enabling HR departments to make informed decisions and improve employee retention.

This project was developed by **Chamath Lasindu Rajapaksha** as a Software Engineering and Machine Learning project.

## 🔗 Repository

Repository: https://github.com/clasindu/Predictive_HR

## ✨ Features

- Employee Churn Prediction using Machine Learning
- Employee Risk Analysis Dashboard
- User-friendly and Responsive Interface
- Real-time Prediction Results
- Secure Data Management
- RESTful API Integration
- Employee Data Visualization and Analytics
- PostgreSQL Database Integration

## 🛠️ Technology Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- JavaScript

### Backend
- Python
- FastAPI
- Uvicorn

### Database
- PostgreSQL

### Machine Learning
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Matplotlib

## 🚀 System Architecture

```text
React Frontend
       │
       ▼
FastAPI Backend
       │
       ▼
Machine Learning Model
       │
       ▼
PostgreSQL Database
```

## 📊 Prediction Factors

The model analyzes multiple employee-related attributes including:

- Age
- Gender
- Department
- Job Role
- Monthly Income
- Years at Company
- Work-Life Balance
- Job Satisfaction
- Distance from Home
- Number of Promotions
- Overtime Status
- Training Hours
- Performance Rating

## 🚀 Installation Guide

### Prerequisites

- Node.js 18+
- Python 3.10+
- PostgreSQL
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/clasindu/Predictive_HR.git
cd Predictive_HR
```

### 2. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

### 3. Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Backend runs on:

```text
http://localhost:8000
```

### 4. Database Configuration

Create a `.env` file inside the backend directory.

```env
DB_HOST=localhost
DB_PORT=5432
DB_NAME=predictivehr
DB_USER=postgres
DB_PASSWORD=your_password

SECRET_KEY=your_secret_key
```

## 📁 Project Structure

```text
Predictive_HR/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── routers/
│   │   ├── models/
│   │   ├── services/
│   │   └── database/
│   ├── requirements.txt
│   └── .env
│
├── ml_models/
│   ├── training_scripts/
│   ├── datasets/
│   └── trained_models/
│
├── README.md
└── LICENSE
```

## 📈 Machine Learning Model

The system applies Machine Learning algorithms to predict employee churn based on historical employee records.

### Libraries Used

- Scikit-learn
- Pandas
- NumPy
- XGBoost
- Matplotlib

### Model Objective

Predict whether an employee is likely to:

- Stay in the organization
- Leave the organization

The prediction helps HR managers identify high-risk employees and take proactive retention measures.

## 🔧 How to Use

1. Launch the frontend and backend services.
2. Enter employee details through the web interface.
3. Submit the form for prediction.
4. View employee churn probability and prediction results.
5. Analyze employee insights using the dashboard.

## 🎓 Academic Information

**University:** Sri Lanka Technological Campus (SLTC) Research University

**Faculty:** Faculty of Computing and Information Technology (FoIT)

**Degree Program:** BSc (Hons) Software Engineering

## 👨‍💻 Developer

**Chamath Lasindu Rajapaksha**

Software Engineering Undergraduate

GitHub: https://github.com/clasindu


## 🔮 Future Improvements

- Advanced Deep Learning Models
- Real-time Prediction API
- Interactive Analytics Dashboard
- Employee Retention Recommendations
- Explainable AI (XAI) Features
- Email Notification System
- Cloud Deployment
- Mobile Application Support

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Create a Pull Request

## 📝 License

This project is licensed under the MIT License.

## ⭐ Acknowledgements

Special thanks to the Faculty of Computing and Information Technology and all lecturers who provided guidance throughout the project development process.

---

**Developed by Chamath Lasindu Rajapaksha**
