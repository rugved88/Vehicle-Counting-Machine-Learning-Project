# Vehicle-Counting-Machine-Learning-Project

## TRANCOS Dataset Vehicle Counting 🚦🚘

This project implements a deep learning model to count vehicles in images from the TRANCOS dataset using Python and TensorFlow. It includes data preprocessing, model training, and visualization of results.

## Getting Started

### Prerequisites 👇🏻

Before running this project, you need to have Python installed along with the following libraries:
- OpenCV
- NumPy
- SciPy
- TensorFlow
- Matplotlib (for data visualization)

You can install these dependencies via pip:

```bash
pip install opencv-python numpy scipy tensorflow matplotlib
```

## 📦 Dataset
The TRANCOS dataset is used for training and evaluating the model. It needs to be downloaded and placed in a specific directory structure:
- 📥 Download the TRANCOS dataset from [the official website](http://agamenon.tsc.uah.es/Personales/rlopez/data/trancos/).
- 📁 Ensure the dataset is located at `C:/Users/<YourUsername>/Desktop/UVA-Course/machine learning/dataset/TRANCOS_v3`.

## 🚀 Usage
1. 📋 Clone the repository to your local machine.
2. 🗃️ Ensure the dataset is placed in the correct directory as mentioned above.
3. ▶️ Run the main script to start the training process:

## 🏗️ Model Architecture
This project uses a modified VGG16 model for the task of vehicle counting. The architecture is adjusted for the specifics of the TRANCOS dataset and includes custom layers on top of the pre-trained VGG16 base.

## 🔄 Data Preprocessing
Data preprocessing involves resizing images, applying data augmentation techniques, and preparing masks for accurate vehicle counting.

## 🖼️ Visualization
The project includes functionality to visualize the original images along with their vehicle annotations and masks to verify the preprocessing and training results.

## 📈 Results

### Performance Metrics
- **Mean Absolute Error (MAE):**  7.8346📉
- **Loss:** 121.1611  📊

### Training and Validation Loss Graphs
_Add training and validation loss graphs here._ 📉📈

### Model Results After Quantization and Pruning
_Describe or show the results after applying quantization and pruning to the model._ ✂️🔍

## 👥 Contributing
Contributions to this project are welcome. Please feel free to fork the repository, make your changes, and submit a pull request. 🤝

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details. ©️

## 🙏 Acknowledgments
- Thanks to the creators of the TRANCOS dataset for providing a rich dataset for vehicle counting research. 🎉
- This project was inspired by the need for accurate vehicle counting in traffic management systems. 🚗🚦
Acknowledgments
Thanks to the creators of the TRANCOS dataset for providing a rich dataset for vehicle counting research.
This project was inspired by the need for accurate vehicle counting in traffic management systems.
