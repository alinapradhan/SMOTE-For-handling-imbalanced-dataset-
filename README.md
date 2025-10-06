

# SMOTE for Handling Imbalanced Dataset

This repository demonstrates how to handle **imbalanced datasets** using the **SMOTE (Synthetic Minority Over-sampling Technique)** algorithm. The notebook provides a practical walkthrough of resampling techniques with imbalanced-learn and scikit-learn.

##  Overview

In many machine learning tasks, datasets are imbalanced — meaning one class significantly outnumbers the others. This imbalance can bias models toward the majority class.

This notebook covers:
- Creating a synthetic imbalanced dataset
- Applying **Random Undersampling** and **Random Oversampling**
- Applying **SMOTE** for synthetic data generation
- Comparing classification performance before and after resampling

##  Requirements

Install the required Python libraries using pip:

```bash
pip install pandas scikit-learn imbalanced-learn
````

##  Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/alinapradhan/SMOTE_for_handling_imbalanced_dataset.git
   cd SMOTE_for_handling_imbalanced_dataset
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook SMOTE_for_handling_imbalanced_dataset.ipynb
   ```

3. Run the cells sequentially to reproduce results.

##  Techniques Used

* **Random Undersampling**: Reduces the majority class.
* **Random Oversampling**: Duplicates minority samples.
* **SMOTE**: Generates synthetic samples for the minority class.
* **Logistic Regression**: Used for model training and evaluation.

##  Evaluation Metrics

The notebook uses:

* **Accuracy Score**
* **Classification Report** (Precision, Recall, F1-score)

These metrics show model performance before and after applying sampling techniques.

##  References

* [SMOTE in imbalanced-learn Documentation](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html)
* [scikit-learn Documentation](https://scikit-learn.org/stable/)

##  License

This project is licensed under the [MIT License](LICENSE).

```

---

Would you like me to include example output images or plots (e.g., class distribution before/after SMOTE) in the README as well? I can auto-generate markdown placeholders for those.
```
