# 🫁 X-Ray Image Classification — Pneumonia, COVID & Lung Opacity Using CNN

A deep learning project that classifies chest X-ray images into **Pneumonia, COVID-19, Lung Opacity, and Normal** categories using Convolutional Neural Networks (CNN).

---

## 📖 About

This project applies CNNs to medical imaging, specifically chest X-rays, to assist in the early detection and classification of respiratory diseases. Two model variants are included with slightly different architectures, allowing experimentation with different input sizes.

---

## 📂 Repository Structure

```
Classification-of-X-RAY.../
├── CNN.py                        # CNN model architecture
├── train_cnn.py                  # Training script
├── network.txt                   # Network architecture summary
├── new.txt                       # Additional notes
├── Accuracy_curve_CNN_255.jpg    # Accuracy curve (255 input size)
├── Accuracy_curve_CNN_256.jpg    # Accuracy curve (256 input size)
├── Loss_curve_CNN_255.jpg        # Loss curve (255 input size)
├── Loss_curve_CNN_256.jpg        # Loss curve (256 input size)
└── README.md
```

---

## ✨ Features

- Multi-class classification: **Normal / Pneumonia / COVID-19 / Lung Opacity**
- Two CNN variants (255×255 and 256×256 input sizes)
- Accuracy and loss curve visualizations
- Easily adaptable to any chest X-ray dataset from Kaggle

---

## 📦 Dataset

The original dataset is available on Kaggle (chest X-ray images). You can adapt the code to any similar dataset with minimal changes.

🔗 Search: *"COVID-19 Radiography Database"* on [Kaggle](https://www.kaggle.com)

---

## 🛠️ Tech Stack

| Library | Purpose |
|--------|---------|
| `TensorFlow` / `Keras` | CNN model building and training |
| `NumPy` | Array operations |
| `Matplotlib` | Plotting accuracy/loss curves |
| `OpenCV` | Image loading and preprocessing |

---

## 🚀 Getting Started

### Install Dependencies

```bash
pip install tensorflow numpy matplotlib opencv-python
```

### Train the Model

```bash
git clone https://github.com/nauman07/Classification-of-X-RAY-Image-of-Pneumonia-Covid-Lung-Opacity-Patients-Using-CNN.git
cd Classification-of-X-RAY-Image-of-Pneumonia-Covid-Lung-Opacity-Patients-Using-CNN
python train_cnn.py
```

### Dataset Setup

Organize your dataset in the following structure:
```
dataset/
├── train/
│   ├── Normal/
│   ├── Pneumonia/
│   ├── COVID/
│   └── Lung_Opacity/
└── test/
    ├── Normal/
    ├── Pneumonia/
    ├── COVID/
    └── Lung_Opacity/
```

---

## 📈 Results

Training accuracy and loss curves are included in the repository for both model configurations (255 and 256 input sizes).

---

## ⚠️ Disclaimer

This project is for **research and educational purposes only**. It is not intended for clinical diagnosis.

---

## 🤝 Contributing

Pull requests are welcome. Open an issue for any bugs or feature requests.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
