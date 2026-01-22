# Accident Detection and Severity Prediction System


![Python](https://img.shields.io/badge/PYTHON-3776AB?style=flat-square&logo=python&logoColor=FFD43B&logoWidth=20)
![SCIKIT-LEARN](https://img.shields.io/badge/SCIKIT--LEARN-F7931E?style=flat-square&logo=scikit-learn&logoColor=white&logoWidth=20)
![XGBOOST](https://img.shields.io/badge/XGBOOST-009CDE?style=flat-square&logoColor=white&logoWidth=20)
![PANDAS](https://img.shields.io/badge/PANDAS-130654?style=flat-square&logo=pandas&logoColor=white&logoWidth=20)
![NUMPY](https://img.shields.io/badge/NUMPY-013243?style=flat-square&logo=numpy&logoColor=white&logoWidth=20)
![MATPLOTLIB](https://img.shields.io/badge/MATPLOTLIB-1F77B4?style=flat-square&logo=matplotlib&logoColor=white&logoWidth=20)
![SEABORN](https://img.shields.io/badge/SEABORN-4CB494?style=flat-square&logoColor=white&logoWidth=20)
![JUPYTER](https://img.shields.io/badge/JUPYTER-F37726?style=flat-square&logo=jupyter&logoColor=white&logoWidth=20)


A machine learning-based predictive system for classifying and forecasting traffic accident severity levels using ensemble learning algorithms like  **Random Forest** (94.55% accuracy) and **XGBoost** (84.90% accuracy). It analyzes environmental, vehicular, and demographic factors to enable data-driven emergency response planning.



## Table of Contents


- [Key Features](#key-features)
- [Datasets](#datasets)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [How to Run](#how-to-run)
- [Results](#results)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)





## Key Features

- Dual algorithm implementation (Random Forest & XGBoost)
- Multi-class accident severity classification
- Feature importance analysis
- Comprehensive evaluation metrics
- Data visualization and analysis
- Production-ready Jupyter notebooks







## Datasets

### 1. Crash Reporting Incidents Dataset
- **File**: `Crash_Reporting_-_Incidents_Data.csv`
- **Records**: 119,944 incident reports
- **Source**: Montgomery County Crash Reporting System
- **Features**: Temporal, location, environmental, incident details, driver data
- **Target**: Severity (Minor, Moderate, Severe)

### 2. RTA (Road Traffic Accident) Dataset
- **File**: `RTA Dataset.csv`
- **Records**: 12,318 accident records
- **Features**: Driver profile, vehicle details, environmental conditions, accident data
- **Target**: Accident_severity (Slight, Serious, Fatal)



## Project Structure

```
Accident_Detection/
│
├── accident_detection_RandomForest/
│   ├── RandomForest.ipynb
│   └── dataset/
│       └── Crash_Reporting_-_Incidents_Data.csv
│
├── accident_detection_XGBoost/
│   ├── XGBoost_2.ipynb
│   └── dataset/
│       └── RTA Dataset.csv
│
├── requirements.txt
└── README.md
```



## Installation & Setup

1. **Clone Repository**: `git clone https://github.com/SRIMATHI-RENGHARAJAN/AccidentNet_Severity_Prediction.git && cd AccidentNet_Severity_Prediction`
2. **Create Environment**: `python -m venv venv && source venv/bin/activate`
3. **Install Dependencies**: `pip install -r requirements.txt`



## How to Run

```bash
cd accident_detection_RandomForest && jupyter notebook RandomForest.ipynb
cd accident_detection_XGBoost && jupyter notebook XGBoost_2.ipynb
```




## Results

### Model Performance

| Metric | Random Forest | XGBoost |
|--------|---------------|---------|
| **Accuracy** | 94.55% | 84.90% |
| **Precision** | 0.95 | 0.81 |
| **Recall** | 0.98 | 0.85 |
| **F1-Score** | 0.97 | 0.80 |

### Key Findings

- Weather and road surface are strong severity predictors
- Higher severity during night hours and rush hours
- Driver age and experience influence outcomes





## Contributing

Contributions are welcome! 

1. Fork the repository
2. Create feature branch: `git checkout -b feature/YourFeature`
3. Commit: `git commit -m "Your message"`
4. Push: `git push origin feature/YourFeature`
5. Submit pull request



## Author

**SRIMATHI RENGHARAJAN**
- GitHub: https://github.com/SRIMATHI-RENGHARAJAN
- Linkedin: https://www.linkedin.com/in/srimathi-rengharajan/



## License

Use for educational and commercial purposes with proper attribution.



**Last Updated**: January 2026  
**Status**: Active Development  
**Python Version**: 3.7+

