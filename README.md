# 🔄 Project Workflow

This project demonstrates the implementation of the **Scaled Dot-Product Self-Attention Mechanism** from scratch using **Python** and **NumPy** in a **Jupyter Notebook**. The workflow followed in this project is described below.

## Step 1: Import Required Library

The project begins by importing the **NumPy** library, which provides efficient support for numerical computations and matrix operations.

```python
import numpy as np
```

---

## Step 2: Define Input Embeddings

A sample input embedding matrix is created to represent the input sequence. Each row corresponds to an input token represented as a numerical vector.

---

## Step 3: Initialize Weight Matrices

Three random weight matrices are initialized using NumPy:

- **Query Weight Matrix (WQ)**
- **Key Weight Matrix (WK)**
- **Value Weight Matrix (WV)**

These matrices are used to transform the input embeddings into Query, Key, and Value representations.

---

## Step 4: Compute Query, Key, and Value Matrices

The Query (Q), Key (K), and Value (V) matrices are computed through matrix multiplication.

```
Q = X × WQ
K = X × WK
V = X × WV
```

---

## Step 5: Compute Attention Scores

Attention scores are calculated by multiplying the Query matrix with the transpose of the Key matrix.

```
Scores = Q × Kᵀ
```

These scores indicate the relationship between different input tokens.

---

## Step 6: Scale the Attention Scores

The attention scores are divided by the square root of the key dimension (√dₖ) to stabilize the values before applying the Softmax function.

```
Scaled Scores = Scores / √dₖ
```

---

## Step 7: Apply the Softmax Function

The Softmax function converts the scaled scores into probability values known as **Attention Weights**.

These weights determine how much importance each input token receives.

---

## Step 8: Generate the Final Attention Output

The attention weights are multiplied by the Value matrix to produce the final context-aware attention output.

```
Attention Output = Attention Weights × V
```

---

# 📊 Results

- Successfully implemented the Scaled Dot-Product Self-Attention mechanism.
- Generated Query (Q), Key (K), and Value (V) matrices.
- Computed Attention Scores and Scaled Attention Scores.
- Applied the Softmax function to obtain Attention Weights.
- Produced the Final Attention Output.
- Demonstrated the fundamental working principle of the Self-Attention mechanism used in Transformer models.

---

# 📸 Output Screenshot

The following screenshot demonstrates the successful execution of the project in Jupyter Notebook.
<img width="341" height="495" alt="image" src="https://github.com/user-attachments/assets/c3b5fcd5-e137-4c58-936f-4a29f98c6503" />







# 🎯 Conclusion

This project provides a clear and practical implementation of the **Scaled Dot-Product Self-Attention Mechanism** using Python and NumPy. It serves as a strong foundation for understanding Transformer architectures and prepares learners for implementing advanced concepts such as Multi-Head Attention, Positional Encoding, and complete Transformer models.
