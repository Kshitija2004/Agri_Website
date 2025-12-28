# Agri_Website
Designed an AI-based multilingual agriculture website for framers.

Problem:
Soybean crops are highly affected by leaf diseases, and manual identification by farmers is time-consuming, error-prone, and requires expert knowledge. Late detection leads to reduced crop yield and financial loss.

Solution:
Developed an AI-based leaf disease detection system that automatically identifies soybean leaf diseases from images using deep learning techniques, enabling early and accurate diagnosis.


How It Works / What I Did:

* Collected and used a soybean leaf image dataset containing healthy and diseased leaf samples.

Performed image preprocessing such as resizing, normalization, and data augmentation to improve model accuracy.

Trained a Convolutional Neural Network (CNN) (using models like ResNet / EfficientNet) to extract visual features from leaf images.

Classified images into healthy or disease categories using a Softmax classifier.

Evaluated model performance using accuracy and validation metrics.


Impact / Outcome:

Enables early disease detection, reducing crop loss.

Assists farmers in taking timely preventive measures.

Demonstrates practical application of computer vision and deep learning in agriculture.


Technologies Used:
Python, CNN, TensorFlow / Keras, OpenCV, NumPy, Deep Learning, Image Processing
