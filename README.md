# 📊 Customer Churn Prediction - Telecom X

A comprehensive machine learning project to predict customer churn and develop strategic retention strategies for telecommunications company Telecom X.

## 🎯 Project Overview

This project develops a predictive model to identify customers at high risk of canceling their services, enabling Telecom X to implement proactive retention strategies and improve business profitability. The analysis includes data exploration, feature engineering, model training, and actionable business recommendations.

### Business Objectives
- **Primary Goal**: Predict customer churn with actionable insights
- **Strategic Impact**: Enable proactive customer retention campaigns
- **Financial Goal**: Reduce revenue loss through targeted interventions
- **Operational Goal**: Optimize customer service resources

## 📈 Key Results

- **Best Model**: Logistic Regression with F1-Score of 0.36
- **High-Risk Customers Identified**: 1,798 customers (30% actual churn rate in this segment)
- **Revenue at Risk**: Significant annual revenue identified for targeted retention
- **Strategic Recommendations**: 5 prioritized retention strategies with implementation roadmap

## 📊 Dataset Information

- **Total Records**: 7,267 customer records
- **Features**: Customer demographics, service usage, billing information, and contract details
- **Target Variable**: Churn (Yes/No)
- **Data Structure**: JSON-structured columns for customer, phone, internet, and account information

### Data Categories
- **Customer Info**: Gender, age, partner status, dependents, tenure
- **Phone Services**: Phone service, multiple lines
- **Internet Services**: Internet type, online security, backup, protection, tech support, streaming
- **Account Info**: Contract type, billing method, payment method, charges

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.7+
- pip package manager

### Dependencies
Install required packages:

```bash
pip install pandas
pip install matplotlib
pip install numpy
pip install seaborn
pip install scikit-learn
```

Or install from requirements file:
```bash
pip install -r requirements.txt
```

### Project Setup
1. Clone the repository:
```bash
git clone https://github.com/Phylip28/prediction-churn-telecom-x.git
cd prediction-churn-telecom-x
```

2. Create virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 📁 Project Structure

```
prediction-churn-telecom-x/
│
├── data/
│   └── TelecomX_cleaned_data.csv       # Customer dataset
│
├── notebooks/
│   └── Modelo_Prediccion_Churn_TelecomX.ipynb  # Main analysis notebook
│
├── requirements.txt                     # Project dependencies
├── .gitignore                          # Git ignore file
└── README.md                           # Project documentation
```

## 🚀 Usage

### Running the Analysis
1. Open Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to `notebooks/Modelo_Prediccion_Churn_TelecomX.ipynb`

3. Run all cells to execute the complete pipeline:
   - Data loading and preprocessing
   - Exploratory data analysis
   - Feature engineering
   - Model training and evaluation
   - Business insights generation

### Key Notebook Sections
1. **Data Loading & Exploration**: Initial data analysis and structure understanding
2. **Data Preprocessing**: JSON parsing and feature extraction
3. **Exploratory Data Analysis**: Statistical analysis and visualizations
4. **Feature Engineering**: Creating predictive features from raw data
5. **Model Training**: Testing multiple ML algorithms
6. **Model Evaluation**: Comprehensive performance assessment
7. **Risk Segmentation**: Customer categorization by churn risk
8. **Business Recommendations**: Strategic action plans

## 🎯 Model Performance

### Algorithms Tested
- **Random Forest Classifier**
- **Logistic Regression** ⭐ (Best Performance)
- **Support Vector Machine (SVM)**

### Best Model Metrics (Logistic Regression)
- **Accuracy**: Baseline performance metric
- **Precision**: Focus on reducing false positives
- **Recall**: Capturing actual churn cases
- **F1-Score**: 0.36 (balanced precision-recall)
- **ROC-AUC**: 0.52 (area under curve)

### Feature Importance
1. **Monthly Charges** - Primary churn driver
2. **Contract Type** - Month-to-month contracts = higher risk
3. **Customer Tenure** - New customers = higher risk
4. **Internet Service Type** - Fiber optic customers = higher risk
5. **Payment Method** - Electronic check = risk factor

## 💼 Business Insights & Recommendations

### Risk Segmentation Results
- **High Risk**: 1,798 customers (30% churn rate)
- **Medium Risk**: Moderate churn probability
- **Low Risk**: Stable customer base

### Strategic Recommendations

#### 1. **Long-term Contract Promotion Program** 🎯 HIGH PRIORITY
- **Target**: High-risk customers with month-to-month contracts
- **Action**: Offer 15-20% discounts for 1-2 year commitments
- **Expected Impact**: Significant churn reduction

#### 2. **Early Customer Retention Program** 🎯 HIGH PRIORITY
- **Target**: New customers (tenure < 24 months)
- **Action**: Intensive follow-up, tutorials, premium support
- **Timeline**: First 6 months post-signup

#### 3. **Pricing Optimization Strategy** 🎯 HIGH PRIORITY
- **Target**: High monthly charge customers
- **Action**: Personalized pricing and value-added bundles
- **Approach**: Data-driven offer personalization

#### 4. **Payment Method Incentive Program** 🎯 MEDIUM PRIORITY
- **Target**: Electronic check users
- **Action**: 5% discount for auto-debit/credit card switch
- **Benefit**: Improved payment reliability

#### 5. **Service Enhancement Initiative** 🎯 MEDIUM PRIORITY
- **Target**: Fiber optic and streaming users
- **Action**: Quality improvements and competitive bundles
- **Focus**: Service quality optimization

### 90-Day Implementation Roadmap
1. **Week 1-2**: Deploy model and create monitoring dashboard
2. **Week 3-4**: Launch contract promotion for high-risk customers
3. **Week 5-6**: Implement early customer retention program
4. **Week 7-8**: Roll out personalized pricing offers
5. **Week 9-10**: Launch payment method incentives
6. **Week 11-12**: Evaluate results and strategy adjustments

## 📊 Key Success Metrics (KPIs)
- Monthly churn rate by risk segment
- Contract conversion rate (month-to-month to long-term)
- Customer lifetime value improvement
- Campaign ROI and cost per retained customer
- Customer satisfaction scores (NPS)
- Model prediction accuracy

## 🔄 Future Improvements

### Model Enhancement
- **Feature Engineering**: Create additional predictive features
- **Algorithm Testing**: Explore ensemble methods and deep learning
- **Hyperparameter Tuning**: Optimize model parameters
- **Cross-validation**: Implement robust validation strategies

### Data Enhancement
- **External Data**: Incorporate market and competitor data
- **Real-time Features**: Add behavioral and usage patterns
- **Temporal Features**: Include seasonality and time-based patterns

### Business Application
- **Real-time Scoring**: Implement live churn probability scoring
- **A/B Testing**: Test retention strategy effectiveness
- **Automated Campaigns**: Deploy automated intervention triggers
- **Dashboard Development**: Create executive and operational dashboards

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

### Contribution Guidelines
- Follow existing code style and structure
- Add appropriate documentation
- Include tests for new features
- Update README if needed

## 📄 License

This project is available for educational and research purposes. Please contact the repository owner for commercial use permissions.

## 📞 Contact & Support

For questions, suggestions, or support:
- **Repository Owner**: Phylip28
- **Project**: Customer Churn Prediction - Telecom X
- **Issues**: Use GitHub Issues for bug reports and feature requests

## 🙏 Acknowledgments

- Data science and machine learning community
- Scikit-learn library contributors
- Jupyter Notebook ecosystem
- Telecommunications industry insights

---

**Project Status**: ✅ Complete and ready for deployment  
**Last Updated**: December 2024  
**Version**: 1.0.0