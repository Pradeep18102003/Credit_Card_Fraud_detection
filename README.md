# Credit Card Fraud Detection

## 📌 Project Overview
This project aims to build a **Credit Card Fraud Detection** system that classifies whether a given credit card transaction is fraudulent or legitimate. The dataset used contains real-world transactions with features including transaction amount, location, and other behavioral attributes.

## 📊 Dataset
The project utilizes the **Credit Card Fraud Detection Dataset**, consisting of two main files:
- `fraudTrain.csv`: Training data
- `fraudTest.csv`: Testing data

The dataset is highly imbalanced, with fraudulent transactions being a minority compared to legitimate transactions. Appropriate data preprocessing techniques have been used to address this imbalance.

## 📂 Project Structure
The project is organized as follows:

```
.
├── notebook
│    └── credit-card-fraud-detection.ipynb  # Main Jupyter Notebook (contains the entire code)
│
└── src
     ├── components
     │      ├── __init__.py
     │      ├── data_ingestion.py          # Empty due to computation limitations
     │      ├── data_transformation.py     # Empty due to computation limitations
     │      └── model_trainer.py           # Empty due to computation limitations
     │
     ├── pipeline
     │      └── __init__.py
     │
     ├── exception.py                      # Custom exception handling
     ├── logger.py                         # Logging module for debugging
     ├── utils.py                          # Utility functions
     └── .gitignore

├── pyproject.toml
├── requirements.txt                       # Python dependencies
└── README.md
```

### 💻 Note:
The **entire code** for data ingestion, transformation, and model training is contained within the Jupyter Notebook (`credit-card-fraud-detection.ipynb`).
The corresponding files under `src/components` are currently **empty due to hardware computation limitations**.

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
Due to **hardware limitations**, only the Jupyter Notebook is fully implemented while the modular Python scripts (`src/components`) remain empty. The project is structured to be easily scalable on higher-compute environments (e.g., Google Colab, Kaggle Notebooks).

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
   jupyter notebook notebook/credit-card-fraud-detection.ipynb
   ```

## 📌 Future Improvements
- Implement deep learning models (e.g., LSTM for sequential data).
- Optimize feature selection and hyperparameter tuning.
- Explore deployment on cloud platforms.

## 📧 Contact
If you have any questions or feedback, feel free to reach out via email: pradeep18kumar10@gmail.com linkedin: https://www.linkedin.com/in/pradeep-kumar-bba090320/.
