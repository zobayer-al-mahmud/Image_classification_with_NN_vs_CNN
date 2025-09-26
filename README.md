
# 🧠 Image Classification with NN vs CNN

This project compares the performance of a **basic Neural Network (NN)** and a **Convolutional Neural Network (CNN)** on the **Fashion MNIST** dataset. The goal is to understand how different architectures perform on image classification tasks.

## 📌 Project Overview

* **Dataset:** [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)
* **Images:** 28x28 grayscale, 10 categories of clothing
* **Models Used:**

  * Simple Neural Network (NN)
  * Convolutional Neural Network (CNN)

## ⚙️ Steps Followed

1. Load and preprocess the Fashion MNIST dataset

   * Normalize pixel values to [0,1]
2. Build and train a Neural Network (NN)
3. Build and train a Convolutional Neural Network (CNN)
4. Compare accuracy and performance
5. Visualize results

## 📊 Results

* **NN Accuracy:** ~86%
* **CNN Accuracy:** ~91%
* **Conclusion:** CNN performs better because it captures local patterns (edges, textures) and preserves spatial structure, while NN only looks at flattened pixel values.

## 📦 Libraries Used

```bash
numpy  
matplotlib  
tensorflow / keras  
```

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Image_classification_with_NN_vs_CNN(Zobayer_Al_Mahmud).ipynb
   ```
3. Run the cells step by step.

## 📌 Author

**Zobayer Al Mahmud**


