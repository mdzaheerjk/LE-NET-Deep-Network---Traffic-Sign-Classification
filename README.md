# 🚦 Traffic Sign Classification using LeNet-5 CNN Architecture

A deep learning project that classifies traffic signs using the **LeNet-5** Convolutional Neural Network (CNN) implemented with **Keras**. Trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

> 📌 Project 5 - Part of Deep Learning Course Assignments  
> 📁 Repository: [`LE-NET-Deep-Network---Traffic-Sign-Classification`](https://github.com/mdzaheerjk/LE-NET-Deep-Network---Traffic-Sign-Classification)

---

## 🔍 Problem Statement

Classify 43 types of German traffic signs based on image data using a deep learning model. The task is to recognize traffic signs from the dataset and assign them the correct label.

---

## 📊 Dataset

- **Name:** German Traffic Sign Recognition Benchmark (GTSRB)
- **Total Classes:** 43
- **Format:** PNG images
- **Source:** [Kaggle / Benchmark Link](https://benchmark.ini.rub.de/gtsrb_news.html)

---

## 🧠 Model: LeNet-5 Architecture

| Layer (Type)         | Output Shape | Parameters |
|----------------------|--------------|------------|
| Input (32x32x1)      | -            | 0          |
| Conv2D + ReLU        | 28x28x6      | 156        |
| AvgPool              | 14x14x6      | 0          |
| Conv2D + ReLU        | 10x10x16     | 2,416      |
| AvgPool              | 5x5x16       | 0          |
| Flatten              | 400          | 0          |
| Dense (ReLU)         | 120          | 48,120     |
| Dense (ReLU)         | 84           | 10,164     |
| Output (Softmax)     | 43 classes   | 3,655      |

---

## 🛠️ Technologies Used

- 🐍 Python
- 🧠 TensorFlow / Keras
- 📊 Matplotlib / Seaborn
- 🗃️ NumPy / Pandas
- 📁 Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/mdzaheerjk/LE-NET-Deep-Network---Traffic-Sign-Classification.git
   cd LE-NET-Deep-Network---Traffic-Sign-Classification

### ✅ Install Dependencies
```bash
pip install -r requirements.txt

Project 5 - Traffic Sign Classification Using LeNet Network in Keras.ipynb

```

###  📈 Results

- **Accuracy Achieved:** ~97% on test set  
- **Loss:** Very low after 10+ epochs  
- **Insights:**
  - ✅ Performs well across most traffic sign classes
  - ⚠️ Some errors due to low-light/blurry images

## 📂 Project Structure

```bash
LE-NET-Deep-Network---Traffic-Sign-Classification/
│
├── traffic-signs-data/                        # Dataset directory
├── Project 5 - Traffic Sign Classification Using LeNet Network in Keras.ipynb
├── Project 5 - Traffic Sign Classification Using LeNet.pptx
├── LICENSE
└── README.md



```
## 🎥 Presentation

PowerPoint version of this project:  
📄 `Project 5 - Traffic Sign Classification Using LeNet.pptx`

## ✍️ Author

👨‍💻 **Mohammed Zaheeruddin** (`@mdzaheerjk`)  
🎓 First-Year B.Tech Student | AI & ML Enthusiast  
🏫 Shetty Institute of Technology, Gulbarga  
🌐 [GitHub Profile](https://github.com/mdzaheerjk)

## 🌟 Support

If you found this project helpful, please consider giving it a ⭐!
