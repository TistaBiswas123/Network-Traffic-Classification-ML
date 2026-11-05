# Network Protocol Classification Using Machine Learning

Project Overview

This project focuses on identifying and classifying different network protocols using Machine Learning techniques. It analyzes network traffic data and applies classification algorithms to recognize the protocols based on their network traffic characteristics.

The main objective is to explore how Machine Learning can be used for network traffic classification and compare the performance of different classification algorithms.

Dataset Description

This project uses network traffic data collected from YouTube Live traffic. The dataset contains network traffic features used for data analysis, preprocessing, model training, and evaluation.

The dataset was merged and processed before applying Machine Learning algorithms. It is not included in this GitHub repository due to its size.

Project Workflow

The project follows these major steps:

1. Dataset Collection and Merging: Combining network traffic CSV files into a single dataset.
2. Data Preprocessing: Handling missing values, checking duplicates, and preparing the data for analysis.
3. Exploratory Data Analysis (EDA): Analyzing network traffic patterns through statistical summaries and visualizations.
4. Feature Preparation: Selecting relevant features, encoding target labels, and scaling numerical data.
5. Model Training: Training multiple Machine Learning classification algorithms.
6. Model Evaluation: Comparing model performance using accuracy, precision, recall, F1-score, and confusion matrices.
7. Prediction: Testing the trained model on sample network traffic data.

Machine Learning Algorithms Used

The following four classification algorithms are implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier

Model Performance

The following accuracy scores were obtained during model evaluation:

Algorithm  | Accuracy


Logistic Regression| 91.55%,
K-Nearest Neighbors (KNN)| 99.15%,
Decision Tree| 98.81%,
Random Forest| 99.48%.

Best Accuracy: Random Forest Classifier – 99.48%.

Note: Accuracy alone does not represent performance across all protocol classes. Precision, recall, F1-score, and class imbalance are also considered during evaluation.

Tools and Technologies

- Programming Language: Python
- Development Environment: Google Colab / Jupyter Notebook
- Data Processing: Pandas, NumPy
- Machine Learning: Scikit-learn
- Data Visualization: Matplotlib, Seaborn

Project Files

- "Network_Traffic_Classification_ML.ipynb" – Contains the complete project implementation, data preprocessing, exploratory data analysis, model training, evaluation, and prediction.
- "README.md" – Provides an overview of the project, methodology, algorithms, and results.

Limitations

- The dataset contains an imbalance in the distribution of network protocol classes.
- Some minority protocol classes have lower classification performance.
- The model's performance may vary depending on the dataset and network traffic characteristics.

Future Scope

- Improving classification performance for minority protocol classes.
- Exploring advanced Machine Learning and Deep Learning algorithms.
- Testing the model on additional network traffic datasets.
- Developing a real-time network traffic classification system.

Conclusion

This project demonstrates the application of four Machine Learning algorithms for network protocol classification using YouTube Live network traffic data. Among the implemented models, Random Forest achieved the highest observed accuracy of 99.48%.

The project provides practical experience in data preprocessing, exploratory data analysis, Machine Learning model development, performance evaluation, and network traffic classification.

Author

Tista Biswas

BCA Student | Brainware University

GitHub: "TistaBiswas123" (https://github.com/TistaBiswas123)
