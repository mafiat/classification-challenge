# Classification Challenge

## Overview

This project is a classification challenge focused on building a spam detector. The goal is to classify messages as either spam or not spam using machine learning techniques.

## Dataset

The dataset used for this project consists of labeled messages. Each message is labeled as either "spam" or "ham" (not spam).

## Notebooks

- `spam_detector.ipynb`: This notebook contains the code for preprocessing the data, training the model, and evaluating its performance.

## Installation

To run the notebook, you need to have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- Pandas
- Scikit-learn

You can install the required packages using pip:

```bash
pip install pandas scikit-learn jupyter
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/mafiat/classification-challenge
    ```
2. Navigate to the project directory:
    ```bash
    cd classification-challenge
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook spam_detector.ipynb
    ```

## Results

The performance of the spam detector is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results are documented in the notebook.

1. Logistic Regression model

        Accuracy Score: 0.923
        Training Score: 0.926
        Testing Score: 0.923

        Classification Report:

                       precision    recall  f1-score   support

                   0       0.91      0.96      0.94       676
                   1       0.94      0.87      0.90       475

            accuracy                           0.92      1151
           macro avg       0.93      0.91      0.92      1151
        weighted avg       0.92      0.92      0.92      1151

2. Random Forest Classifier model

Accuracy Score: 0.958
Training Score: 0.999
Testing Score: 0.958

        Classification Report:

                       precision    recall  f1-score   support

                   0       0.95      0.98      0.97       676
                   1       0.98      0.92      0.95       475

            accuracy                           0.96      1151
           macro avg       0.96      0.95      0.96      1151
        weighted avg       0.96      0.96      0.96      1151

## Conclusion

* Random Forest Classifier performed better.
* The Logistic Regression presented an accuracy of 92.3% while Random Forest model presented an accuracy of 95.8%
* Looking into more detail with the classification report, we observe a higher F1-Score for the Random Forest

## License

This project is licensed under the MIT License.
