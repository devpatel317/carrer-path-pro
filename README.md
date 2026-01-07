# 🎓 Career Path Pro - Student Placement Prediction System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=flat-square)](https://www.python.org/)
[![Next.js](https://img.shields.io/badge/Next.js-16.1+-black.svg?style=flat-square)](https://nextjs.org/)
[![Machine Learning](https://img.shields.io/badge/ML-Predictive%20Analytics-green.svg?style=flat-square)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-In%20Development-yellow.svg?style=flat-square)](https://github.com/devpatel317/carrer-path-pro)
[![License](https://img.shields.io/badge/License-MIT-purple.svg?style=flat-square)](LICENSE)

## 📋 About The Project

**Career Path Pro** is an intelligent ML-powered web application that predicts whether a college student will secure placement in their dream organization. The system analyzes student profiles across multiple dimensions - academics, professional development, and soft skills - to deliver accurate placement predictions.

### Why This Project?
- **Real-world Problem**: Placement prediction helps students identify skill gaps
- **Data-Driven Approach**: Uses statistical analysis and machine learning
- **Full-Stack Solution**: Combines ML backend with modern web frontend
- **Educational Value**: Demonstrates complete ML pipeline from EDA to deployment

---

## ✨ Key Features

✅ **ML-Powered Prediction Engine** - Analyzes comprehensive student profiles  
✅ **Exploratory Data Analysis** - Statistical insights with visualizations  
✅ **Interactive Web Interface** - User-friendly Next.js frontend  
✅ **Multi-Dimensional Assessment** - Evaluates academics, skills, and experience  
✅ **Clean Dataset** - 10,000 student records with zero missing values  
✅ **Production-Ready** - Docker-ready, scalable architecture  

---

## 📊 Dataset Overview

**Total Records**: 10,000 students  
**Features**: 9 input features + 1 target variable  
**Data Quality**: 100% complete (no missing values)

### Features Description

| Feature | Type | Range | Description |
|---------|------|-------|-------------|
| **College_ID** | Categorical | - | Unique college identifier |
| **IQ** | Numerical | 41-158 | Student intelligence quotient score |
| **Prev_Sem_Result** | Numerical | 5.0-10.0 | Previous semester GPA |
| **CGPA** | Numerical | 4.54-10.46 | Cumulative Grade Point Average |
| **Academic_Performance** | Numerical | 1-10 | Overall academic rating |
| **Internship_Experience** | Categorical | Yes/No | Has completed internship |
| **Extra_Curricular_Score** | Numerical | 0-10 | Extracurricular activities rating |
| **Communication_Skills** | Numerical | 1-10 | Communication proficiency |
| **Projects_Completed** | Numerical | 0-5 | Number of completed projects |
| **Placement** | Categorical | Yes/No | **TARGET: Placement status** |

### Key Statistics
- **Mean IQ**: 99.47
- **Average CGPA**: 7.53
- **Median Projects**: 3
- **Communication Skills Mean**: 5.56

---

## 🏗️ Project Architecture

```
carrer-path-pro/
│
├── 📁 app/                               # Next.js Frontend Application
│   ├── page.tsx                         # Main page component
│   ├── layout.tsx                       # Root layout
│   └── ...                              # Additional pages & components
│
├── 📁 ml_engine/                        # ML Backend & Data Science
│   ├── 📁 notebooks/
│   │   ├── eda_analysis.ipynb          # Exploratory Data Analysis
│   │   ├── model_training.ipynb        # Model development (upcoming)
│   │   └── evaluation.ipynb            # Model evaluation (upcoming)
│   ├── 📁 data/
│   │   └── college_student_placement_dataset.csv
│   ├── requirements.txt                # Python dependencies
│   └── ...                             # ML models & utilities
│
├── 📁 prisma/                          # Database ORM & Schema
│   ├── schema.prisma                   # Database schema
│   └── ...
│
├── 📁 public/                          # Static Assets
│
├── Configuration Files
│   ├── package.json                    # Node.js dependencies
│   ├── next.config.ts                  # Next.js config
│   ├── tsconfig.json                   # TypeScript config
│   ├── postcss.config.mjs              # PostCSS config
│   ├── eslint.config.mjs               # ESLint rules
│   └── .gitignore
│
└── README.md                           # This file
```

---

## 🛠️ Tech Stack

### **Frontend**
```
Next.js 16.1+          - React framework for production
React 19.2+            - UI library
TypeScript             - Type-safe JavaScript
Tailwind CSS           - Utility-first CSS framework
PostCSS                - CSS transformations
```

### **Backend & Machine Learning**
```
Python 3.8+            - ML development
Pandas                 - Data manipulation
NumPy                  - Numerical computing
Scikit-learn           - ML algorithms (upcoming)
Matplotlib/Seaborn     - Data visualization
Jupyter                - Interactive notebooks
```

### **Database & ORM**
```
Prisma 7.2+            - Modern ORM
PostgreSQL             - Recommended database
```

### **Development Tools**
```
Git                    - Version control
npm/Node.js            - Package management
ESLint                 - Code linting
```

---

## 🚀 Getting Started

### Prerequisites
- **Node.js** 16.1+ (with npm)
- **Python** 3.8+
- **Git**

### Installation Steps

#### **Step 1: Clone Repository**
```bash
git clone https://github.com/devpatel317/carrer-path-pro.git
cd carrer-path-pro
```

#### **Step 2: Frontend Setup**
```bash
# Install Node dependencies
npm install

# Start development server
npm run dev
```
Open http://localhost:3000 in your browser

#### **Step 3: Backend ML Setup**
```bash
# Navigate to ML engine
cd ml_engine

# Create Python virtual environment (recommended)
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install Python dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook notebooks/eda_analysis.ipynb
```

---

## 📈 Project Progress

### ✅ **Phase 1: Completed**
- [x] Project initialization (Next.js + Python)
- [x] Dataset integration (10,000 records)
- [x] Exploratory Data Analysis
  - Data loading and profiling
  - Missing value analysis (✓ Zero null values)
  - Statistical summaries
  - Distribution analysis (IQ, CGPA, Prev_Sem_Result)
  - Correlation analysis & heatmap
  - Feature relationship visualizations
  - Placement vs key metrics analysis

### 🔄 **Phase 2: In Progress**
- [ ] Machine Learning Model Development
  - Classification algorithms (Logistic Regression, Random Forest, XGBoost, SVM)
  - Train/test split and cross-validation
  - Hyperparameter tuning
  - Model evaluation metrics (Accuracy, Precision, Recall, F1-Score, AUC-ROC)
- [ ] Backend API Development
  - Flask/FastAPI REST API
  - Model deployment
  - Prediction endpoints
- [ ] Frontend-Backend Integration

### 📋 **Phase 3: Planned**
- [ ] Advanced visualizations
- [ ] User authentication & database integration
- [ ] Prediction explanation (SHAP values)
- [ ] Docker containerization
- [ ] Deployment (Vercel/Railway)

---

## 📊 Exploratory Data Analysis Insights

### Data Quality ✓
- **Complete Dataset**: 0 null values across all 10 columns
- **Balanced Features**: Good distribution of numerical and categorical data

### Key Correlations
```
Strong Correlation:
- Prev_Sem_Result ↔ CGPA: 0.98 (highly correlated)

Weak Correlations:
- Other features show independence, good for model training
```

### Important Findings
1. **CGPA Impact**: Strong relationship with placement outcomes
2. **Internship Experience**: Significant factor in placement success
3. **Communication Skills**: Important soft skill predictor
4. **Projects Completed**: Positive correlation with placement
5. **Feature Independence**: Multiple independent features provide diverse signals

### Visualizations Generated
- IQ Distribution Analysis
- CGPA Distribution Analysis  
- Previous Semester Results Distribution
- Placement vs CGPA Box Plots
- Internship Experience vs Placement Count Plots
- Communication Skills vs Placement Analysis
- Projects Completed vs Placement Correlation
- CGPA vs IQ Scatter Plots
- Pairplot Analysis (CGPA, IQ, Academic Performance by Placement)

---

## 🔌 API Specification (Upcoming)

Once ML model is deployed, use this endpoint:

```bash
POST /api/predict
Content-Type: application/json
Authorization: Bearer YOUR_TOKEN

{
  "iq": 105,
  "prev_sem_result": 7.5,
  "cgpa": 7.6,
  "academic_performance": 7,
  "internship_experience": true,
  "extra_curricular_score": 6,
  "communication_skills": 7,
  "projects_completed": 3
}
```

**Success Response (200)**
```json
{
  "placement": "Yes",
  "confidence": 0.87,
  "probability": 0.87,
  "key_factors": {
    "cgpa": "Strong positive",
    "internship_experience": "Strong positive",
    "communication_skills": "Moderate positive"
  },
  "recommendation": "Strong candidate for placement"
}
```

---

## 📚 Available Commands

```bash
# Frontend Development
npm run dev           # Start dev server (localhost:3000)
npm run build         # Build for production
npm run start         # Start production server
npm run lint          # Run ESLint

# ML Development
jupyter notebook      # Start Jupyter notebook server
python script.py      # Run Python scripts
```

---

## 📖 Resources & References

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [Scikit-learn Guide](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [NumPy Guides](https://numpy.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Prisma ORM](https://www.prisma.io/)

---

## 🤝 Contributing

We welcome contributions! Here's how:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Contribution Guidelines
- Follow existing code style
- Add comments for complex logic
- Update documentation
- Test your changes

---

## 📝 License

This project is open source and available under the **MIT License** - see the LICENSE file for details.

---

## 👨‍💻 Author

**Dev Patel**  
GitHub: [@devpatel317](https://github.com/devpatel317)  
Location: Ahmedabad, Gujarat, India

---

## 🎯 Roadmap

| Phase | Timeline | Status |
|-------|----------|--------|
| EDA & Analysis | Jan 2026 | ✅ Complete |
| Model Development | Jan-Feb 2026 | 🔄 In Progress |
| API Development | Feb 2026 | ⏳ Planned |
| Frontend Integration | Feb-Mar 2026 | ⏳ Planned |
| Deployment | Mar 2026 | ⏳ Planned |

---

## 💡 Future Enhancements

- [ ] Multiple ML models comparison
- [ ] Feature importance visualization
- [ ] Student recommendations based on predictions
- [ ] Batch prediction capability
- [ ] Model versioning and tracking
- [ ] Real-time predictions
- [ ] Mobile app version
- [ ] Analytics dashboard

---

## ⚠️ Disclaimer

This is an **educational project** demonstrating:
- Machine Learning workflows
- Data analysis & visualization
- Full-stack development
- Modern web technologies

Predictions are for educational purposes and should not be solely relied upon for real placement decisions.

---

## 📞 Support

For issues, questions, or suggestions:
1. Open an issue on [GitHub Issues](https://github.com/devpatel317/carrer-path-pro/issues)
2. Include clear description and reproduction steps
3. Attach relevant screenshots or logs

---

**Last Updated**: January 7, 2026  
**Version**: 1.0.0 (In Development)

⭐ If you find this project helpful, please give it a star!
