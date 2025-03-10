# Module Report:

---

**Overview:**

We analyzed whether a logistic regression model that values loan size, interest rate, borrower income, debt-to-income and other features to predict whether it's a high-risk or a NON-high-risk loan.  The financial information provided was based on prior credit reports and loans acquired from a public database. We took each of these values and used a logstic regression model to predict the 'loan status'. We simply split our data into a training and testing set and then fit our model. Afterwards we did a confusion matrix and a classification report.

---

**Results**:

*Logistic regression model #1*

* Accuracy: 99.39%
* Precision: 87.33%
* Recall/Sensitivity: 94.88%

---

**Summary:**

The model is great at predicting whether a loan is high-risk or not. We did not compare any other ML models. However, it's so good that it makes me wonder whether it would work when used for real data.
