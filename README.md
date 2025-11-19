# knn_from_scratch
Method of K-nearest neighbours from scratch for prepaid dataset

# k-NN Classification from Scratch (Euclidean Distance)

This project implements the **k-Nearest Neighbours classifier** **from scratch**, without using scikit-learn's KNN.  
The implementation includes:

- distance computation (Euclidean)
- search for k nearest neighbours
- majority voting (with tie → class **1**, per assignment)
- prediction for single points and arrays
- selection of the best k from the set {1, 3, 5, …, 51}
- full evaluation with accuracy and confusion matrix
- visualizations: scatter plots, decision boundary, accuracy vs k

The dataset contains 2 numerical features describing apples:

- **Weight**
- **Redness**

and a binary class label.

---
# How to Run

1) Open notebooks/knn.ipynb
2) Run cells sequentially
3) Ensure required packages are available:
   - pandas
   - numpy
   - sklearn
   - matplotlib
   - seaborn
All plots will be generated automatically.
