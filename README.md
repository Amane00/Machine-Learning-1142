# Machine-Learning-1142

This repository contains my coursework, assignments, and notes for the Machine Learning course. 
The course spans 16 weeks (with Week 8 as the midterm / Week 15 and 16 as the final exam), covering foundational machine learning algorithms, model evaluation techniques, and practical implementations.

## 📅 Course Syllabus & Summary

### Week 1: Introduction to Machine Learning
- Definition of Machine Learning by Tom Mitchell and Arthur Samuel.
- Overview of learning types: Supervised, Unsupervised, and Reinforcement Learning.
- The Machine Learning Loop and practical applications (e.g., Autonomous cars, Deep Learning, Generative AI).

### Week 2: Decision Trees (Foundations)
- Introduction to Decision Tree structures and decision boundaries.
- Measuring impurity using Entropy and calculating Information Gain.
- Top-down induction of decision trees using the ID3 algorithm and the concept of Occam's Razor.

### Week 3: Decision Trees (Advanced & Overfitting)
- Using Gain Ratio to handle attributes with many values, and dealing with real-valued or missing data.
- Understanding the problem of overfitting in decision trees.
- Methods to avoid overfitting, including Reduced-Error Pruning and converting trees to rules.

### Week 4: Linear Regression & Regularization
- Cost function for least squares linear regression and optimization using Gradient Descent or Closed Form solutions.
- Improving learning through feature scaling and standardization to make gradient descent converge faster.
- Understanding model fit (underfitting vs. overfitting) and controlling complexity using L2 Regularization.
- 📝 *Includes In-class assignment on Linear Regression:* Explored model coefficients, intercepts, Sum of Squared Errors, and the impact of data generation parameters.

### Week 5: Linear Classification & The Perceptron
- Using hyperplanes for linear classification and understanding the Perceptron update rule.
- The Perceptron cost function, comparing 0/1 loss with the perceptron criterion.
- Differences between online and batch learning modes, and improvements like Voted or Averaged Perceptrons.
- 📝 *Includes In-class assignment on Perceptron and Multilayer Perceptron:* Covered convergence conditions, handling linearly non-separable data, gradient calculations, and visualization using PCA and t-SNE.

### Week 6: Logistic Regression
- Takes a probabilistic approach to classification by estimating the probability of an instance belonging to a class using the logistic/sigmoid function.
- The objective cost function is derived via Maximum Likelihood Estimation (MLE), which heavily penalizes large prediction mistakes.
- Handling multi-class classification using the One-vs-Rest approach and the softmax function.
- 📝 *Includes In-class assignment on Logistic Regression:* Built a diagnostic model to classify breast tumors as Malignant (1) or Benign (0) using the Breast Cancer Wisconsin Diagnostic dataset. Evaluated the model using a Confusion Matrix, Accuracy, Precision, and Recall.

### Week 7: Performance Evaluation & Perceptrons
- Identifying core classification outcomes: True Positives (TP), True Negatives (TN), False Positives (FP), and False Negatives (FN).
- Computing and interpreting key performance metrics, including Accuracy, Precision, Recall, and F1-score.
- Exploring linear classifiers through practical code examples of binary linear perceptrons and multilayer perceptrons.
- 📝 *Includes In-class assignment on Performance Evaluation Metrics:* Calculated various metrics from a scenario matrix and justified which metric is most important for the given context.

### Week 8: Midterm Exam Week

### Week 9: Guest Speaker Session I
- Special lecture by an invited expert in Reinforcement Learning (RL) and pedagogical approaches.
- Explored the intersection of RL algorithms and human teaching effectiveness.
- Discussed real-world case studies and the challenges of evaluating how learners adapt to algorithmic feedback.

### Week 10: Guest Speaker Session II
- Second session featuring an industry/academic specialist focusing on advanced RL applications.
- Analyzed data-driven strategies for optimizing educational outcomes.
- Interactive discussion on future trends in AI-assisted teaching and personalized learning environments.

### Week 11: Support Vector Machines (SVM) & Kernels
- SVMs aim to find the maximum margin hyperplane to separate classes, which helps reduce model capacity and enhances generalization.
- The "kernel trick" enables SVMs to learn non-linear decision boundaries by implicitly mapping data into a higher-dimensional space without explicit computation.
- Various kernels (Linear, Polynomial, Gaussian/RBF, Sigmoid) allow for different types of data similarity measures and decision surfaces.
- SVMs are effective for both classification and regression, with parameters like 'C' controlling the trade-off between margin maximization and misclassification error.
- 📝 *Includes In-class assignment on SVM:* Explored image classification using SVMs, covering data preprocessing, feature dimensions, and model evaluation metrics.

### Week 12: Ensemble Methods & Neural Networks (CNNs)
- Ensemble Learning: Constructs a strong classifier by combining multiple member classifiers (e.g., Voting, Averaging, Stacking). Diversity is key, as classifiers should make different mistakes to improve overall accuracy.
- Techniques: Bagging (Bootstrap Aggregating) builds trees on bootstrap replicates to reduce variance, while Random Forests further restrict feature subsets to increase diversity. Boosting (specifically AdaBoost) iteratively emphasizes misclassified instances to improve high-bias models.
- Deep Learning (CNNs): Convolutional Neural Networks utilize convolution filters to extract hierarchical features (edges, shapes, object parts) from images.
- CNN Architecture: Composed of Convolutional layers, ReLU activation layers, Pooling (downsampling) layers, and Fully Connected layers.
- 📝 *Includes In-class assignment on Ensemble Models:* Covered VotingClassifiers, BaggingClassifier (with OOB score), Random Forest feature importance, and StackingClassifiers.

### Week 13: Naïve Bayes Classifier
- Probability basics are essential for machine learning, including marginalization, conditional probability, and Bayes' Rule.
- The Naïve Bayes classifier is introduced, which relies on the "naïve" assumption that all attributes are conditionally independent given the class label.
- This classifier simplifies the estimation of the joint distribution $P(X|Y)$ by breaking it into the product of independent probabilities, making it effective for high-dimensional data.
- Parameters are estimated by counting from the training data, with Laplace smoothing (adding 1 to counts) applied to prevent zero-probability issues.
- Log probabilities are utilized during the classification process to prevent numerical underflow.
- 📝 *Includes In-class assignment on Naive-Bayes:* Explored Gaussian Naive Bayes using the `make_blobs` dataset, focusing on visual changes in data clusters and classification performance metrics.

### Week 14: OO
- 

### Week 15: Final Exam Week

### Week 16: Final Exam Week
