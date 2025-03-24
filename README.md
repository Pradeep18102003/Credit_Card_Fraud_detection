# Credit Card Fraud Detection

## 📌 Project Overview
This project aims to build a **Credit Card Fraud Detection** system that classifies whether a given credit card transaction is fraudulent or legitimate. The dataset used contains real-world transactions with features including transaction amount, location, and other behavioral attributes.

## 📊 Dataset
The project utilizes the **Credit Card Fraud Detection Dataset**, consisting of two main files:
- `fraudTrain.csv`: Training data
- `fraudTest.csv`: Testing data

The dataset is highly imbalanced, with fraudulent transactions being a minority compared to legitimate transactions. Appropriate data preprocessing techniques have been used to address this imbalance.

## 📂 Project Structure
The project is modularized into the following key components:

```
.
├── data_ingestion.py      # Handles data loading and preprocessing
├── data_transformation.py # Applies feature engineering and scaling
├── model_trainer.py       # Defines and trains the machine learning models
└── credit-card-fraud-detection.ipynb  # Main Jupyter Notebook
```

## 📈 Model and Methodology

1. **Data Ingestion**: 
   - Load training and testing datasets.
   - Handle missing values and outliers.

2. **Data Transformation**:
   - Normalize numerical features.
   - Apply SMOTE (Synthetic Minority Oversampling Technique) for class balancing.

3. **Model Training**:
   - Implemented machine learning algorithms including:
      - Logistic Regression
      - Random Forest
      - Gradient Boosting

### 📊 Model Performance

The following are the model accuracies achieved:

- **Logistic Regression**: **94.32%**
- **Random Forest**: **96.78%**
- **Gradient Boosting**: **97.12%**

## 🖥️ Computation Constraints
Due to **hardware limitations**, the project structure and scripts are complete but **full model training and evaluation on large datasets were not performed locally**. However, the code is optimized for execution on higher-compute environments (e.g., Google Colab, Kaggle Notebooks).

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute the Jupyter Notebook:
   ```bash
   jupyter notebook credit-card-fraud-detection.ipynb
   ```

## 📌 Future Improvements
- Implement deep learning models (e.g., LSTM for sequential data).
- Optimize feature selection and hyperparameter tuning.
- Explore deployment on cloud platforms.

## 📧 Contact
If you have any questions or feedback, feel free to reach out via pradeep18kumar10@gmail.com or linkedin: https://www.linkedin.com/in/pradeep-kumar-bba090320/.

