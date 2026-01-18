# NumPy for Data Science & Data Analytics

A structured, beginner-to-intermediate roadmap to learn **NumPy** with a focus on **Data Science** and **Data Analytics** use cases.

---

## What is NumPy?

NumPy (Numerical Python) is the core Python library for **numerical computing**. It provides:

* Fast N-dimensional arrays (`ndarray`)
* Vectorized mathematical operations
* Linear algebra, statistics, and random sampling
* The foundation for libraries like **Pandas, Scikit-learn, TensorFlow, PyTorch**

If you work with data, NumPy is non-negotiable.

---

## Why NumPy for Data Science & Analytics?

* Processes large datasets faster than Python lists
* Enables vectorized computations (no loops)
* Backbone of data preprocessing pipelines
* Required for ML, statistics, and scientific computing

---

## Prerequisites

* Basic Python (variables, loops, functions)
* Basic math (mean, variance, matrices – optional but helpful)

---

## Installation

```bash
pip install numpy
```

Verify:

```python
import numpy as np
print(np.__version__)
```

---

## Learning Roadmap

### 1. NumPy Basics

* Importing NumPy
* Creating arrays

  * `array()`
  * `zeros()`, `ones()`, `arange()`, `linspace()`
* Array attributes

  * `ndim`, `shape`, `size`, `dtype`

### 2. Indexing & Slicing

* 1D, 2D, 3D indexing
* Boolean indexing
* Fancy indexing
* Views vs Copies

### 3. Data Types & Type Casting

* Numeric dtypes (`int32`, `float64`)
* Type conversion using `astype()`
* Memory efficiency

### 4. Array Operations (Core for Analytics)

* Element-wise operations
* Broadcasting
* Arithmetic operations
* Comparison and logical operations

### 5. Mathematical & Statistical Functions

* Aggregations

  * `sum()`, `mean()`, `median()`, `std()`, `var()`
* Axis-based operations
* Min/Max, Argmin/Argmax

### 6. Shape Manipulation

* `reshape()`
* `flatten()` vs `ravel()`
* `transpose()`
* `expand_dims()`
* `squeeze()`

### 7. Combining & Splitting Arrays

* `concatenate()`
* `stack()`, `hstack()`, `vstack()`
* `split()`, `hsplit()`, `vsplit()`

### 8. Linear Algebra (Important for ML)

* Matrix multiplication (`dot`, `@`)
* Determinant, inverse
* Eigenvalues and eigenvectors
* Solving linear equations

### 9. Random Module (Data Simulation)

* `rand()`, `randn()`
* `randint()`
* `choice()`
* Seeding for reproducibility

### 10. File Input & Output

* Load data from files

  * `loadtxt()`
  * `genfromtxt()`
* Save arrays

  * `savetxt()`
  * `save()` / `load()`

---

## NumPy for Data Analytics (Practical Use)

### Data Cleaning

* Handling missing values (`np.nan`)
* Replacing values
* Filtering rows using conditions

### Exploratory Data Analysis (EDA)

* Descriptive statistics
* Percentiles and quantiles
* Frequency analysis

### Performance Optimization

* Vectorization vs loops
* Memory-efficient operations

---

## NumPy for Data Science & ML

* Feature scaling
* Normalization & standardization
* Distance calculations
* Data preprocessing before Pandas / ML models

---

## Mini Projects (Recommended)

1. Student CGPA vs Package Analysis
2. Sales data analysis (Year-wise trends)
3. Matrix-based recommendation scoring
4. Random data simulation for ML training

---

## Common Mistakes to Avoid

* Using Python loops instead of vectorization
* Confusing views and copies
* Ignoring broadcasting rules
* Using wrong axis in aggregations

---

## NumPy vs Pandas

| NumPy            | Pandas                   |
| ---------------- | ------------------------ |
| Numerical arrays | Labeled data (tables)    |
| Faster           | More user-friendly       |
| Math-heavy tasks | Data analysis & cleaning |

Use **NumPy** for computation, **Pandas** for analysis.

---

## Recommended Learning Order

1. NumPy basics & arrays
2. Indexing & slicing
3. Mathematical operations
4. Statistics & aggregations
5. Real-world datasets
6. Integration with Pandas & ML

---

## Resources

* Official NumPy Documentation
* NumPy User Guide
* Kaggle notebooks using NumPy
* Practice on real CSV datasets

---

## Goal Outcome

After completing this roadmap, you should be able to:

* Efficiently manipulate numerical datasets
* Perform fast data analysis
* Prepare data for ML pipelines
* Understand the internal working of data science libraries

---


