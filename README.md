# Face Mask Detection using CNN (TensorFlow, Keras, OpenCV)
This project is a deep learning-based image classification model designed to detect whether a person in an image is wearing a face mask or not. It uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras, and includes preprocessing with OpenCV and other tools.

📌 Features

CNN-based binary image classifier.

Achieved 91% test accuracy and 0.19 test loss.

Preprocessed and labeled 7,500+ images (with/without masks).

Model evaluation using:

Confusion Matrix

ROC-AUC Curve

Log Loss

Custom image predictions supported (test with your own images).
![WhatsApp Image 2025-07-05 at 11 34 49_e4d7a588](https://github.com/user-attachments/assets/8b8e0d07-0788-40c7-a12d-512a602725d3)

![WhatsApp Image 2025-07-05 at 11 35 43_97276a09](https://github.com/user-attachments/assets/7ff01bf6-323c-4e97-9236-14bcd4b7b66e)

![WhatsApp Image 2025-07-05 at 11 35 58_e25ee215](https://github.com/user-attachments/assets/f1d002da-39e8-4ab8-83ba-422d69cabf9c)

![WhatsApp Image 2025-07-05 at 11 36 08_7544b2c8](https://github.com/user-attachments/assets/e440344d-8eb5-4636-b401-1d5d936fcd1b)

![WhatsApp Image 2025-07-05 at 11 36 20_20972b90](https://github.com/user-attachments/assets/0b912958-8f69-4141-8bcf-49014047d836)

📂 Dataset

Dataset used:

Face Mask Dataset - Kaggle



🛠️ Tech Stack

Python

TensorFlow & Keras

OpenCV

scikit-learn

Matplotlib & Seaborn

PIL (Python Imaging Library)




🚀 Model Architecture

Convolutional Layers + MaxPooling

Dense Fully Connected Layers with Dropout

Sigmoid Activation for Binary Classification

Optimizer: Adam

Loss: Sparse Categorical Crossentropy



📊 Results

Metric	Value

Test Accuracy	91%

Test Loss	0.19

Validation Accuracy	Up to 92%



🔎 How to Use

Clone the repository:

git clone https://github.com/Saumya-1802/Face-Mask-Detection.git


Install dependencies:

pip install tensorflow keras opencv-python matplotlib seaborn scikit-learn pillow


Download and extract the dataset into the project directory.


Run the training script (face_mask_detection.py or notebook).




🎯 Predicting on Custom Images

Place your test image in the project folder.

Use the provided prediction function



📄 License

This project is for academic and educational purposes.



🙋‍♀️ Author

Saumya Mishra
