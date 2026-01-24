# NPTEL Introduction To Machine Learning Week 02 Assignment Answers

Are you looking for NPTEL Introduction To Machine Learning Week 02 Assignment Answers? This repository will help you find your answers and solutions for Week 02 of the Introduction To Machine Learning course. We provide detailed solutions to help you complete your assignments efficiently.

![Introduction to Machine Learning Nptel Week 2 Answers](https://miro.medium.com/v2/resize:fit:875/1*nh2U8GRaYnyFlaeRQVDh6g.jpeg)


## __Introduction To Machine Learning Week 2 Nptel Answers__ (Jan-Apr 2026)

**Que.1**\
In building a linear regression model for a particular data set, you observe the coefficient of one of the features having a relatively high negative value. This suggests that:

a) This feature has a strong effect on the model (should be retained)\
b) This feature does not have a strong effect on the model (should be ignored)\
c) It is not possible to comment on the importance of this feature without additional information

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.2**\
We have seen methods like ridge and lasso to reduce variance among the coefficients. We can use these methods to do feature selection also. Which one of them is more appropriate?

a) Ridge\
b) Lasso

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.3**\
Given a set of _n_ data points, ((x\_1, y\_1), (x\_2, y\_2), \ldots, (x\_n, y\_n)), the best least squares fit (f(x)) is obtained by minimization of:

a) (\sum\_{i=1}^{n}\[y\_i – f(x\_i)])\
b) (\min (y\_i – f(x\_i)))\
c) (\sum\_{i=1}^{n}\[y\_i – f(x\_i)]^2)\
d) (\max (y\_i – f(x\_i)))

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.4**\
During linear regression, with regards to residuals, which among the following is true?

a) Lower is better\
b) Higher is better\
c) Depends upon the data\
d) None of the above

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.5**\
In the lecture on Multivariate Regression, you learn about using orthogonalization iteratively to obtain regression coefficients. This method is generally referred to as Multiple Regression using Successive Orthogonalization.\
In the formulation of the method, we observe that in iteration _k_, we regress the entire dataset on (z\_0, z\_1, \ldots, z\_{k-1}). It seems like a waste of computation to recompute the coefficients repeatedly. Can we reuse the coefficients computed in iteration _j_ for iteration _j + 1_ for (z\_{j-1})?

a) No. Doing so will result in the wrong (\gamma) matrix and hence the wrong (\beta\_i)’s.\
b) Yes. Since (z\_{j-1}) is orthogonal to (z\_{j-l}) for all (l \le j-1), the regression coefficients do not change and can be reused.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.6**\
You decide to reduce the dimensionality of your data ((N \times p)) using Best Subset Selection. The library you’re using has a function `regress(X, Y)` that regresses _Y_ on _X_. What is the expected number of times `regress(·, ·)` will be called during dimensionality reduction?

a) (O(2^N))\
b) (O(2^p))\
c) (O(Np))\
d) (O(p^2))

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.7**\
If the number of features is larger than the number of training data points, to identify a suitable subset of the features for use with linear regression, we would prefer:

a) Forward stepwise selection\
b) Backward stepwise selection

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.8**\
Assume you have a five-dimensional input data for a three-class classification problem. Further assume that all five dimensions of the input are independent of each other. In this scenario, is it possible for linear regression using lasso to result in one or more coefficients becoming zero?

a) Yes\
b) No

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.9**\
You are given the following five three-dimensional training data instances (along with one-dimensional output):

• (x\_1 = 5, x\_2 = 7, x\_3 = 3, y = 4)\
• (x\_1 = 2, x\_2 = 4, x\_3 = 9, y = 8)\
• (x\_1 = 3, x\_2 = 8, x\_3 = 1, y = 2)\
• (x\_1 = 7, x\_2 = 7, x\_3 = 2, y = 3)\
• (x\_1 = 1, x\_2 = 9, x\_3 = 7, y = 8)

Using the K-nearest neighbour technique for performing regression, what will be the predicted _y_ value corresponding to the query point ((x\_1 = 5, x\_2 = 3, x\_3 = 4)), for (K = 2)?

a) 3\
b) 2.5\
c) 3.5\
d) 2

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Que.10**\
For the dataset given in the previous question, what will be the predicted _y_ value corresponding to the query point ((x\_1 = 5, x\_2 = 3, x\_3 = 4)), for (K = 3)?

a) 4.66\
b) 5\
c) 3\
d) 3.5

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)


## __Introduction To Machine Learning Week 2 Nptel Answers__ (July-Dec 2025)

***

**Question 1.**\
Typically, linear regression tends to underperform compared to k-nearest neighbor algorithms when dealing with high-dimensional input spaces.

a) True\
b) False

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Question 2.**\
Given the following dataset, find the uni-variate regression function that best fits the dataset.

a) f(x) = 1 × x + 4\
b) f(x) = 1 × x + 5\
c) f(x) = 1.5 × x + 3\
d) f(x) = 2 × x + 1

Answer:

***

**Question 3.**\
Given a training data set of 500 instances, with each input instance having 6 dimensions and each output being a scalar value, the dimensions of the design matrix used in applying linear regression to this data is:

a) 500 × 6\
b) 500 × 7\
c) 500 × 62\
d) None of the above

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Question 4.**\
Assertion A: Binary encoding is usually preferred over One-hot encoding to represent categorical data (e.g., colors, gender etc).\
Reason R: Binary encoding is more memory efficient when compared to One-hot encoding.

a) Both A and R are true and R is the correct explanation of A\
b) Both A and R are true but R is not the correct explanation of A\
c) A is true but R is false\
d) A is false but R is true

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Question 5.**\
Select the TRUE statement:

a) Subset selection methods are more likely to improve test error by only focussing on the most important features and by reducing variance in the fit.\
b) Subset selection methods are more likely to improve train error by only focussing on the most important features and by reducing variance in the fit.\
c) Subset selection methods are more likely to improve both test and train error by focussing on the most important features and by reducing variance in the fit.\
d) Subset selection methods don’t help in performance gain in any way.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Question 6.**\
Rank the 3 subset selection methods in terms of computational efficiency:

a) Forward stepwise selection, best subset selection, and forward stagewise regression.\
b) Forward stepwise selection, forward stagewise regression and best subset selection.\
c) Best subset selection, forward stagewise regression and forward stepwise selection.\
d) Best subset selection, forward stepwise selection and forward stagewise regression.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Question 7.**\
Choose the TRUE statements from the following: (Multiple correct choices)

a) Ridge regression since it reduces the coefficients of all variables, makes the final fit a lot more interpretable.\
b) Lasso regression since it doesn’t deal with a squared power is easier to optimize than ridge regression.\
c) Ridge regression has a more stable optimization than lasso regression.\
d) Lasso regression is better suited for interpretability than ridge regression.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**Question 8.**\
Which of the following statements are TRUE?\
Let xix\_i be the i-th datapoint in a dataset of N points. Let vv represent the first principal component of the dataset. (Multiple answer questions)

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)


## _Introduction to Machine Learning Nptel Week 2 Answers (Jan-Apr 2025)_

***

**1) In a linear regression model y = 90 + β1×1 + β2×2 + … + βpxp, what is the purpose of adding an intercept term 90?**\
Options:\
\[a] To increase the model’s complexity.\
\[b] To account for the effect of independent variables.\
\[c] To adjust for the baseline level of the dependent variable when all predictors are zero.\
\[d] To ensure the coefficients of the model are unbiased.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**2) Which of the following is true about the cost function (objective function) used in linear regression?**\
Options:\
\[a] It is non-convex.\
\[b] It is always minimized at θ = 0.\
\[c] It measures the sum of squared differences between predicted and actual values.\
\[d] It assumes the dependent variable is categorical.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**3) Which of these would most likely indicate that Lasso regression is a better choice than Ridge regression?**\
Options:\
\[a] All features are equally important.\
\[b] Features are highly correlated.\
\[c] Most features have small but non-zero impact.\
\[d] Only a few features are truly relevant.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**4) Which of the following conditions must hold for the least squares estimator in linear regression to be unbiased?**\
Options:\
\[a] The independent variables must be normally distributed.\
\[b] The relationship between predictors and the response must be non-linear.\
\[c] The errors must have a mean of zero.\
\[d] The sample size must be larger than the number of predictors.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**5) When performing linear regression, which of the following is most likely to cause overfitting?**\
Options:\
\[a] Adding too many regularization terms.\
\[b] Including irrelevant predictors in the model.\
\[c] Increasing the sample size.\
\[d] Using a smaller design matrix.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**6) You have trained a complex regression model on a dataset. To reduce its complexity you decide to apply Ridge regression, using a regularization parameter λ. How does the relationship between bias and variance change as λ becomes very large?**\
Options:\
\[a] Bias is low, variance is high.\
\[b] Bias is high, variance is low.\
\[c] Bias is high, variance is high.\
\[d] Bias is low, variance is low.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**7) Given a training dataset of 10,000 instances, with each input instance having 12 dimensions and each output instance having 3 dimensions, the dimensions of the design matrix used in applying linear regression to this data is**\
Options:\
\[a] 10,000 x 12\
\[b] 10,000 x 13\
\[c] 10,000 x 12\
\[d] 10,000 x 15

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**8) The linear regression model y = β0 + β1×1 + … + βpxp is to be fitted to a set of N training data points having P attributes each. Let X be an N x (p + 1) matrix of input values (augmented by 1’s), Y be an N x 1 vector of target values, and β be a (p + 1) x 1 vector of parameter values (β0, β1, … , βp). If the sum of squared error is minimized for obtaining the optimal regression model, which of the following equation holds?**\
Options:\
\[a] X^TX = X^TY\
\[b] X^TX = XY\
\[c] X^TX = Y\
\[d] X^TX = X^TY

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**9) Which of the following scenarios is most appropriate for using Partial Least Squares (PLS) regression instead of ordinary least squares (OLS)?**\
Options:\
\[a] When the predictors are uncorrelated and the number of samples is much larger than the number of predictors.\
\[b] When there is significant multicollinearity among predictors or the number of predictors exceeds the number of samples.\
\[c] When the response variable is categorical and the predictors are highly non-linear.\
\[d] When the primary goal is to interpret the relationship between predictors and response, rather than prediction accuracy.

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

**10) Consider forward selection, backward selection, and best subset selection with respect to the same dataset. Which of the following is true?**\
Options:\
\[a] Best subset selection can be computationally more expensive than forward selection.\
\[b] Forward selection and backward selection always lead to the same result.\
\[c] Best subset selection can be computationally less expensive than backward selection.\
\[d] Best subset selection and forward selection are computationally equally expensive.\
\[e] Both (b) and (d).

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

Introduction to Machine Learning Nptel Week 2 Answers (July-Dec 2024)


# Introduction to Machine Learning Nptel Week 2 Answers (July-Dec 2024)<a id="f6eb"></a>

**Q1**.State True or False:\
Typically, linear regression tend to underperform compared to k-nearest neighbor algorithms when dealing with high-dimensional input spaces.\
True\
False

**Answer: True**

**Q2. Given the following dataset, find the uni-variate regression function that best fits the dataset.**

f(x)=1×x+4

f(x)=1×x+5

f(x)=1.5×x+3

f(x)=2×x+1

**Answer: f(x)=1.5×x+3**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Machine Learning Nptel Week 2 Answers**

**Q3.**Given a training data set of 500 instances, with each input instance having 6 dimensions and each output being a scalar value, the dimensions of the design matrix used in applying linear regression to this data is

500×6

500×7

500×62\
None of the above

[**_**Answer: Click here to see answers**_**](https://progiez.com/introduction-to-machine-learning-nptel-week-2-answers)

**Q4.** Assertion A: Binary encoding is usually preferred over One-hot encoding to represent categorical data (eg. colors, gender etc)\
Reason R: Binary encoding is more memory efficient when compared to One-hot encoding\
Both A and R are true and R is the correct explanation of A\
Both A and R are true but R is not the correct explanation of A\
A is true but R is false\
A is false but R is true

[**_**Answer: Click here to see answers**_**](https://progiez.com/introduction-to-machine-learning-nptel-week-2-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Machine Learning Nptel Week 2 Answers**

**Q5.** Select the TRUE statement\
Subset selection methods are more likely to improve test error by only focussing on the most important features and by reducing variance in the fit.\
Subset selection methods are more likely to improve train error by only focussing on the most important features and by reducing variance in the fit.\
Subset selection methods are more likely to improve both test and train error by focussing on the most important features and by reducing variance in the fit.\
Subset selection methods don’t help in performance gain in any way.

[**_**Answer: Click here to see answers**_**](https://progiez.com/introduction-to-machine-learning-nptel-week-2-answers)

**Q6.** Rank the 3 subset selection methods in terms of computational efficiency:\
Forward stepwise selection, best subset selection, and forward stagewise regression.\
Forward stepwise selection, forward stagewise regression and best subset selection.\
Best subset selection, forward stagewise regression and forward stepwise selection.\
Best subset selection, forward stepwise selection and forward stagewise regression.

[**_**Answer: Click here to see answers**_**](https://progiez.com/introduction-to-machine-learning-nptel-week-2-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Machine Learning Nptel Week 2 Answers**

Q7.Choose the TRUE statements from the following: (Multiple correct choice)\
Ridge regression since it reduces the coefficients of all variables, makes the final fit a lot more interpretable.\
Lasso regression since it doesn’t deal with a squared power is easier to optimize than ridge regression.\
Ridge regression has a more stable optimization than lasso regression.\
Lasso regression is better suited for interpretability than ridge regression.

[**_**Answer: Click here to see answers**_**](https://progiez.com/introduction-to-machine-learning-nptel-week-2-answers)

**Q8.**Which of the following statements are TRUE? Let xi be the i−th datapoint in a dataset of N\
points. Let v represent the first principal component of the dataset. (Multiple answer questions)

a) v=argmax∑Ni=1(vTxi)2s.t.|v|=1

b) v=argmin∑Ni=1(vTxi)2s.t.|v|=1\
c) Scaling at the start of performing PCA is done just for better numerical stability and computational benefits but plays no role in determining the final principal components of a dataset.\
d) The resultant vectors obtained when performing PCA on a dataset can vary based on the scale of the dataset.

[**_**Answer: Click here to see answers**_**](https://progiez.com/introduction-to-machine-learning-nptel-week-2-answers)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Machine Learning Nptel Week 2 Answers**

All weeks of Introduction to Machine Learning: [Click Here](https://progiez.com/nptel-assignment-answers/introduction-to-internet-of-things)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment Answers](https://progiez.com/nptel-assignment-answers)


# Introduction to Machine Learning Nptel Week 2 Answers (JAN-APR 2024)<a id="af0a"></a>

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs51/preview)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

These are Introduction to Machine Learning Week 2 Assignment 2 Answers

Q1. The parameters obtained in linear regression\
can take any value in the real space\
are strictly integers\
always lie in the range \[0,1]\
can take only non-zero values

**Answer: can take any value in the real space**

**Q2. Suppose that we have N independent variables (X1,X2,…Xn) and the dependent variable is Y. Now imagine that you are applying linear regression by fitting the best fit line using the least square error on this data. You found that the correlation of X1 with Y is -0.005.**\
Regressing Y on X1 mostly does not explain away Y\
Regressing Y on X1 explains away Y\
The given data is insufficient to determine if regressing Y on X1 explains away Y or not\
None of the above

**Answer: Regressing Y on X1 mostly does not explain away Y**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Introduction to Machine Learning Week 2 Assignment Answers**

**Q3. The relation between studying time (in hours) and grade on the final examination (0–100) in a random sample of students in the Introduction to Machine Learning Class was found to be:\
Grade = 30.5+15.2(h)\
How will a student’s grade be affected if she studies for four hours, compared to not studying?**\
It will go down by 30.4 points\
It will go up by 60.8 points\
The grade will remain unchanged\
It cannot be determined from the information given

**Answer: It will go up by 60.8 points**

**Q4. Consider the following 4 training examples:\
We want to learn a function f(x)=ax+b which is parametrized by (a,b). Using squared error as the loss function, which of the following parameters would you use to model this function.**\
(1,1)\
(1,2)\
(2,1)\
(2,2)

**Answer: (1,1)**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Introduction to Machine Learning Week 2 Assignment Answers**

**Q5. Consider a modified k−NN method in which once the k nearest neighbours to the query point are identified, you do a linear regression fit on them and output the fitted value for the query point. Which of the following is/are true regarding this method.**\
This method makes an assumption that the data is locally linear\
In order to perform well, this method would need dense distributed training data\
This method has higher bias compared to k−NN\
This method has higher variance compared to k−NN

**Answer: a, b, d\
This method makes an assumption that the data is locally linear\
In order to perform well, this method would need dense distributed training data\
This method has higher variance compared to k−NN**

**Q6. Which of the statements is/are True?**\
Ridge has sparsity constraint, and it will drive coefficients with low values to 0\
Lasso has a closed form solution for the optimization problem, but this is not the case for Ridge\
Ridge regression may reduce the number of variables\
If there are two or more highly collinear variables, Lasso will select one of them randomly

**Answer: c, d\
Ridge regression does not reduce the number of variables since it never leads a coefficient to zero but only minimizes it.\
If there are two or more highly collinear variables, Lasso will select one of them randomly**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Introduction to Machine Learning Week 2 Assignment Answers**

**Q7. Choose the correct option(s) from the following:**\
When working with a small dataset, one should prefer low bias/high variance classifiers over high bias/low variance classifiers\
When working with a small dataset, one should prefer high bias/low variance classifiers over low bias/high variance classifiers\
When working with a large dataset, one should prefer high bias/low variance classifiers over low bias/high variance classifiers\
When working with a large dataset, one should prefer low bias/high variance classifiers over high bias/low variance classifiers

**Answer: b), d)\
When working with a small dataset, one should prefer high bias/low variance classifiers over low bias/high variance classifiers\
When working with a large dataset, one should prefer low bias/high variance classifiers over high bias/low variance classifiers**

**Q8. Consider the following statements:\
Statement A: In Forward stepwise selection, in each step, that variable is chosen which has the maximum correlation with the residual, then the residual is regressed on that variable, and it is added to the predictor.\
Statement B: In Forward stagewise selection, the variables are added one by one to the previously selected variables to produce the best fit till then**\
Both the statements are True\
Statement A is True, and Statement B is False\
Statement A if False and Statement B is True\
Both the statements are False

**Answer: Both the statements are False**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Introduction to Machine Learning Week 2 Assignment Answers**

**Q9. The linear regression model y=a0+a1x1+a2x2+…+apxp is to be fitted to a set of N training data points having p attributes each. Let X be N×(p+1) vectors of input values (augmented by 1’s), Y be N×1\
vector of target values, and θ be (p+1)×1 vector of parameter values (a0,a1,a2,…,ap ). If the sum squared error is minimized for obtaining the optimal regression model, which of the following equation holds?**\
XTX=XY\
Xθ=XTY\
XTXθ=Y\
XTXθ=XTY

**Answer: XTXθ=XTY**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Nptel Introduction to Machine Learning Week 2 Assignment Answers**

More Weeks of Introduction to Machine Learning: [Click here](https://progiez.com/nptel-assignment-answers/introduction-to-machine-learning/)

More Nptel Courses: <https://progiez.com/nptel-assignment-answers>


# Introduction to Machine Learning Nptel Week 2 Answers (JULY-DEC 2023)<a id="b171"></a>

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs98/course)

**These are Introduction to Machine Learning Week 2 Assignment 2 Answers**

**Q1. The parameters obtained in linear regression**\
can take any value in the real space\
are strictly integers\
always lie in the range \[0,1]\
can take only non-zero values

**Answer: can take any value in the real space**

**These are Nptel Introduction to Machine Learning Week 2 Assignment Answers**

**Q2. Suppose that we have N independent variables (X1,X2,…Xn) and the dependent variable is Y. Now imagine that you are applying linear regression by fitting the best fit line using the least square error on this data. You found that the correlation coefficient for one of its variables (Say X1) with Y is -0.005.**\
Regressing Y on X1 mostly does not explain away Y.\
Regressing Y on X1 explains away Y.\
The given data is insufficient to determine if regressing Y on X1 explains away Y or not.
