# Naive Bayes Classifier

Naive Bayes classifier implemented from scratch in Python, on the *weather / play tennis* dataset (categorical features).

> First assignment of the Machine Learning course (1st year, 1st semester), MSc Robotics Engineering, University of Genoa.

## Content

- Prior, likelihood and posterior probabilities computed from the training set, without ML libraries.
- Two versions: standard likelihood (`Lab_1.py`) and with **Laplace smoothing** (`Lab_1_Laplace.py`), which avoids zero probabilities for feature values never seen in training.
- Evaluation over 1000 random training/test splits: the error rate of each split is collected and shown as a histogram.

## Usage

```bash
pip install numpy pandas matplotlib
python3 Lab_1.py            # standard Naive Bayes
python3 Lab_1_Laplace.py    # with Laplace smoothing
```
