# AI & Data Mining Prerequisite Refresher

This repository contains executed Google Colab notebooks with saved outputs and video walkthroughs covering the mathematical and programming foundations needed for AI, machine learning, and data mining.

The notebooks are organized in learning order:

1. Python and scientific-computing tools
2. Linear algebra and tensors
3. Probability and statistics
4. Calculus and optimization
5. The complete machine-learning training loop

## Repository Overview

Add the final Colab and YouTube URLs in the placeholder fields below.

| # | Topic | Colab Notebook | YouTube Video | Status |
|---:|---|---|---|---|
| 01 | Introduction to Python | https://colab.research.google.com/drive/17E_cjURtuCBcPte6qUrMlCCdHRJ0QUB4?authuser=1 | https://youtu.be/3I4x-iQzl8I | ✅ Completed |
| 02 | Introduction to NumPy | https://colab.research.google.com/drive/1YyP6U9_i4ljQPmF6f8tzY9kkEZJzd9vp?authuser=1 | https://youtu.be/wAisLsb27oo | ✅ Completed |
| 03 | Introduction to Pandas | https://colab.research.google.com/drive/1qkK9z4Z4K5-jjV4AZ9dW3MFBtETP3RfL?authuser=1 | https://youtu.be/mUaciusTJ30 | ✅ Completed |
| 04 | Introduction to Matplotlib | https://colab.research.google.com/drive/1PWbv1VTxUL-h8zc7XOBok2yhvTLaPZL8?authuser=1 | https://youtu.be/T9-Sn_1lu5I | ✅ Completed |
| 05 | Intro to Linear Algebra: Zero to Hero for ML | https://colab.research.google.com/drive/1hDWoG3Rff8P9K4XOBpDSvk-t_CT71Qda?authuser=1 | PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 06 | Linear Algebra for Deep Learning | https://colab.research.google.com/drive/1m7Ikj-Rtkb6Y-r1o-Dmz1JL09c5ZiBUv?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 07 | Linear Algebra: The MODEL Box | https://colab.research.google.com/drive/1vxCN42XVuIX16HAsrXA0Aagq7j0WdBNq?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 08 | Intro to Probability: Zero to Hero for ML | https://colab.research.google.com/drive/167UqtMULhmQ56sOyxkhCbivWM41HT2FX?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 09 | Probability Fundamentals for Deep Learning | https://colab.research.google.com/drive/1crKVfbHYS75XskZ_fsiAShONIMNFFqXe?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 10 | Probability & Statistics: The DATA Box | https://colab.research.google.com/drive/1kBe6aGwGwBEu6rGv5fGXlpApNWNLRMII?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 11 | Intro to Statistics: Zero to Hero for ML | https://colab.research.google.com/drive/1FxQBjwbLMUX5hsKwUJJXPF0qVONwuj0T?authuser=1 | PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 12 | Statistics for Deep Learning: Zero to Hero | https://colab.research.google.com/drive/1puj2UGqjq7i7p0sTE5S3gymUe-MOHGxP?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 13 | Intro to Calculus: Zero to Hero for ML | https://colab.research.google.com/drive/13uuWoVizOJWk-XLNpfhqQ4xtmxsL6UAm?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 14 | Calculus for Deep Learning | https://colab.research.google.com/drive/1CG5Dpu4ll9WoF7RRnck1LGlSJAk9I8BR?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 15 | Calculus: The LOSS & UPDATE Boxes | https://colab.research.google.com/drive/1Yw45XNhhW1d41KUw658lPzEnFvZzA1rn?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |
| 16 | The Learning Machine | https://colab.research.google.com/drive/1XS5eHSw0l6tXQ6k9u_VkvdXkVmDRmCLO?authuser=1
| PASTE_YOUTUBE_LINK_HERE | ✅ Completed |

## Colab Playground

The Neural Network Playground is an interactive website, not a Colab notebook:

- https://dlmastery.github.io/neural-network-playground/

It provides a visual way to experiment with data, decision boundaries, hidden layers, activation functions, and training behavior.

## Module Details

### 01. Introduction to Python

- **Colab Notebook:** https://colab.research.google.com/drive/17E_cjURtuCBcPte6qUrMlCCdHRJ0QUB4?authuser=1
- **YouTube Explanation:** https://youtu.be/3I4x-iQzl8I

Core concepts:

- Zero-indexed list retrieval, `.pop()` index removal, and in-place modification.
- Safe dictionary lookups with `.get()` and `.setdefault()` to avoid `KeyError` exceptions.
- ASCII-based character tallying using `ord()` and fixed-size arrays.
- Functional helpers: `map()` for transformations, `enumerate()` for index tracking, and `zip()` for parallel looping.

### 02. Introduction to NumPy

- **Colab Notebook:** https://colab.research.google.com/drive/1YyP6U9_i4ljQPmF6f8tzY9kkEZJzd9vp?authuser=1
- **YouTube Explanation:** https://youtu.be/wAisLsb27oo

Core concepts:

- Array dimensions: 1D vectors, 2D matrices, and 3D tensors such as RGB image data.
- Helper initializations: `np.zeros()`, `np.ones()`, and `np.eye()`.
- Data types and memory: `int32`, `float32`, and `float64`, including why `float32` is common on GPUs.

### 03. Introduction to Pandas

- **Colab Notebook:** https://colab.research.google.com/drive/1qkK9z4Z4K5-jjV4AZ9dW3MFBtETP3RfL?authuser=1
- **YouTube Explanation:** https://youtu.be/mUaciusTJ30

Core concepts:

- Series and DataFrames as 1D and 2D tabular data structures.
- Label-based `.loc` and position-based `.iloc` indexing.
- Missing-value detection and cleaning with `.fillna()` and `.dropna()`.
- Grouping and feature aggregation with `.groupby()`.

### 04. Introduction to Matplotlib

- **Colab Notebook:** https://colab.research.google.com/drive/1PWbv1VTxUL-h8zc7XOBok2yhvTLaPZL8?authuser=1
- **YouTube Explanation:** https://youtu.be/T9-Sn_1lu5I

Core concepts:

- Moving from global `plt.*` calls to explicit `fig, ax = plt.subplots()` figures.
- Understanding Figure, Axes, Axis, and Artist objects.
- Visualizing missing sensor data and corrupted spikes in weather time-series data.
- Tick locators, date formatting, spines, annotations, shared axes, and `GridSpec` layouts.
- Colorblind-safe colormaps and readable multi-panel figures.

### 05. Intro to Linear Algebra: Zero to Hero for ML

- **Executed notebook:** `executed_final_intro_to_linear_algebra_zero_to_hero_for_ml.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1hDWoG3Rff8P9K4XOBpDSvk-t_CT71Qda?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Vectors as arrows, ordered lists, points, and high-dimensional feature representations.
- Vector addition, scaling, norms, distance, projections, and dot products.
- Matrices as transformations that stretch, rotate, shear, reflect, or collapse space.
- Matrix multiplication derived from dot products and applied to complete data batches.
- Linear systems, inverses, rank, singularity, and least squares.
- Eigenvectors and eigenvalues as important directions of a transformation.
- Neural-network layers using `y = Wx + b`.
- PCA built from centering, covariance, eigenvectors, projection, and reconstruction.

### 06. Linear Algebra for Deep Learning

- **Executed notebook:** `executed_linear_algebra_for_deep_learning-2.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1m7Ikj-Rtkb6Y-r1o-Dmz1JL09c5ZiBUv?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Scalars, vectors, matrices, and tensors as deep-learning data structures.
- Dot products as the computation inside a neuron.
- Matrix-vector multiplication and batched matrix multiplication.
- Transpose, inverse, determinant, eigenvalues, eigenvectors, and norms.
- Tensor shapes in image, text, and batch-processing tasks.
- A complete neural-network forward pass with linear layers, ReLU, and softmax.

### 07. Linear Algebra: The MODEL Box

- **Executed notebook:** `executed_final_foundations_2_linear_algebra.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1vxCN42XVuIX16HAsrXA0Aagq7j0WdBNq?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- A matrix as a function that moves space.
- Basis vectors as the columns, or landing spots, of a transformation.
- Dimension changes, rank, determinant, null spaces, and information loss.
- Inverses and the exact conditions required to undo a transformation.
- Eigenvectors as the axes a matrix is built around.
- A neural-network layer as a wide matrix of dot products.
- PCA as covariance eigenvectors applied to data.

### 08. Intro to Probability: Zero to Hero for ML

- **Executed notebook:** `executed_final_intro_to_probability_zero_to_hero_for_ml.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/167UqtMULhmQ56sOyxkhCbivWM41HT2FX?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Outcomes, sample spaces, events, complements, and probability rules.
- AND, OR, inclusion-exclusion, and “at least one” calculations.
- Conditional probability as filtering and re-measuring a smaller world.
- Independence, the multiplication rule, and the difference between `P(A|B)` and `P(B|A)`.
- Bayes’ theorem and the base-rate problem.
- Likelihood, cross-entropy, and Naive Bayes classification.

### 09. Probability Fundamentals for Deep Learning

- **Executed notebook:** `executed_final_probability_fundamentals_for_deep_learning.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1crKVfbHYS75XskZ_fsiAShONIMNFFqXe?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Probability distributions and the Law of Large Numbers.
- Sample spaces, events, complements, and conditional probability.
- Bayes’ theorem and sequential belief updates.
- Discrete and continuous random variables.
- Softmax as a probability mass function over classes.
- Entropy as uncertainty and cross-entropy as negative log-likelihood.

### 10. Probability & Statistics: The DATA Box

- **Executed notebook:** `executed_final_foundations_3_probability.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1kBe6aGwGwBEu6rGv5fGXlpApNWNLRMII?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Conditional probability as shrinking the world and re-measuring.
- Bayes’ theorem derived from symmetry and the law of total probability.
- Rare-disease testing, natural frequencies, false positives, and base-rate effects.
- Bernoulli, Binomial, Gaussian, Uniform, and Poisson distributions.
- Maximum likelihood estimation and the bridge to binary cross-entropy.
- Naive Bayes, conditional independence, smoothing, log probabilities, and numerical underflow.
- Accuracy, confusion matrices, precision, recall, F1, and threshold selection.

### 11. Intro to Statistics: Zero to Hero for ML

- **Executed notebook:** `execute_final_intro_to_statistics_zero_to_hero_for_ml.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1FxQBjwbLMUX5hsKwUJJXPF0qVONwuj0T?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Population parameters versus sample statistics.
- Mean, median, mode, variance, standard deviation, skewness, kurtosis, and percentiles.
- Outliers, robust statistics, sampling bias, and non-response.
- Sampling distributions, the Central Limit Theorem, and standard error.
- Confidence intervals, t-distributions, bootstrapping, and hypothesis testing.
- Correlation, regression, residuals, R-squared, extrapolation, and regression to the mean.
- Multiple comparisons, p-hacking, Simpson’s paradox, survivorship bias, and confounding.
- Train/test evaluation, confidence intervals for accuracy, and cross-validation.

### 12. Statistics for Deep Learning: Zero to Hero

- **Executed notebook:** `executed_final_statistics_for_deep_learning.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1puj2UGqjq7i7p0sTE5S3gymUe-MOHGxP?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Probability distributions, expectation, variance, covariance, and correlation.
- Batch normalization as statistical standardization of activations.
- Sampling and Monte Carlo estimation.
- Regularization as a statistical preference for simpler weights.
- Model evaluation, class imbalance, precision-recall trade-offs, and F1.
- Statistical foundations of model performance and generalization.

### 13. Intro to Calculus: Zero to Hero for ML

- **Executed notebook:** `executed_final_intro_to_calculus_zero_to_hero_for_ml.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/13uuWoVizOJWk-XLNpfhqQ4xtmxsL6UAm?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Functions, graphs, slope, average rate of change, and limits.
- Derivatives from the difference quotient.
- Power, product, quotient, chain, and sigmoid derivative rules.
- Critical points, second derivatives, optimization, and tangent lines.
- Integrals, numerical area, antiderivatives, and the Fundamental Theorem of Calculus.
- Partial derivatives, gradients, multivariable chain rule, Jacobians, and Hessians.
- Gradient descent, learning rates, backpropagation, and numerical gradient checking.

### 14. Calculus for Deep Learning

- **Executed notebook:** `executed_final_calculus_for_deep_learning.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1CG5Dpu4ll9WoF7RRnck1LGlSJAk9I8BR?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Numerical and analytical derivatives.
- Sigmoid, tanh, ReLU, and the vanishing-gradient problem.
- The chain rule through a mini neural network.
- Partial derivatives and gradients as directions of steepest increase.
- Gradient descent and learning-rate behavior.
- Backpropagation through XOR, gradient checking, and PyTorch autograd.

### 15. Calculus: The LOSS & UPDATE Boxes

- **Executed notebook:** `executed_final_foundations_4_calculus.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1Yw45XNhhW1d41KUw658lPzEnFvZzA1rn?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Derivatives as local rates of change and the meaning of the derivative sign.
- Partial derivatives and gradients in multiple dimensions.
- Gradient descent updates and learning-rate stability.
- The chain rule through multiple layers and fan-out paths.
- Backpropagation, transposed weight matrices, and efficient gradient computation.
- Integral calculus as accumulated area and its connection to probability.
- Loss functions as expected values over data.

### 16. The Learning Machine

- **Executed notebook:** `executed_final_foundations_1_the_learning_machine.ipynb`
- **Colab Notebook:** https://colab.research.google.com/drive/1XS5eHSw0l6tXQ6k9u_VkvdXkVmDRmCLO?authuser=1
- **YouTube Explanation:** PASTE_YOUTUBE_LINK_HERE

Core concepts:

- Classical AI, machine learning, and deep learning as nested ideas.
- Supervised, unsupervised, and reinforcement learning.
- Models as changeable parameters that produce predictions.
- Squared error as a loss function.
- Gradients and learning rates as the update mechanism.
- The complete loop: data → prediction → loss → gradient → update.
- Generalization, unseen examples, and overfitting.

## Final Learning Loop

The entire refresher leads to one reusable machine-learning workflow:

```text
data
  → model prediction
  → loss measurement
  → gradient calculation
  → parameter update
  → improved prediction
```

The programming, linear algebra, probability, statistics, and calculus notebooks each explain one part of this loop.
