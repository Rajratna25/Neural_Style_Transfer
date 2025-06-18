# 🧠🎨 Neural Style Transfer

This project applies **Neural Style Transfer** using TensorFlow and Keras to combine the **content of one image** (e.g. a photo) with the **style of another image** (e.g. a painting).

> Inspired by the work of Gatys et al.  
> Based on tutorials from [GeeksforGeeks](https://www.geeksforgeeks.org/deep-learning/neural-style-transfer-with-tensorflow/) and [TensorFlow.org](https://www.tensorflow.org/tutorials/generative/style_transfer)

---

## ✨ Examples

| Content Image | Style Image | Stylized Result |
|---------------|-------------|-----------------|
| Brandenburg Gate | Starry Night (Van Gogh) | ![output](output_example.jpg) |

---

## 🛠 Features
- Transfer the **style of a painting** to your **own photo**
- Based on **VGG19** feature extraction
- Customizable: style/content weights, epochs, layers
- GPU-ready via Google Colab

---

## 🚀 Run the Notebook

### ▶️ Google Colab (recommended)
Open the project in Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rajratna25/Neural_Style_Transfer/blob/main/notebooks/neural_style_transfer.ipynb)

---

## 📂 Project Structure

```bash
Neural_Style_Transfer/
│
├── notebooks/
│   └── neural_style_transfer.ipynb    # Main Colab notebook
│
├── output_example.jpg                 # Optional output sample
├── README.md
└── requirements.txt (optional)
