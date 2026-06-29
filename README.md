# Comprehensive Machine Learning Lab Repository

## 📋 Overview
This repository contains a complete set of Machine Learning lab assignments covering the entire ML pipeline from basic Python libraries to advanced deep learning models. Each lab is self-contained and builds upon concepts from previous assignments, providing a structured learning path for students.

**Author:** Muhammad Hanif Khan  
**Registration Number:** 22JZELE0456  
**Institution:** University of Engineering and Technology Peshawar, Nowshera Campus

---

## 📚 Lab Contents

### Part 1: Python Libraries Foundations

#### **Lab 2.1: Introduction to NumPy**
*Fundamental array operations and numerical computing*

**Key Topics:**
- Array creation from lists and ranges
- Matrix operations and manipulation
- Indexing, slicing, and selection
- Vectorized computations
- Statistical operations
- Reshaping and stacking
- Random number generation

**Skills Gained:** Efficient numerical computing, array manipulation, vectorization

---

#### **Lab 2.2: Introduction to Pandas**
*Data manipulation and analysis with DataFrames*

**Key Topics:**
- DataFrame creation and operations
- Reading/writing CSV and Excel files
- Data exploration (head, tail, describe)
- Indexing and selection methods
- GroupBy operations for aggregation
- Data cleaning and preprocessing
- Column renaming and management

**Skills Gained:** Data wrangling, exploratory data analysis, data preprocessing

---

#### **Lab 2.3: Introduction to Matplotlib**
*Data visualization and plotting*

**Key Topics:**
- Line plots, bar charts, scatter plots
- Histograms and pie charts
- Plot customization (colors, markers, styles)
- Adding titles, labels, legends, and grids
- Multiple plots with subplots
- Layout management with tight_layout

**Skills Gained:** Data visualization, plot customization, multi-plot layouts

---

### Part 2: Data Preprocessing and Feature Engineering

#### **Lab 3.1: Handling Missing Data - AEP Dataset**
*Missing value imputation in time-series data*

**Key Topics:**
- Loading and exploring time-series data
- Identifying missing timestamps
- Removing duplicates
- Resampling data at regular intervals
- Interpolation methods for missing values
- Data quality assessment

**Dataset:** AEP Hourly Energy Consumption (2004-2018)

**Skills Gained:** Missing data handling, time-series resampling, data cleaning

---

#### **Lab 3.2: Outlier Detection - AEP Dataset**
*Identifying and handling outliers using statistical methods*

**Key Topics:**
- IQR (Interquartile Range) method
- Box plot visualization for outlier detection
- Outlier identification and removal
- Interpolation for outlier replacement
- Data normalization after outlier handling

**Skills Gained:** Statistical outlier detection, data quality improvement

---

#### **Lab 3.3: Feature Engineering - AEP Dataset**
*Creating meaningful features from raw data*

**Key Topics:**
- Adding holiday features
- Creating temporal features (hour, month, day)
- Feature extraction from datetime objects
- Cyclical encoding of time features
- Season-based feature creation
- Binary encoding for categorical features

**Skills Gained:** Feature engineering, temporal feature extraction, categorical encoding

---

#### **Lab 4.1: Feature Extraction - AEP Dataset**
*Advanced feature engineering and extraction*

**Key Topics:**
- Feature engineering for time-series
- Creating categorical features
- Holiday and weekend indicators
- Day/night cycle encoding
- Seasonal feature extraction
- Feature selection strategies

**Skills Gained:** Advanced feature engineering, feature selection, data transformation

---

#### **Lab 4.2: Correlation Analysis - AEP Dataset**
*Understanding feature relationships*

**Key Topics:**
- Pearson correlation coefficient
- Kendall rank correlation
- Spearman rank correlation
- Feature correlation with target variable
- Correlation matrix analysis
- Feature importance evaluation
- Feature selection based on correlation

**Skills Gained:** Statistical correlation analysis, feature selection, relationship understanding

---

### Part 3: Data Preprocessing for Modeling

#### **Lab 5: Data Normalization and Encoding**
*Preparing data for machine learning models*

**Key Topics:**
- MinMaxScaler normalization
- One-Hot Encoding for categorical features
- Cyclic feature generation
- Train-validation-test splitting
- Dataset preparation for modeling
- Saving preprocessed data

**Skills Gained:** Data normalization, feature encoding, dataset splitting

---

### Part 4: Linear Models and Optimization

#### **Lab 6A: Linear Regression - Ohm's Law**
*Implementing linear regression for physical relationships*

**Key Topics:**
- Linear Regression implementation
- Model training and evaluation
- MAE and RMSE computation
- Regression visualization
- Model interpretation
- Parameter analysis

**Dataset:** Synthetic Ohm's Law data (current-voltage relationship)

**Skills Gained:** Linear regression, model evaluation, physical interpretation

---

#### **Lab 6B: Gradient Descent Implementation**
*Understanding optimization algorithms*

**Key Topics:**
- Gradient Descent implementation
- Linear regression with SGD
- Loss function and gradient computation
- Normalization and rescaling
- Convergence analysis
- Learning rate tuning
- Mathematical formulation

**Skills Gained:** Optimization algorithms, gradient computation, parameter learning

---

#### **Lab 6C: Overfitting and Underfitting**
*Understanding model complexity tradeoffs*

**Key Topics:**
- Polynomial regression analysis
- Model complexity comparison
- Underfitting vs overfitting demonstration
- Bias-variance tradeoff
- Training vs testing performance
- Model selection strategies

**Dataset:** Synthetic projectile motion data

**Skills Gained:** Model selection, bias-variance analysis, complexity management

---

### Part 5: Deep Learning for Time-Series

#### **Lab 7: Image Dataset Preparation**
*Organizing data for deep learning*

**Key Topics:**
- Creating train/validation/test splits
- Organizing image datasets by class
- Folder structure creation
- Copying and organizing files
- Dataset preparation for CNN

**Dataset:** Corn Leaf Disease Dataset

**Skills Gained:** Dataset organization, folder structure creation, data preparation

---

#### **Lab 10: MLP for Time-Series Forecasting**
*Multi-layer perceptron for prediction*

**Key Topics:**
- MLP architecture design
- Time-series window creation
- Model training and validation
- Checkpoint and history management
- Forecasting error evaluation
- Model fine-tuning

**Dataset:** AEP Hourly Energy Consumption

**Skills Gained:** Neural network implementation, time-series forecasting, model checkpointing

---

#### **Lab 11: 1D CNN for Time-Series Forecasting**
*Convolutional neural networks for sequence data*

**Key Topics:**
- 1D CNN architecture
- Convolutional layer design
- Temporal feature extraction
- Model training and validation
- Checkpoint management
- Performance comparison with MLP

**Skills Gained:** CNN implementation, time-series feature extraction, model comparison

---

#### **Lab 12: LSTM for Time-Series Forecasting**
*Long Short-Term Memory networks for sequential data*

**Key Topics:**
- LSTM architecture design
- Stacked LSTM layers
- Sequential dependency learning
- Model training and validation
- Checkpoint and fine-tuning
- Forecasting performance evaluation

**Skills Gained:** LSTM implementation, sequence learning, advanced time-series forecasting

---

## 🛠️ Technical Stack

### Core Libraries
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Scikit-learn** - Machine learning models and preprocessing

### Deep Learning
- **TensorFlow/Keras** - Deep learning framework
- **LSTM** - Sequential modeling
- **CNN** - Feature extraction
- **MLP** - Neural network basics

### Utilities
- **Custom modules** (`timeseires.*`) - Time-series utilities
- **Callbacks** - Training monitoring and checkpointing

---

## 📊 Dataset Information

### AEP Hourly Dataset
- **Source:** American Electric Power
- **Type:** Time-series energy consumption data
- **Timeframe:** 2004-2018
- **Resolution:** Hourly
- **Samples:** ~121,000 hourly records
- **Features:** 21 features (temporal, seasonal, holiday indicators)

### Corn Leaf Disease Dataset
- **Source:** PlantVillage dataset
- **Classes:** Healthy, Cercospora, Common Rust, Northern Leaf Blight
- **Split:** Training (120/class), Validation (30/class), Testing (10/class)
- **Format:** JPEG images

---

## 📁 Repository Structure

```
machine-learning-repo/
│
├── 📚 Lab_2.1_22JZELE0456.ipynb          # NumPy Fundamentals
├── 📚 Lab_2.2_22JZELE0456.ipynb          # Pandas Fundamentals
├── 📚 Lab_2.3_22JZELE0456.ipynb          # Matplotlib Visualization
├── 📚 Lab_3.1_22JZELE0456.ipynb          # Missing Data Handling
├── 📚 Lab_3.2_22JZELE0456.ipynb          # Outlier Detection
├── 📚 Lab_3.3_22JZELE0456.ipynb          # Feature Engineering
├── 📚 Lab_4.1_22JZELE0456.ipynb          # Feature Extraction
├── 📚 Lab_4.2_22JZELE0456.ipynb          # Correlation Analysis
├── 📚 Lab_5_22JZELE0456.ipynb            # Data Preprocessing
├── 📚 Lab_6.A_22JZELE0456.ipynb          # Linear Regression
├── 📚 Lab_6.B_22JZELE0456.ipynb          # Gradient Descent
├── 📚 Lab_6.C_22JZELE0456.ipynb          # Overfitting/Underfitting
├── 📚 Lab_7_22JZELE0456.ipynb            # Image Dataset Prep
├── 📚 Lab_10_22JZELE0456.ipynb           # MLP Forecasting
├── 📚 Lab_11_22JZELE0456.ipynb           # 1D CNN Forecasting
├── 📚 Lab_12_22JZELE0456.ipynb           # LSTM Forecasting
│
├── 📁 data/
│   ├── 📄 AEP_hourly.csv                 # Time-series dataset
│   └── 📁 Corn/                          # Image dataset
│
├── 📁 timeseires/                        # Custom utilities
│   ├── 📄 utils/                         # Time-series utilities
│   └── 📄 callbacks/                     # Training callbacks
│
├── 📄 requirements.txt                   # Python dependencies
└── 📄 README.md                          # This file
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/muhammadhanifkhan/machine-learning-repo.git
cd machine-learning-repo
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Verify Installation
```python
import numpy as np
import pandas as pd
import tensorflow as tf
print("All libraries imported successfully!")
```

---

## 📖 Learning Path

### Beginner Level
1. Start with **Lab 2.1** (NumPy) → **Lab 2.2** (Pandas) → **Lab 2.3** (Matplotlib)
2. Understand data manipulation and visualization basics

### Intermediate Level
3. Progress to **Labs 3.1-3.3** (Data Preprocessing)
4. Learn feature engineering with **Labs 4.1-4.2**
5. Apply preprocessing in **Lab 5**

### Advanced Level
6. Understand linear models in **Labs 6A-6C**
7. Move to deep learning with **Labs 10-12**

---

## 🎯 Key Learning Outcomes

### Python Libraries Proficiency
- Master NumPy, Pandas, and Matplotlib
- Efficient data manipulation and visualization

### Data Preprocessing
- Handle missing values and outliers
- Engineer features from raw data
- Normalize and encode data

### Machine Learning
- Implement linear regression (closed-form and SGD)
- Understand overfitting and underfitting
- Evaluate model performance

### Deep Learning
- Build MLPs, CNNs, and LSTMs
- Time-series forecasting
- Model checkpointing and fine-tuning

---

## 📈 Model Performance Comparison

| Model | MAE | RMSE | MAPE | Notes |
|-------|-----|------|------|-------|
| MLP | 12,838 | 13,070 | 73.28% | Baseline model |
| 1D CNN | 1,369 | 1,407 | 8.76% | Best feature extraction |
| LSTM | 358 | 457 | 2.44% | Best sequential learning |

*Results based on AEP time-series forecasting with scaled and fine-tuned models*

---

## 🧪 Dataset Details

### AEP Features
- **Target**: `aep` - Energy consumption (MW)
- **Temporal**: hour, month, day_of_week
- **Cyclical**: sin/cos transformations
- **Categorical**: holiday, weekend
- **Seasonal**: winter, spring, summer, fall
- **Derived**: year_day, quarter

### Image Dataset Splits
```
train/
  ├── healthy/         (120 images)
  ├── Cercospora/      (40 images)
  ├── common_rust/     (40 images)
  └── northern_leaf_blight/ (40 images)

validation/
  ├── healthy/         (30 images)
  ├── Cercospora/      (10 images)
  ├── common_rust/     (10 images)
  └── northern_leaf_blight/ (10 images)

test/
  ├── healthy/         (12 images)
  ├── Cercospora/      (4 images)
  ├── common_rust/     (4 images)
  └── northern_leaf_blight/ (4 images)
```

---

## 📚 Recommended Additional Resources

### Books
- "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" - Aurélien Géron
- "Python for Data Analysis" - Wes McKinney
- "Deep Learning with Python" - François Chollet

### Online Resources
- [TensorFlow Documentation](https://www.tensorflow.org/api_docs)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/user_guide.html)
- [Keras API Reference](https://keras.io/api/)

---

## 🤝 Contributing
This repository is maintained for educational purposes. Feel free to fork and modify for your learning needs. Contributions are welcome for improvements and corrections.

## 📄 License
This project is for educational purposes only. All rights reserved.

---

## 📬 Contact
**Muhammad Hanif Khan**  
Email: hafizmuhammadhanifkhan77@gmail.com  
Institution: University of Engineering and Technology Peshawar, Nowshera Campus

---

*Last Updated: June 2026*
