# Image-Classification-Using-CNNs
🧠 Image Classification Using CNNs
🎯 Objective
This project demonstrates the use of Convolutional Neural Networks (CNNs) to classify images from the CIFAR-10 dataset. The goal is to understand CNN architecture, training, evaluation, and improvements in model performance using standard deep learning techniques.

📁 Dataset
CIFAR-10 is a publicly available dataset consisting of 60,000 32×32 color images across 10 classes.

🧪 Tasks Overview
✅ Task 1: Data Exploration and Preparation (2 Marks)
Displayed 5 sample images with labels.

Printed dataset shape and label counts.

Normalized pixel values to [0, 1].

Split into 80% training and 20% test data.

✅ Task 2: Build and Train a CNN Model (5 Marks)
Built a CNN with the following structure:

Conv2D → ReLU → MaxPooling → Dropout (x2)
Flatten → Dense → Output (Softmax)
Trained for 15 epochs using Adam optimizer.

Plotted training vs. validation accuracy & loss.

Analyzed model performance and overfitting behavior.

✅ Task 3: Evaluate the Model (2 Marks)
Calculated test accuracy and generated:

Classification Report

Confusion Matrix

Visualizations of Correctly & Incorrectly Classified Samples

✅ Task 4: Model Improvements (1 Mark)
Tested other optimizers: SGD, RMSProp

Compared results in terms of:

Accuracy

Training stability

Convergence speed

📊 Results
Optimizer	Test Accuracy	Observations
Adam	78.2%	Best overall performance
SGD	72.5%	Slower convergence
RMSProp	76.3%	Good performance, less stable
🧰 Tech Stack / Skills Used
Languages: Python

Libraries: TensorFlow/Keras, NumPy, Matplotlib, Seaborn, Scikit-learn

Concepts: CNN, Image Classification, Dropout, Optimizer Tuning, Confusion Matrix, Classification Report
