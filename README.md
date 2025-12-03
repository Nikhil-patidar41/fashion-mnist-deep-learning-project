# fashion-mnist-deep-learning-project
This project builds and evaluates Artificial Neural Networks and Convolutional Neural Networks to classify Fashion MNIST clothing images into 10 categories:


T-shirt / Top

Trouser

Pullover

Dress

Coat

Sandal

Shirt

Sneaker

Bag

Ankle boot

📌 Project Objectives

✔ Build ANN and CNN models
✔ Train, validate, evaluate accuracy
✔ Use TensorBoard for monitoring
✔ Save and reload trained models
✔ Predict new unseen images

📂 Repository Structure
├── notebooks/
│     └── fashion_mnist_assignment.ipynb
├── models/
│     └── fashion_mnist_ann_final.h5
├── dataset/sample_images/
├── README.md
└── requirements.txt

🔧 Model Architecture
ANN Model:

Flatten Layer

Dense(128) + ReLU

Dense(128) + ReLU

Dense(10) + Softmax

CNN Model:

Conv2D + MaxPooling

Conv2D + MaxPooling

Flatten

Dense(128) + ReLU

Dropout(0.3)

Dense(10) + Softmax

📊 Model Performance

ANN Accuracy: ~89%

CNN Accuracy: ~93%

🔍 Key Features Demonstrated

✔ Data normalization & preprocessing
✔ Model building (ANN + CNN)
✔ Training with validation set
✔ TensorBoard visualization
✔ Saving & loading Keras models
✔ Confusion matrix evaluation
✔ Universal prediction function to classify new image

🧠 What I Learned

✔ Deep Learning model workflow
✔ ANN vs CNN comparison
✔ Importance of preprocessing
✔ Saving & serving models
✔ TensorBoard tracking

👤 Author

Nikhil Patidar — Data Science learner



