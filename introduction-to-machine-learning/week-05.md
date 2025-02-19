# NPTEL Introduction To Machine Learning Week 05 Assignment Answers

Are you looking for NPTEL Introduction To Machine Learning Week 05 Assignment Answers? This repository will help you find your answers and solutions for Week 05 of the Introduction To Machine Learning course. We provide detailed solutions to help you complete your assignments efficiently.


![](https://miro.medium.com/v2/resize:fit:875/1*UxOJzYOIjcHxUSLId0OQTQ.jpeg)

## Introduction to Machine Learning Nptel Week 5 Answers (Jan-Apr 2025)

**Course Link: [**Click Here**](https://onlinecourses.nptel.ac.in/noc25_cs46/preview)**

***

Q1. Consider a feedforward neural network that performs regression on a pp-dimensional input to produce a scalar output. It has mm hidden layers and each of these layers has kk hidden units. What is the total number of trainable parameters in the network? Ignore the bias terms.

a) pk+mk2+kpk + mk^2 + k\
b) pk+(m−1)k2+kpk + (m−1)k^2 + k\
c) p2+(m−1)pk+kp^2 + (m−1)pk + k\
d) p2+(m−1)pk+k2p^2 + (m−1)pk + k^2

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q2. Consider a neural network layer defined as y=ReLU(Wx)y = \text{ReLU}(Wx).\
Here, x∈Rpx \in \mathbb{R}^p is the input, y∈Rdy \in \mathbb{R}^d is the output, and W∈Rd×pW \in \mathbb{R}^{d \times p} is the parameter matrix. The ReLU activation ReLU(z):=max⁡(0,z)\text{ReLU}(z) := \max(0, z) is applied element-wise to WxWx.

Find ∂yi∂Wij\frac{\partial y\_i}{\partial W\_{ij}}, where i=1,..,di=1,..,d and j=1,…,pj=1,…,p.\
In the following options, I(condition)I(\text{condition}) is an indicator function that returns 1 if the condition is true and 0 if it is false.

a) I(∑k=1pWikxk≤0)xiI(\sum\_{k=1}^{p} W\_{ik} x\_k \leq 0) x\_i\
b) I(∑k=1pWikxk>0)xjI(\sum\_{k=1}^{p} W\_{ik} x\_k > 0) x\_j\
c) I(∑k=1pWikxk>0)WijxjI(\sum\_{k=1}^{p} W\_{ik} x\_k > 0) W\_{ij} x\_j\
d) I(∑k=1pWikxk≤0)WijxjI(\sum\_{k=1}^{p} W\_{ik} x\_k \leq 0) W\_{ij} x\_j

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q3. Consider a two-layered neural network y=σ(W(B)σ(W(A)x))y = \sigma(W^{(B)}\sigma(W^{(A)}x)).\
Let h=σ(W(A)x)h = \sigma(W^{(A)}x) denote the hidden layer representation. W(A)W^{(A)} and W(B)W^{(B)} are arbitrary weights. Which of the following statements is/are true?

a) ∇h(y)\nabla\_h(y) depends on W(A)W^{(A)}\
b) ∇W(A)(y)\nabla\_{W^{(A)}}(y) depends on W(B)W^{(B)}\
c) ∇W(A)(h)\nabla\_{W^{(A)}}(h) depends on W(B)W^{(B)}\
d) ∇W(B)(y)\nabla\_{W^{(B)}}(y) depends on W(A)W^{(A)}

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q4. Which of the following statements about the initialization of neural network weights is/are true for a network that uses the sigmoid activation function?

a) Two different initializations of the same network could converge to different minima\
b) For a given initialization, gradient descent will converge to the same minima irrespective of the learning rate\
c) Initializing all weights to the same constant value leads to undesirable results\
d) Initializing all weights to very large values leads to undesirable results

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q5. Consider the following statements about the derivatives of the sigmoid (σ(x)=11+e−x)(\sigma(x) = \frac{1}{1+e^{-x}}) and tanh (tanh⁡(x)=ex−e−xex+e−x)(\tanh(x) = \frac{e^x – e^{-x}}{e^x + e^{-x}}) activation functions. Which of these statements is/are correct?

a) σ′(x)=σ(x)(1−σ(x))\sigma'(x) = \sigma(x)(1 – \sigma(x))\
b) 0<σ′(x)≤140 < \sigma'(x) \leq \frac{1}{4}\
c) tanh⁡′(x)=12(1−(tanh⁡(x))2)\tanh'(x) = \frac{1}{2} (1 – (\tanh(x))^2)\
d) 0\<tanh⁡′(x)≤10 < \tanh'(x) \leq 1

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q6. A geometric distribution is defined by the p.m.f. f(x;p)=(1−p)(x−1)pf(x;p) = (1-p)^{(x-1)} p for x=1,2,….x = 1,2,….\
Given the samples \[4, 5, 6, 5, 4, 3] drawn from this distribution, find the MLE of pp.

a) 0.111\
b) 0.222\
c) 0.333\
d) 0.444

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q7. Consider a Bernoulli distribution with p=0.7p=0.7 (true value of the parameter). We draw samples from this distribution and compute an MAP estimate of pp by assuming a prior distribution over pp. Let N(μ,σ2)N(\mu, \sigma^2) denote a Gaussian distribution with mean μ\mu and variance σ2\sigma^2. Distributions are normalized as needed. Which of the following statements is/are true?

a) If the prior is N(0.6,0.1)N(0.6,0.1), we will likely require fewer samples for converging to the true value than if the prior is N(0.4,0.1)N(0.4,0.1)\
b) If the prior is N(0.4,0.1)N(0.4,0.1), we will likely require fewer samples for converging to the true value than if the prior is N(0.6,0.1)N(0.6,0.1)\
c) With a prior of N(0.1,0.001)N(0.1,0.001), the estimate will never converge to the true value, regardless of the number of samples used\
d) With a prior of U(0,0.5)U(0,0.5) (i.e., uniform distribution between 0 and 0.5), the estimate will never converge to the true value, regardless of the number of samples used

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q8. Which of the following statements about parameter estimation techniques is/are true?

a) To obtain a distribution over the predicted values for a new data point, we need to compute an integral over the parameter space\
b) The MAP estimate of the parameter gives a point prediction for a new data point\
c) The MLE of a parameter gives a distribution of predicted values for a new data point\
d) We need a point estimate of the parameter to compute a distribution of the predicted values for a new data point

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q9. In a classification setting, it is common to minimize the discrete cross-entropy loss given by\
HCE(p,q)=−∑ipilog⁡qiH\_{CE}(p,q) = -\sum\_i p\_i \log q\_i\
where pip\_i and qiq\_i are the true and predicted distributions (pi∈{0,1}p\_i \in \\{0,1\\} depending on the label). Which of the following statements about minimizing the cross-entropy loss is/are true?

a) Minimizing HCE(p,q)H\_{CE}(p,q) is equivalent to minimizing the (self) entropy H(q)H(q)\
b) Minimizing HCE(p,q)H\_{CE}(p,q) is equivalent to minimizing HCE(q,p)H\_{CE}(q,p)\
c) Minimizing HCE(p,q)H\_{CE}(p,q) is equivalent to minimizing the KL divergence DKL(p∣∣q)D\_{KL}(p||q)\
d) Minimizing HCE(p,q)H\_{CE}(p,q) is equivalent to minimizing the KL divergence DKL(q∣∣p)D\_{KL}(q||p)

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)

***

Q10. Which of the following statements about activation functions is/are NOT true?

a) Non-linearity of activation functions is not a necessary criterion when designing very deep neural networks\
b) Saturating non-linear activation functions (derivative → 0 as x→±∞x \to \pm \infty) avoid the vanishing gradients problem\
c) Using the ReLU activation function avoids all problems arising due to gradients being too small\
d) The dead neurons problem in ReLU networks can be fixed using a leaky ReLU activation function

[View Answer](https://my.progiez.com/courses/introduction-to-machine-learning-answers/)


Introduction to Machine Learning Nptel Week 5 Answers (July-Dec 2024)


# Introduction to Machine Learning Nptel Week 5 Answers (July-Dec 2024)

**1. Given a 3-layer neural network which takes in 10 inputs, has 5 hidden units, and outputs 10 outputs, how many parameters are present in this network?**

**a)** 115\
**b)** 500\
**c)** 25\
**d)** 100

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**2. Recall the XOR (tabulated below) example from class where we did a transformation of features to make it linearly separable. Which of the following transformations can also work?**

**a)** Rotating x₁ and x₂ by a fixed angle.\
**b)** Adding a third dimension z = x \* y\
**c)** Adding a third dimension z = x² + y²\
**d)** None of the above

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**3. We use several techniques to ensure the weights of the neural network are small (such as random initialization around 0 or regularisation). What conclusions can we draw if the weights of our ANN are high?**

**a)** Model has overfitted.\
**b)** It was initialized incorrectly.\
**c)** At least one of (a) or (b).\
**d)** None of the above.

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**4. In a basic neural network, which of the following is generally considered a good initialization strategy for the weights?**

**a)** Initialize all weights to zero\
**b)** Initialize all weights to a constant non-zero value (e.g., 0.5)\
**c)** Initialize weights randomly with small values close to zero\
**d)** Initialize weights with large random values (e.g., between -10 and 10)

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**5. Which of the following is the primary reason for rescaling input features before passing them to a neural network?**

**a)** To increase the complexity of the model\
**b)** To ensure all input features contribute equally to the initial learning process\
**c)** To reduce the number of parameters in the network\
**d)** To eliminate the need for activation functions

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**6. In the Bayesian approach to machine learning, we often use the formula: P(θ|D) = P(D|θ) \* P(θ) / P(D). Where θ represents the model parameters and D represents the observed data. Which of the following correctly identifies each term in this formula?**

**a)** P(θ|D) is the likelihood, P(D|θ) is the posterior, P(θ) is the prior, P(D) is the evidence\
**b)** P(θ|D) is the posterior, P(D|θ) is the likelihood, P(θ) is the prior, P(D) is the evidence\
**c)** P(θ|D) is the evidence, P(D|θ) is the likelihood, P(θ) is the posterior, P(D) is the prior\
**d)** P(θ|D) is the prior, P(D|θ) is the evidence, P(θ) is the likelihood, P(D) is the posterior

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**7. Why do we often use log-likelihood maximization instead of directly maximizing the likelihood in statistical learning?**

**a)** Log-likelihood provides a different optimal solution than likelihood maximization\
**b)** Log-likelihood is always faster to compute than likelihood\
**c)** Log-likelihood turns products into sums, making computations easier and more numerically stable\
**d)** Log-likelihood allows us to avoid using probability altogether

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**8. In machine learning, if you have an infinite amount of data, but your prior distribution is incorrect, will you still converge to the right solution?**

**a)** Yes, with infinite data, the influence of the prior becomes negligible, and you will converge to the true underlying solution.\
**b)** No, the incorrect prior will always affect the convergence, and you may not reach the true solution even with infinite data.\
**c)** It depends on the type of model used; some models may still converge to the right solution, while others might not.\
**d)** The convergence to the right solution is not influenced by the prior, as infinite data will always lead to the correct solution regardless of the prior.

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**9. Statement: Threshold function cannot be used as activation function for hidden layers.**\
**Reason: Threshold functions do not introduce non-linearity.**

**a)** Statement is true and reason is false.\
**b)** Statement is false and reason is true.\
**c)** Both are true and the reason explains the statement.\
**d)** Both are true and the reason does not explain the statement.

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

**10. Choose the correct statement (multiple may be correct):**

**a)** MLE is a special case of MAP when prior is a uniform distribution.\
**b)** MLE acts as regularisation for MAP.\
**c)** MLE is a special case of MAP when prior is a beta distribution.\
**d)** MAP acts as regularisation for MLE.

**Answer:** [Click here to View Answers](https://progiez.com/introduction-to-machine-learning-nptel-week-5-answers)

All weeks of Introduction to Machine Learning: [Click Here](https://progiez.com/nptel-assignment-answers/introduction-to-internet-of-things)

For answers to additional Nptel courses, please refer to this link: [NPTEL Assignment Answers](https://progiez.com/nptel-assignment-answers)


# Introduction to Machine Learning Nptel Week 5 Answers (JAN-APR 2024)

**Course name: Introduction to Machine Learning**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc24_cs51/preview)

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

Q1. Consider a feedforward neural network that performs regression on a p-dimensional input to produce a scalar output. It has m hidden layers and each of these layers has k hidden units. What is the total number of trainable parameters in the network? Ignore the bias terms.\
pk+mk2\
pk+mk2+k\
pk+(m−1)k2+k\
p2+(m−1)pk+k\
p2+(m−1)pk+k2

**Answer: pk+(m−1)k2+k**

**Q2. Consider a neural network layer defined as y=ReLU(Wx). Here x∈Rp is the input, y∈Rd is the output and W∈Rd×p is the parameter matrix. The ReLU activation (defined as ReLU(z):=max(0,z) for a scalar z) is applied element-wise to Wx. Find ∂yi∂Wij where i=1,..,d and j=1,…,p. In the following options, I (condition) is an indicator function that returns 1 if the condition is true and 0 if it is false.**\
I(yi>0)xi\
I(yi>0)xj\
I(yi≤0)xi\
I(yi>0)Wijxj\
I(yi≤0)Wijxi

**Answer: I(yi>0)xj**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q3. Consider a two-layered neural network y=σ(W(B)σ(W(A)x)). Let h=σ(W(A)x) denote the hidden layer representation. W(A) and W(B) are arbitrary weights. Which of the following statement(s) is/are true? Note: ∇g(f) denotes the gradient of f w\.r.t g.**\
∇h(y) depends on W(A).\
∇W(A)(y) depends on W(B).\
∇W(A)(h) depends on W(B).\
∇W(B)(y) depends on W(A).

**Answer: B, D**

**Q4. Which of the following statement(s) about the initialization of neural network weights is/are true?**\
Two different initializations of the same network could converge to different minima.\
For a given initialization, gradient descent will converge to the same minima irrespective of the learning rate.\
The weights should be initialized to a constant value.\
The initial values of the weights should be sampled from a probability distribution.

**Answer: A, D**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q5. Consider the following statements about the derivatives of the sigmoid (σ(x)=11+exp(−x))) and tanh(tanh(x)=exp(x)−exp(−x)exp(x)+exp(−x)) activation functions. Which of these statement(s) is/are correct?**\
0<σ′(x)≤18\
limx→−∞σ′(x)=0\
0\<tanh′(x)≤1\
limx→+∞tanh′(x)=1

**Answer: B, C**

**Q6. A geometric distribution is defined by the p.m.f. f(x;p)=(1−p)(x−1)p for x=1,2,….. Given the samples \[4,5,6,5,4,3] drawn from this distribution, find the MLE of p. Using this estimate, find the probability of sampling x≥5 from the distribution.**\
0.289\
0.325\
0.417\
0.366

**Answer: 0.366**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q7. Consider a Bernoulli distribution with with p=0.7 (true value of the parameter). We draw samples from this distribution and compute an MAP estimate of p by assuming a prior distribution over p. Which of the following statement(s) is/are true?**

If the prior is Beta(2,6), we will likely require fewer samples for converging to the true value than if the prior is Beta(6,2).\
If the prior is Beta(6,2), we will likely require fewer samples for converging to the true value than if the prior is Beta(2,6).\
With a prior of Beta(2,100), the estimate will never converge to the true value, regardless of the number of samples used.\
With a prior of U(0,0.5) (i.e. uniform distribution between 0 and 0.5), the estimate will never converge to the true value, regardless of the number of samples used.

**Answer: B, D**

**Q8. Which of the following statement(s) about parameter estimation techniques is/are true?**\
To obtain a distribution over the predicted values for a new data point, we need to compute an integral over the parameter space.\
The MAP estimate of the parameter gives a point prediction for a new data point.\
The MLE of a parameter gives a distribution of predicted values for a new data point.\
We need a point estimate of the parameter to compute a distribution of the predicted values for a new data point.

**Answer: A, B**

**For answers or latest updates join our telegram channel:** [**Click here to join**](https://telegram.me/nptel_assignments)

**These are Introduction to Machine Learning Nptel Week 5 Answers**

More Weeks of Introduction to Machine Learning: [Click here](https://progiez.com/nptel-assignment-answers/introduction-to-machine-learning/)

More Nptel Courses: <https://progiez.com/nptel-assignment-answers>


# Introduction to Machine Learning Nptel Week 5 Answers (JULY-DEC 2023)

**Course Name: Introduction to Machine Learning**

**Course Link:** [**Click Here**](https://onlinecourses.nptel.ac.in/noc23_cs98/course)

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q1. The perceptron learning algorithm is primarily designed for:**\
Regression tasks\
Unsupervised learning\
Clustering tasks\
Linearly separable classification tasks\
Non-linear classification tasks

**Answer: Linearly separable classification tasks**

**Q2. The last layer of ANN is linear for \_\_\_\_\_\_\_\_ and softmax for \_\_\_\_\_\_\_\_.**\
Regression, Regression\
Classification, Classification\
Regression, Classification\
Classification, Regression

**Answer: Regression, Classification**

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q3. Consider the following statement and answer True/False with corresponding reason:\
The class outputs of a classification problem with a ANN cannot be treated independently.**\
True. Due to cross-entropy loss function\
True. Due to softmax activation\
False. This is the case for regression with single output\
False. This is the case for regression with multiple outputs

**Answer: True. Due to softmax activation**

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q4. Given below is a simple ANN with 2 inputs X1,X2∈{0,1} and edge weights −3,+2,+2\
h={1 if x≥0 0 otherwise\
Which of the following logical functions does it compute?**\
XOR\
NOR\
NAND\
AND

**Answer: AND**

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q5. Using the notations used in class, evaluate the value of the neural network with a 3–3–1 architecture (2-dimensional input with 1 node for the bias term in both the layers). The parameters are as follows\
α=\[1 1 0.4 0.6 0.3 0.5]\
β=\[0.4 0.6 0.9]\
Using sigmoid function as the activation functions at both the layers, the output of the network for an input of (0.8, 0.7) will be (up to 4 decimal places)**\
0.7275\
0.0217\
0.2958\
0.8213\
0.7291\
0.8414\
0.1760\
0.7552\
0.9442\
None of these

**Answer: 0.8414**

**Q6. If the step size in gradient descent is too large, what can happen?**\
Overfitting\
The model will not converge\
We can reach maxima instead of minima\
None of the above

**Answer: The model will not converge**

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q7. On different initializations of your neural network, you get significantly different values of loss. What could be the reason for this?**\
Overfitting\
Some problem in the architecture\
Incorrect activation function\
Multiple local minima

**Answer: Multiple local minima**

**These are Introduction to Machine Learning Nptel Week 5 Answers**

**Q8. The likelihood L(θ|X) is given by:**\
P(θ|X)\
P(X|θ)\
P(X).P(θ)\
P(θ)/P(X)

**Answer: P(X|θ)**

**Q9. Why is proper initialization of neural network weights important?**\
To ensure faster convergence during training\
To prevent overfitting\
To increase the model’s capacity\
Initialization doesn’t significantly affect network performance\
To minimize the number of layers in the network

**Answer: To ensure faster convergence during training**

**Q10. Which of these are limitations of the backpropagation algorithm?**\
It requires error function to be differentiable\
It requires activation function to be differentiable\
The ith layer cannot be updated before the update of layer i+1 is complete\
All of the above\
(a) and (b) only\
None of these

**Answer: All of the above**

**These are Introduction to Machine Learning Nptel Week 5 Answers**

More Weeks of INTRODUCTION TO MACHINE LEARNING: [Click here](https://progiez.com/nptel-assignment-answers/introduction-to-machine-learning)

More Nptel Courses: [Click here](https://progiez.com/nptel-assignment-answers)
