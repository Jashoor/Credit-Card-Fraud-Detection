# Credit-Card-Fraud-Detection
Overview
This repository contains Python code for performing anomaly detection using various algorithms from the scikit-learn library. The implemented algorithms include Isolation Forest, Local Outlier Factor (LOF), and One-Class SVM.

Dependencies
Python 3.x
NumPy
Pandas
Scikit-Learn
SciPy
Matplotlib
Seaborn

You can install the dependencies using the following command:

bash
code
pip install numpy pandas scikit-learn scipy matplotlib seaborn
Usage
Clone the repository:
bash
code
git clone https://github.com/your-username/anomaly-detection.git
cd anomaly-detection
Run the anomaly_detection.py script:
bash
code
python anomaly_detection.py
Adjust the script parameters and dataset paths as needed.
Algorithms
Isolation Forest
Isolation Forest is an algorithm for anomaly detection that works by isolating instances in random subspaces. It is efficient and effective for high-dimensional datasets.

python
code
from sklearn.ensemble import IsolationForest
Local Outlier Factor (LOF)
LOF is an algorithm that measures the local density deviation of a data point with respect to its neighbors. It can identify outliers based on the local density of instances.

python
code
from sklearn.neighbors import LocalOutlierFactor
One-Class SVM
One-Class SVM is a support vector machine algorithm that learns a decision function for novelty detection. It is trained only on the 'normal' instances and can identify deviations from this norm.

python
code
from sklearn.svm import OneClassSVM
Evaluation
The script includes evaluation metrics such as classification report and accuracy score to assess the performance of the anomaly detection algorithms.

python
code
from sklearn.metrics import classification_report, accuracy_score
Visualization
Matplotlib and Seaborn are used for visualizing the results. Adjust the plotting parameters in the script to suit your preferences.

python
code
import matplotlib.pyplot as plt
import seaborn as sns



Author
Jashoor Kingsly
