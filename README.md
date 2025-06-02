# PRODIGY_ML_03
This project uses the SVM algorithm to classify images of cats and dogs from the Kaggle dataset. Images are resized, features are extracted using HOG, and an SVM model is trained to accurately distinguish between cat and dog images.
# Cat vs Dog Image Classification using SVM 🐱🐶

This project implements an image classifier to distinguish between cat and dog images using a Support Vector Machine (SVM).

## 📁 Dataset
- [Kaggle Dogs vs Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

## 🧠 ML Model
- Support Vector Machine (SVM) with linear kernel
- Images resized to 64x64 and converted to grayscale

## 🔧 Technologies Used
- Python
- OpenCV
- scikit-learn
- NumPy
- Jupyter Notebook

## 📦 How to Run
1. Clone the repo
2. Install libraries
3. Open `svm_cat_dog_classifier.ipynb`
4. Train or load the model
5. Run predictions on test images

## 🧠 Model Details

- **Model:** Support Vector Machine (SVM)  
- **Kernel:** Linear  
- **Input:** Grayscale images resized to 64x64 pixels  
- **Flattened input size:** 4096 features per image  
- **Output:** 0 for Dog, 1 for Cat  

## 📦 Requirements

Install the following Python libraries before running the notebook:

pip install numpy
pip install matplotlib
pip install opencv-python
pip install scikit-learn
pip install tqdm
pip install joblib

