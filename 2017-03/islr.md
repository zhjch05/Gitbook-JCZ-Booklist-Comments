# ISLR

## 2. Statistical Learning

**Prediction and Inference:**

Prediction's f is like a black-box while inference seeks the inner relationships and therefore needs f in exact form.

**Estimation of f:**

**Parametric method:**

linear; overfitting

**Non-parametric methods:**

In contrast, non-parametric approaches completely avoid this danger, since essentially no assumption about the form offis made. Since they do not reduce the problem of estimatingfto a small number of parameters, a very large number of observations \(far more than is typically needed for a parametric approach\) is required in order to obtain an accurate estimate for f.

**Trade-Off Between Prediction Accuracy and Model Interpretability**

Still depends on the preference to prediction or inference.

We will often obtain more accurate predictions using a less flexible method. - "overfitting"

**Supervised Versus Unsupervised Learning**

Unsupervised Learning: We can seek to understand the relationships between the variables or between the observations.

Example: classification v.s. clustering

Semi-supervised learning: m cases with supervised model and n - m the other.

**Regression Versus Classification Problems**

quantitive: numerical values and qualitive: classes/categories

quantitive: regression, qualitive: classification

Since it\(logistic regression\) estimates class probabilities, it can be thought of as a regression method as well.

**Measuring the Quality of Fit**

As model flexibility increases, training MSE will decrease, but the test MSE may not. When a given method yields a small training MSE but a large test MSE, we are said to be overfitting the data.

