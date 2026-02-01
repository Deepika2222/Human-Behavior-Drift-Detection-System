# Human Behavior Drift Detection System (HBDDS)

A data-driven framework for modeling collective movement patterns and identifying behavioral transitions using unsupervised ML and statistical drift detection.

## Overview

The Human Behavior Drift Detection System is a full-stack application designed to monitor, analyze, and detect significant changes in collective human behavior patterns. By leveraging machine learning algorithms and statistical methods, the system identifies behavioral drifts and assesses associated risks in real-time.

## Project Structure

```
Human-Behavior-Drift-Detection-System/
├── api/                          # Django REST API
│   ├── __init__.py
│   ├── views.py                  # API view functions and classes
│   ├── urls.py                   # URL routing configuration
│   └── serializers.py            # Data serialization
├── ml/                           # Machine Learning modules
│   ├── __init__.py
│   ├── feature_engineering.py    # Feature extraction and transformation
│   ├── drift_detection.py        # Drift detection algorithms
│   ├── model.py                  # ML model definitions
│   └── risk_scoring.py           # Risk assessment logic
├── frontend/                     # React frontend application
│   └── src/
│       ├── App.jsx               # Root React component
│       ├── components/           # Reusable UI components
│       └── pages/                # Page-level components
├── data/                         # Data storage directory
│   └── README.md
├── notebooks/                    # Jupyter notebooks for analysis
│   └── README.md
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

## Features

### Backend (Django)
- RESTful API for behavior data management
- Real-time drift detection endpoints
- Risk scoring and assessment APIs
- Model training and prediction services

### Machine Learning
- Feature engineering pipeline for behavioral data
- Statistical drift detection algorithms
- Unsupervised learning for pattern recognition
- Risk quantification and alerting

### Frontend (React)
- Interactive dashboard for drift visualization
- Data upload and management interface
- Real-time alerts and notifications
- Risk assessment reporting

## Getting Started

### Prerequisites
- Python 3.8+
- Node.js 16+
- PostgreSQL (optional, for production)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Deepika2222/Human-Behavior-Drift-Detection-System.git
cd Human-Behavior-Drift-Detection-System
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Install frontend dependencies:
```bash
cd frontend
npm install
```

4. Set up the database:
```bash
python manage.py migrate
```

5. Run the development servers:

Backend:
```bash
python manage.py runserver
```

Frontend:
```bash
cd frontend
npm start
```

## Usage

1. **Data Upload**: Upload behavioral data through the web interface
2. **Feature Engineering**: Process raw data into meaningful features
3. **Drift Detection**: Run drift detection algorithms on processed data
4. **Risk Assessment**: View risk scores and severity levels
5. **Monitoring**: Set up real-time monitoring and alerts

## Technologies

### Backend
- Django 4.2+
- Django REST Framework
- PostgreSQL
- Scikit-learn
- Pandas, NumPy

### Frontend
- React 18+
- React Router
- Axios
- Chart.js / Plotly

### Machine Learning
- Scikit-learn (clustering, anomaly detection)
- Evidently (drift detection)
- Alibi-detect (statistical tests)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or feedback, please open an issue on GitHub.
