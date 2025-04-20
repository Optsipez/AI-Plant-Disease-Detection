# 🌿 Plant Disease Detection using Deep Learning

This repository contains a deep learning model built using Convolutional Neural Networks (CNN) to classify plant leaf diseases from images. It aims to assist farmers and agricultural professionals in early detection of plant diseases using AI.

## 📁 Files Included

- PlantModel.ipynb: Jupyter notebook for data preprocessing, model training, evaluation, and optional TFLite model conversion (currently commented out).
- trained_model.h5: Final trained model saved in Keras .h5 format.

## 🧠 Model Features

- ✅ Built using TensorFlow and Keras
- ✅ Custom CNN for image classification
- ✅ High accuracy on test dataset
- ✅ Ready for deployment (.h5 format)
- 🚫 TFLite conversion code present but currently commented out

## 📥 Dataset

The dataset used for training and testing is sourced from Mendeley Data:

🔗 Plant Village Dataset - Mendeley: https://data.mendeley.com/datasets/tywbtsjrjv/1

The dataset contains images of healthy and diseased plant leaves categorized by type.

Expected folder structure:
- /dataset
  - /Tomato___Leaf_Mold
  - /Tomato___Healthy
  - /Potato___Early_blight
  - ...

## 🚀 Getting Started

1. Clone the repository
   https://github.com/Optsipez/AI-Plant-Disease-Detection.git
   
   cd AI-Plant-Disease-Detection

3. Install the dependencies
   pip install tensorflow opencv-python matplotlib

4. Run the notebook
   Open PlantModel.ipynb in Jupyter Notebook and run the cells sequentially to:
   - Load and preprocess images
   - Train and evaluate the CNN model
   - (Optional) Export to TFLite by uncommenting the relevant section

## 📄 License

This project is licensed under the MIT License.  
Feel free to use, modify, and distribute it — just give appropriate credit.

## 🙌 Acknowledgments

- Dataset: Mendeley Data - Plant Leaf Disease (https://data.mendeley.com/datasets/tywbtsjrjv/1)
- Built using TensorFlow, Keras, and OpenCV
- Inspired by the need for smarter, AI-powered agriculture 🌾

