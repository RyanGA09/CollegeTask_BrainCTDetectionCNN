# BrainCT-Detection-CNN

## Project Description

This project utilizes a Convolutional Neural Network (CNN) to detect brain diseases based on CT scan images. The model is developed using TensorFlow and Keras, with image preprocessing and data augmentation to improve classification accuracy.

## Dataset

The dataset consists of three brain disease classes:

- CTBrain_aneurysm
- CTBrain_cancer
- CTBrain_tumor

## Dataset directory structure

```
healthy/
|-- data_train/
| |-- CTBrain_aneurysm/
| |-- CTBrain_cancer/
| |-- CTBrain_tumor/
|
|-- data_test/
| |-- CTBrain_aneurysm/
| |-- CTBrain_cancer/
| |-- CTBrain_tumor/
```

## Installation

To run this project, ensure you have Python and the required libraries installed:

```bash
pip install tensorflow numpy matplotlib opencv-python scikit-learn

```

## Usage

1. Run the .ipynb file in Jupyter Notebook or Google Colab.
2. The model will be trained using the available dataset.
3. Model evaluation is conducted by calculating accuracy on test data.
4. Users can upload a CT scan image for model testing.

## 🎯Prediction Example

Jika pengguna memilih gambar input, model akan menampilkan hasil seperti berikut:

```bash
Detected Class: CTBrain_tumor
```

Disertai dengan visualisasi gambar input.

## LICENSE

Copyright &copy; 2025 Ryan Gading Abdullah. All rights reserved.

This project is licensed under the MIT License - see the [MIT License](LICENSE) for details.
