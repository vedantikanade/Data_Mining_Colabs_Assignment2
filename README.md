# AI & Data Mining Prerequisite Refresher

This repository contains my executed Google Colab notebooks (with all outputs saved) and YouTube video walkthroughs for the prerequisite refresher modules in AI, Machine Learning, and Data Mining.

---

## 📌 Repository Overview & Video Links

| # | Topic | Colab Notebook | YouTube Video Link | Status |
| :--- | :--- | :--- | :--- | :--- |
| **01** | Introduction to Python: | https://colab.research.google.com/drive/17E_cjURtuCBcPte6qUrMlCCdHRJ0QUB4?authuser=1 | https://youtu.be/3I4x-iQzl8I | ✅ Completed |
| **02** | Introduction to NumPy | https://colab.research.google.com/drive/1YyP6U9_i4ljQPmF6f8tzY9kkEZJzd9vp?authuser=1 | https://youtu.be/wAisLsb27oo  | ✅ Completed |
| **03** | Introduction to Pandas | https://colab.research.google.com/drive/1qkK9z4Z4K5-jjV4AZ9dW3MFBtETP3RfL?authuser=1 | https://youtu.be/mUaciusTJ30 | ✅ Completed |
| **04** | Introduction to matplotlib | https://colab.research.google.com/drive/1PWbv1VTxUL-h8zc7XOBok2yhvTLaPZL8?authuser=1#scrollTo=SJoenKNKuUXb | | |
| **05** | Linear Algebra & Tensors | https://colab.research.google.com/drive/1Sx-IO5N7MoD1nHqKMpNj44AdwIBrSvP0 | | |
| **06** | Probability & Statistics |   | ⏳ Pending |
| **07** | Calculus & Optimization |   | ⏳ Pending |
| **08** | Scikit-Learn Overview |   | ⏳ Pending |
| **09** | Data Preprocessing |   | ⏳ Pending |
| **10** | Neural Network Fundamentals |   | ⏳ Pending |
| **11** | PyTorch Fundamentals |   | ⏳ Pending |
| **12** | TensorFlow Basics |   | ⏳ Pending |
| **13** | Model Evaluation |   | ⏳ Pending |
| **14** | Convolutional Networks |   | ⏳ Pending |
| **15** | Recurrent Networks & Sequence Models |   | ⏳ Pending |
| **16** | Transformers & Advanced Topics |   | ⏳ Pending |

---

## 📝 Module Summaries & Direct Video Links

### 01. Introduction to Python
* **Colab Notebook:** https://colab.research.google.com/drive/17E_cjURtuCBcPte6qUrMlCCdHRJ0QUB4?authuser=1
* **YouTube Explanation:** https://youtu.be/3I4x-iQzl8I
* **Core Concepts:**
  * Zero-indexed list retrieval, `.pop()` index removal, and in-place modification.
  * Safe dictionary lookups with `.get()` and `.setdefault()` to avoid `KeyError` exceptions.
  * ASCII-based character tallying using `ord()` and fixed-size arrays.
  * Functional helpers: `map()` for transformations, `enumerate()` for index tracking, and `zip()` for parallel looping.

---

### 02. Introduction to NumPy
* **Colab Notebook:** https://colab.research.google.com/drive/1YyP6U9_i4ljQPmF6f8tzY9kkEZJzd9vp?authuser=1
* **YouTube Explanation:** https://youtu.be/wAisLsb27oo
* **Core Concepts:**
  * Array dimensions: 1D vectors, 2D matrices, and 3D tensors (e.g., RGB channels).
  * Helper initializations: `np.zeros()` for bias terms, `np.ones()` for masks, and `np.eye()` for skip connections in ResNets.
  * Precision and RAM: comparing `int32`, `float32`, and `float64`, highlighting why `float32` is standard for GPU memory efficiency.

---

### 03. Introduction to Pandas
* **Colab Notebook:** https://colab.research.google.com/drive/1qkK9z4Z4K5-jjV4AZ9dW3MFBtETP3RfL?authuser=1
* **YouTube Explanation:** https://youtu.be/mUaciusTJ30
* **Core Concepts:**
  * Tabular data abstractions using 1D Series and 2D DataFrames.
  * Indexing and slicing via `.loc` (label-based) and `.iloc` (integer position-based).
  * Data cleaning routines: detecting missing values, handling nulls with `.fillna()`, and dropping rows with `.dropna()`.
  * Group operations and feature aggregation using `.groupby()`.

---

### 04. Data Visualization (Matplotlib)
* **Colab Notebook:** https://colab.research.google.com/drive/1PWbv1VTxUL-h8zc7XOBok2yhvTLaPZL8?authuser=1#scrollTo=SJoenKNKuUXb
* **YouTube Explanation:** 
* **Core Concepts:**
  * Transitioning from global state functions (`plt.*`) to `fig, ax = plt.subplots()` for explicit visual control.
  * Understanding `Figure`, `Axes`, `Axis`, and `Artist` objects to diagnose and fix formatting issues on sight.
  * Uncovering real-world data issues (missing sensor gaps, corrupted spikes) across multi-station weather time-series data.
  * Configuring tick locators, date formatting, spines, and direct callout annotations (`ax.annotate`).
  * Constructing multi-panel figures with `GridSpec`, using shared axes, and applying colorblind-safe colormaps.
 
  ---
  
### 05. Intro to Linear Algebra
* **Colab Notebook:** https://colab.research.google.com/drive/1Sx-IO5N7MoD1nHqKMpNj44AdwIBrSvP0
* **YouTube Explanation:** 
* **Core Concepts:**
  * Vectors as geometric arrows, lists, and points, along with vector arithmetic, scaling, and length/norm calculations.
  * Geometric and algebraic properties of the dot product as a core measure of similarity between vectors.
  * Viewing matrices as active spatial transformations (stretching, rotation, reflection) rather than static data tables.
  * Deriving matrix multiplication from dot products, solving linear systems, and finding matrix inverses.
  * Eigenvectors and eigenvalues as invariant transformation directions, leading into machine learning applications like linear layers ($y = Wx + b$) and Principal Component Analysis (PCA).
