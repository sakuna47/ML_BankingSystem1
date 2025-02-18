# Bank Marketing Campaign Prediction

## Overview
This project utilizes machine learning models to predict customer responses in a bank marketing campaign. The dataset used is the `bank-additional-full.csv`, which contains details of customers contacted for term deposits. The goal is to classify whether a customer will subscribe to a term deposit.

## Features & Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Standardizing numerical features
   - Addressing class imbalance using SMOTE

2. **Exploratory Data Analysis (EDA)**
   - Checking dataset structure
   - Visualizing class distribution

3. **Model Training & Evaluation**
   - **Random Forest Classifier** (Hyperparameter tuning with GridSearchCV)
   - **Neural Network (MLPClassifier)**
   - Performance metrics: Accuracy, Precision, Recall, F1-score
   - Confusion matrix visualization
   - ROC Curve and AUC Score

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- Google Colab (for execution)

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/sakuna47/ML_BankingSystem1
.git
   cd bank-marketing-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Mount Google Drive (if using Colab) and update dataset path:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   file_path = '/content/drive/My Drive/bank-additional-full.csv'
   ```

4. Run the script:
   ```bash
   python main.py
   ```

## Results & Analysis
- The Random Forest model achieved **X% accuracy**.
- The Neural Network model achieved **Y% accuracy**.
- The comparison shows that **[your key insights here]**.

## Future Improvements
- Experiment with additional feature engineering.
- Try other classifiers like XGBoost or SVM.
- Optimize the neural network architecture.

## License
This project is open-source and available under the [MIT License](LICENSE).

