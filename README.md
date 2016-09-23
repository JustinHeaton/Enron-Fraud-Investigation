# Enron Fraud Investigation
## Predicting whether or not Enron employees were POIs in their fraud scandal

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Seaborn](http://stanford.edu/~mwaskom/software/seaborn/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Code

- **Enron_Emails.ipynb:** Contains the report with investigation on the dataset including training and tuning the final classifier and feature set.
- **final_project_dataset.pkl:** Contains the dataset used in the problem.
- **my_classifier.pkl:** Contains the final classification algorithm used to make predictions on the dataset.
- **my_dataset.pkl:** Contains the final dataset after removing outliers and engineering new features.
- **my_feature_list.pkl:** Contains the final list of features used to the classifier.
- **tester.py:** The script which can be used to test my final classifier, dataset and feature list.

### Run

In order to run the tester file and see the resulting performance.
In a terminal or command window, navigate to the top-level project directory which  contains this README and run the following command:
```
python tester.py
```

