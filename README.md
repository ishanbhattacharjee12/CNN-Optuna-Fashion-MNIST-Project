# Fashion Neural Net (CNN + Optuna)

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?logo=pytorch&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter_Tuning-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📖 Project Overview

**Fashion Neural Net** is an advanced image classification model built from scratch using PyTorch. The goal of the project is to accurately classify the 60,000 images in the Fashion MNIST dataset across 10 distinct clothing categories.

To achieve maximum performance without manual guesswork, the network integrates **Optuna**, a hyperparameter optimization framework, to automatically tune the learning rate, dropout rates, and layer dimensions, ultimately achieving a robust **94% validation accuracy**.

---

## ✨ Features

- **Custom CNN Architecture**: A deep Convolutional Neural Network designed with PyTorch.
- **Optuna Integration**: Automated hyperparameter searching to find the global minimum loss.
- **High Accuracy**: Reaches state-of-the-art performance (~94%) on the complex Fashion MNIST test set.
- **Scalable Pipeline**: Clean PyTorch Dataset & DataLoader implementation for rapid batch processing.

---

## 🛠 Tech Stack

| Layer       | Technology                                          |
|-------------|-----------------------------------------------------|
| **Core**    | Python 3.11                                         |
| **AI/ML**   | PyTorch, Torchvision, Numpy                         |
| **MLOps**   | Optuna (Hyperparameter Tuning)                      |

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ishanbhattacharjee12/CNN-Optuna-Fashion-MNIST-Project.git
   cd CNN-Optuna-Fashion-MNIST-Project
   ```

2. Install dependencies:
   ```bash
   pip install torch torchvision optuna matplotlib numpy
   ```

3. Run the notebook to start the Optuna trials and train the final CNN architecture.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

## 📝 License
This project is [MIT](LICENSE) licensed.
