🚨 Intrusion Detection using Machine Learning Techniques
This project presents an approach to Network Intrusion Detection using a variety of machine learning algorithms applied to the NSL-KDD dataset. It includes data preprocessing, model training, evaluation, and comparative analysis.

📌 Features
Exploratory Data Analysis (EDA)
Data Preprocessing and Normalization
Handling Imbalanced Data
Implementation of Multiple Classifiers:
Logistic Regression
Decision Trees
Random Forest
Support Vector Machines (SVM)
k-Nearest Neighbors (kNN)
Naive Bayes

Evaluation Metrics:
Accuracy
Precision, Recall, F1-Score
Confusion Matrix

Visualizations for better model insights

🧠 Algorithms Used
Supervised Learning techniques to classify traffic as normal or one of several types of attacks.
Comparison of models to determine best performance on detection accuracy.

📁 Dataset
NSL-KDD Dataset: A refined version of the classic KDD Cup 1999 dataset.
Contains a more balanced distribution of classes and removes duplicate entries to provide a better benchmark.

📦 Requirements
Key libraries used:
pandas, numpy
scikit-learn
matplotlib, seaborn
imbalanced-learn

📊 Results
The best performing model achieved over X% accuracy on the test dataset.
Detailed comparison is available in the notebook.

📎 Project Structure
├── Intrusion Detection using Machine Learning Techniques.ipynb
├── NSL_KDD_dataset/
│   ├── KDDTrain.txt
│   └── KDDTest.txt
├── README.md
└── requirements.txt

📚 References
NSL-KDD Dataset
Scikit-learn documentation
Imbalanced-learn documentation
