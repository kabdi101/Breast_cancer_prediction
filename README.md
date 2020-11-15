## Analyzing and Predicting Whether A cell is Benign or Malignant


According to Center for Disease Control and Prevention, cancer is the second leading cause of death "exceeded only by heart disease" in the United States. In 2017, over 250,520 new cases of female breast cancer were reported in the United States, and 42,000 women died of this cancer.
Analyzing breast cancer data set and building a model that will predict whether a cancer is benign or malignant will help greatly in implementing early detection, treatment, and prevention strategies which will lead to the reduction of number of deaths in the United States.

**Exploratory data analysis:**

- There is a strong correlation between malignancy and (radius, number of concave points, perimeter, and area)
- Generally speaking, the benign median is lower than the malignant median for almost all features
- The benign and malignant features distribution varies almost across all cells

These findings are expected because these features were modeled in such way that higher values are typically associated with malignancy

**Support vector machine**

-	The SVM model's accuracy is 96%
-	The accuracy of positive predictions (precision) is 94%
-	The fraction of positives that were correctly identified (recall) is 97%

The SVM model showed great ability (high accuracy, precision, and recall scores) to correctly classify weather a cell is benign or malignant. To improv these scores, I suggest using more advanced feature selection techniques to determine the highest scoring features then using these features to build the model
