# 🧠 Simple Neural Network Implementation from Scratch

This project demonstrates the implementation of a **basic neural network from scratch**, without using deep learning frameworks like TensorFlow or PyTorch. Instead, it uses **only NumPy** to handle matrix operations and manual implementation of **forward propagation, backpropagation, and gradient descent**.

The project serves as an educational resource for understanding how neural networks work under the hood.

---

## 📌 Features

* Fully connected **feedforward neural network** implementation
* Supports **forward propagation** and **backpropagation**
* Uses **gradient descent optimization**
* Trains on a simple dataset (e.g., XOR, MNIST, or custom data)
* Visualizes **loss curve** during training
* No external ML libraries – only **NumPy**

---

## 📂 Project Structure

```
├── data/                  # Dataset (optional, e.g., MNIST)
├── notebooks/             # Jupyter notebooks for step-by-step explanation
├── src/                   # Source code
│   ├── neural_network.py  # Core implementation (from scratch)
│   ├── train.py           # Training loop
│   ├── evaluate.py        # Model evaluation
│   └── utils.py           # Helper functions (activation, plotting)
├── results/               # Training logs and plots
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/simple-nn-scratch.git
cd simple-nn-scratch
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Training

```bash
python src/train.py
```

### 4️⃣ Evaluate Model

```bash
python src/evaluate.py
```

---

## 🧮 Neural Network Architecture

* Input Layer: Accepts input features
* Hidden Layer(s): Fully connected with activation functions
* Output Layer: Predicts class probabilities

**Implemented Components:**

* Sigmoid, ReLU, Softmax activations
* Cross-Entropy / MSE loss functions
* Backpropagation with gradient descent

---

## 📊 Results

* Successfully classifies simple datasets (e.g., XOR, linearly separable data)
* Extensible to MNIST digit classification (with minor changes)

**Sample Output (XOR training):**

| Input   | Expected | Predicted |
| ------- | -------- | --------- |
| \[0, 0] | 0        | 0.01      |
| \[0, 1] | 1        | 0.98      |
| \[1, 0] | 1        | 0.97      |
| \[1, 1] | 0        | 0.05      |

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** NumPy, Matplotlib (for visualization)

---

## 📌 Applications

* Educational tool for understanding **neural networks**
* Step toward implementing **more advanced models**
* Useful for those preparing for **ML/DL interviews**

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 🙌 Acknowledgements

* Inspired by Andrew Ng’s **Deep Learning Specialization**
* Based on core principles from “Neural Networks and Deep Learning” by Michael Nielsen

---
