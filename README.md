# 🧠 Graph Neural Network using KarateClub Dataset

![Python](https://img.shields.io/badge/Python-3.9-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Geometric-red)
![Project](https://img.shields.io/badge/Project-GNN-green)

This project implements a **Graph Convolutional Network (GCN)** using **PyTorch Geometric** on the **KarateClub dataset** to perform **node classification** and visualize **node embeddings** during training.

---

# 📌 Features

* KarateClub graph dataset
* GCN model implementation
* Node classification
* Training loop with loss & accuracy
* Graph visualization using NetworkX
* Training animation
* 3D embedding visualization
* PyTorch Geometric implementation

---

# 🧩 Dataset

We use the **KarateClub dataset**, a small social network graph:

* Nodes → members
* Edges → relationships
* Task → node classification

---

# 🏗 Model Architecture

GCN Model:

```
Input Features
     ↓
GCN Layer (3 hidden units)
     ↓
ReLU Activation
     ↓
Linear Layer
     ↓
Node Classification
```

---

# 📊 Training

* Loss: CrossEntropyLoss
* Optimizer: Adam
* Epochs: 200
* Learning Rate: 0.02

---

# 📈 Visualizations

The project includes:

* Graph structure visualization
* Training animation
* Node classification color updates
* 3D embedding visualization

---

# 📂 Project Structure

```
.
├── gnn_karateclub.ipynb
└── README.md
```

---

# 🚀 Installation

```bash
pip install torch_geometric
pip install networkx
pip install matplotlib
pip install numpy
```

---

# ▶️ Run

Open the notebook:

```
gnn_karateclub.ipynb
```

Run all cells to train the model and visualize embeddings.

---

# 🖼 Output

* Node classification visualization
* Training animation
* 3D embeddings plot

---

# 🛠 Technologies Used

* PyTorch
* PyTorch Geometric
* NetworkX
* Matplotlib
* NumPy

---

# 🎯 Learning Outcomes

* Understanding Graph Neural Networks
* Message passing in graphs
* Node embeddings
* Graph visualization
* GCN implementation

---

# 👩‍💻 Author

**Nyasa Lohiya**

---
