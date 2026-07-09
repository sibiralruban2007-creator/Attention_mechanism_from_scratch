# 🚀 Scaled Dot-Product Self-Attention Mechanism From Scratch

> A beginner-friendly implementation of the **Scaled Dot-Product Self-Attention** mechanism using **Python** and **NumPy**, demonstrating the fundamental building block of Transformer architectures.

---

## 📖 Overview

The Attention Mechanism is one of the most important innovations in modern Artificial Intelligence and Natural Language Processing (NLP). It enables models to focus on the most relevant parts of the input sequence, improving contextual understanding and overall performance.

This project implements the **Scaled Dot-Product Self-Attention** algorithm from scratch using only **NumPy**, providing a clear understanding of how attention works internally without relying on deep learning frameworks such as TensorFlow or PyTorch.

---

## ✨ Features

- ✅ Built entirely with Python and NumPy
- ✅ Computes Query (Q), Key (K), and Value (V) matrices
- ✅ Implements Scaled Dot-Product Attention
- ✅ Applies the Softmax function to obtain attention weights
- ✅ Generates the final attention output
- ✅ Clean and easy-to-understand implementation
- ✅ Suitable for beginners learning Transformer models

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3 | Programming Language |
| NumPy | Matrix Operations |
| Jupyter Notebook | Development Environment |

---

## 📂 Project Structure

```text
attention-mechanism-from-scratch/
│
├── Attention_Mechanism.ipynb
├── README.md
├── requirements.txt
└── LICENSE
```

---

## ⚙️ Algorithm

The implementation follows these steps:

1. Create Input Embeddings
2. Initialize Weight Matrices
3. Generate Query (Q), Key (K), and Value (V)
4. Compute Attention Scores

\[
Scores = QK^T
\]

5. Scale the Scores

\[
Scaled\ Scores = \frac{Scores}{\sqrt{d_k}}
\]

6. Apply Softmax

\[
Attention\ Weights = Softmax(Scaled\ Scores)
\]

7. Generate Final Output

\[
Output = Attention\ Weights \times V
\]

---

## ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/sibiralruban2007-creator/attention-mechanism-from-scratch.git
```

### Navigate to the Project Folder

```bash
cd attention-mechanism-from-scratch
```

### Install Dependencies

```bash
pip install numpy
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **Attention_Mechanism.ipynb** and run all cells.

---

## 📊 Output

The program generates:

- Input Embeddings
- Query Matrix (Q)
- Key Matrix (K)
- Value Matrix (V)
- Attention Scores
- Scaled Attention Scores
- Attention Weights
- Final Attention Output

---

## 🎯 Learning Objectives

This project helps you understand:

- Self-Attention Mechanism
- Query, Key, and Value (QKV)
- Scaled Dot-Product Attention
- Softmax Function
- Matrix Multiplication
- Transformer Fundamentals

---

## 🚀 Future Improvements

- Multi-Head Attention
- Positional Encoding
- Masked Self-Attention
- Transformer Encoder
- Transformer Decoder
- Attention Visualization

---

## 🤝 Contributing

Contributions are welcome.

1. Fork this repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Sibiral Ruban**

**B.Sc. Computer Science with Artificial Intelligence**

- 🌐 GitHub: https://github.com/sibiralruban2007-creator
- 💼 LinkedIn: https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME

---

## ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub. Your support is greatly appreciated!
