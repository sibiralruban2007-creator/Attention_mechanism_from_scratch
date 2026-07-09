# 🚀 Scaled Dot-Product Self-Attention Mechanism From Scratch

A Python implementation of the **Scaled Dot-Product Self-Attention** mechanism using **NumPy**. This project demonstrates the core concept behind the attention mechanism used in Transformer-based architectures such as **BERT**, **GPT**, and **Vision Transformers (ViT)**.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [How Self-Attention Works](#-how-self-attention-works)
- [Installation](#-installation)
- [Usage](#-usage)
- [Sample Output](#-sample-output)
- [Learning Outcomes](#-learning-outcomes)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

# 📖 Overview

The **Self-Attention Mechanism** enables a model to determine which parts of the input are most relevant when processing information. It is one of the key components of the Transformer architecture and has significantly advanced the field of Natural Language Processing (NLP).

This project provides a clear implementation of the **Scaled Dot-Product Attention** algorithm using only **Python** and **NumPy**, making it easy to understand the mathematical operations involved without relying on deep learning frameworks.

---

# ✨ Features

- Implementation from scratch using Python
- Uses only the NumPy library
- Computes Query (Q), Key (K), and Value (V) matrices
- Calculates Attention Scores
- Applies Scaled Dot-Product Attention
- Uses Softmax for attention weight calculation
- Generates the final attention output
- Beginner-friendly and well-commented code

---

# 📁 Project Structure

```
attention-mechanism-from-scratch/
│
├── Attention_Mechanism.ipynb
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🛠️ Technologies Used

- Python 3.x
- NumPy
- Jupyter Notebook

---

# ⚙️ How Self-Attention Works

The implementation follows these steps:

### Step 1: Create Input Embeddings

Input tokens are represented as embedding vectors.

### Step 2: Initialize Weight Matrices

Three learnable weight matrices are created:

- Query Weight Matrix (WQ)
- Key Weight Matrix (WK)
- Value Weight Matrix (WV)

### Step 3: Compute Query, Key, and Value

```
Q = X × WQ
K = X × WK
V = X × WV
```

### Step 4: Compute Attention Scores

```
Scores = Q × Kᵀ
```

### Step 5: Scale the Scores

```
Scaled Scores = Scores / √dₖ
```

where **dₖ** is the dimension of the key vectors.

### Step 6: Apply Softmax

```
Attention Weights = Softmax(Scaled Scores)
```

### Step 7: Compute Final Output

```
Attention Output = Attention Weights × V
```

---

# 💻 Installation

Clone the repository:

```bash
git clone https://github.com/sibiralruban2007-creator/attention-mechanism-from-scratch.git
```

Move to the project directory:

```bash
cd attention-mechanism-from-scratch
```

Install the required package:

```bash
pip install numpy
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open **Attention_Mechanism.ipynb** and run all cells.

---

# ▶️ Usage

Run the notebook to observe the following outputs:

- Input Embeddings
- Query Matrix (Q)
- Key Matrix (K)
- Value Matrix (V)
- Attention Scores
- Scaled Attention Scores
- Attention Weights
- Final Attention Output

---

# 📊 Sample Output

The notebook prints:

- Input Embedding Matrix
- Query Matrix
- Key Matrix
- Value Matrix
- Attention Score Matrix
- Scaled Attention Scores
- Softmax Attention Weights
- Final Self-Attention Output

---

# 🎯 Learning Outcomes

After completing this project, you will understand:

- Self-Attention Mechanism
- Query, Key, and Value (QKV)
- Scaled Dot-Product Attention
- Matrix Multiplication
- Softmax Function
- Transformer Fundamentals
- NumPy Matrix Operations

---

# 🚀 Future Enhancements

- Multi-Head Attention
- Positional Encoding
- Masked Self-Attention
- Transformer Encoder
- Transformer Decoder
- Attention Visualization
- PyTorch Implementation
- TensorFlow Implementation

---

# 🤝 Contributing

Contributions are welcome.

To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to your branch.
5. Submit a Pull Request.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

## Sibiral Ruban

**B.Sc. Computer Science with Artificial Intelligence**

- GitHub: https://github.com/sibiralruban2007-creator
- LinkedIn: https://www.linkedin.com/in/your-linkedin-profile

---

## ⭐ Support

If you found this project helpful, please consider giving it a **Star ⭐** on GitHub.

Your support is greatly appreciated.

