This project aims to classify MRI brain images into four categories — Glioma, Meningioma, Pituitary Tumor, and No Tumor — using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The dataset is preprocessed, augmented, split into training and testing sets, and passed through a custom deep learning model to perform multi-class classification.

📂 Dataset

The dataset used contains labeled MRI brain images categorized into:

glioma_tumor

meningioma_tumor

no_tumor

pituitary_tumor

Images are resized to 150×150×3 and normalized before training.

🏗️ Model Architecture

The model is built using Multiple Convolution Layers, MaxPooling, Dropout, and Dense Layers, followed by a Softmax classifier for predicting tumor type.
Loss Function: categorical_crossentropy
Optimizer: Adam
Metrics: Accuracy

🚀 Features

✔ Multi-class brain tumor image classification
✔ Data preprocessing & label encoding
✔ Train/test split & model validation
✔ Model prediction on real test image
✔ Implementation using TensorFlow & OpenCV

🧪 How It Works

Load and preprocess the dataset

Shuffle and split into training & testing sets

Train the CNN model

Evaluate validation accuracy

Test prediction on unseen image

📈 Output

The model prints:

Training accuracy & loss

Validation performance

Predicted tumor class for a test image

🔧 Technologies Used

Python

TensorFlow / Keras

OpenCV

NumPy

Pandas

Matplotlib

📌 Future Enhancements

Use EfficientNet / Transfer Learning for higher accuracy

Apply data augmentation & normalization pipelines

Deploy using Flask / Streamlit

Convert to web or mobile-based diagnosis assistant
