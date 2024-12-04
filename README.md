# Breast Cancer Prediction Project

This project aims to predict breast cancer outcomes using various classification techniques. The implemented techniques include Support Vector Machine (SVM), Decision Tree, K Nearest Neighbors (KNN), and Sequential Minimal Optimization (SMO). The project also includes a script for reading the breast cancer dataset.

## Files Included:

1. `Evaluation.py`: This script evaluates the performance of different classification techniques using metrics such as accuracy, precision, recall, and F1-score. It compares the results of SVM, Decision Tree, KNN, and SMO classifiers.

2. `SVM.py`: This script contains the implementation of the Support Vector Machine (SVM) classifier for breast cancer prediction. It utilizes the Sequential Minimal Optimization (SMO) algorithm for training the SVM model.

3. `decision_tree.py`: This script implements the Decision Tree classifier for breast cancer prediction. It constructs a decision tree based on the attributes of the breast cancer dataset.

4. `gistfile1.py`: This script contains the implementation of the K Nearest Neighbors (KNN) classifier for breast cancer prediction. It classifies instances based on the similarity of their nearest neighbors.

5. `knn.py`: This script provides a KNN implementation, although the code provided in this file is similar to what is in `gistfile1.py`. 

6. `read_dataset.py`: This script is responsible for reading the breast cancer dataset. It loads the dataset from a file and prepares it for use in training and testing the classification models.

## Usage:

1. Clone the repository to your local machine:

```
git clone <repository_url>
```

2. Ensure you have Python installed on your system along with necessary libraries like NumPy, Pandas, and Scikit-learn.

3. Navigate to the project directory:

```
cd breast_cancer_prediction
```

4. Run the scripts:

- For running the evaluation script:

```
python Evaluation.py
```

- For running individual classifiers:

```
python SVM.py
python decision_tree.py
python knn.py
```

5. Follow the on-screen instructions and observe the output to analyze the performance of each classifier.

## Credits:

This project is based on the research paper titled "Evaluation of Classification Techniques for Breast Cancer Prediction" by Dr. Vikas Chaurasia and Saurabh Pal. (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2994932) I acknowledge their work and contribution to the field of breast cancer prediction.
