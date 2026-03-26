🚢 Titanic Survival Prediction
---

🚀 Machine Learning Project | Classification + Feature Engineering + Model Comparison
🌟 Internship Project at Arch Technologies ✅
  
  ---

📌 Task Description
---
Build a predictive model to classify passenger survival on the Titanic based on historical data.

- Perform data cleaning and preprocessing (handling missing values, dropping irrelevant features)
- Conduct Exploratory Data Analysis (EDA) to identify key survival patterns
- Create new features (Sex_Pclass, FamilySize, FarePerPerson, IsAlone)
- Apply feature scaling for model optimization
- Train and compare multiple models (Logistic Regression, Random Forest, SVM, KNN, Decision Tree)
- Perform hyperparameter tuning using GridSearchCV
- Evaluate model performance using Accuracy & ROC-AUC
 ---
 
📂 Dataset
---
- Source: Titanic Dataset (Kaggle)
- Features: Passenger information (Pclass, Sex, Age, Fare, SibSp, Parch, Embarked, etc.)
- Target Variable: Survival (0 = Not Survived, 1 = Survived)
 ---
 
🧰 Tools & Libraries Used
---
- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib / Seaborn
 ---

🔄 Project Workflow
---

✅ 1. Data Cleaning

Dropped irrelevant features (PassengerId, Name, Ticket, Cabin)
Handled missing values:
- Age → Median
- Fare → Median
- Embarked → Mode

📊 2. Exploratory Data Analysis (EDA)

- Analyzed survival distribution
- Identified key patterns (Gender, Pclass, Fare)
- Visualized relationships between features and survival
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/d708b2c3-356d-4bbc-8b2d-6d280c0c071b" />

⚙️ 3. Feature Engineering

Created new features:
- Sex_Pclass
- FamilySize
- IsAlone
- FarePerPerson
- Encoding categorical variables
- Feature selection based on importance

📏 4. Feature Scaling

- Applied StandardScaler for models sensitive to scale
- Ensured consistent data distribution

🤖 5. Modeling

- Trained multiple models:
  
      - Logistic Regression
      - Random Forest
      - SVM
      - KNN
      - Decision Tree
- Evaluated using Accuracy & ROC-AUC

🔍 6. Hyperparameter Tuning
- Applied GridSearchCV for optimization
- Improved model performance and generalization

🏆 7. Best Model
- Logistic Regression selected as the best model
- Achieved balanced performance with strong generalization
- Interpretable and effective for binary classification
 ---

📊 Business Insight
---
 
- Survival is strongly influenced by gender and social class
- Female passengers had significantly higher survival rates
- Higher-class passengers had better access to safety resources
- Survival outcomes were driven by priority and accessibility, not randomness
 ---
 
📚 Concepts Covered
---

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Classification Modeling
- Model Evaluation (Accuracy, ROC-AUC)
- Hyperparameter Tuning
