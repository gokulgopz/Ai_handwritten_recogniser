# AI_Handwritten_Recogniser

---

## ✍️ A Neural Network That Learns to Read Your Handwriting!

This repository hosts a beginner-friendly deep learning project built in Google Colab that trains a simple **Artificial Neural Network (ANN)** to accurately recognize handwritten digits (0-9). Utilizing the famous **MNIST dataset** and powered by **TensorFlow/Keras**, this project serves as an ideal "Hello World" for anyone diving into the exciting world of Artificial Intelligence and Machine Learning.

---

## 🎯 Project Goal

The primary objective of this project is to demonstrate the fundamental steps involved in building, training, and evaluating a neural network for a common classification task. We aim to achieve high accuracy in identifying handwritten digits, showcasing how AI can "see" and interpret visual data.

---

## ✨ Key Features

* **MNIST Dataset Integration:** Seamless loading and preprocessing of the industry-standard handwritten digits dataset.
* **Simple Neural Network Architecture:** A straightforward `Sequential` model with `Dense` layers, perfect for understanding core ANN concepts.
* **Training & Evaluation:** Robust training process with 'Adam' optimizer and 'sparse_categorical_crossentropy' loss, followed by comprehensive evaluation on unseen test data.
* **Visual Predictions:** Ability to visualize actual test images alongside the model's predictions, highlighting correct and incorrect classifications.
* **Google Colab Ready:** Designed to run entirely within Google Colab, leveraging free GPU/TPU access for faster training without any local setup.

---

## 🛠️ Technologies Used

* **Python 3.x**
* **TensorFlow / Keras:** For building and training the neural network.
* **NumPy:** For numerical operations and data handling.
* **Matplotlib:** For data visualization and plotting results.
* **Google Colab:** The cloud-based environment for development and execution.

---

## 🚀 How to Run This Project

1.  **Open in Google Colab:** Click on the `MNIST_Digit_Recognizer.ipynb` notebook file in this repository. It will open directly in Google Colab.
    * *Self-correction: The notebook name is `MNIST_Digit_Recognizer.ipynb` based on our previous discussion.*
2.  **Run All Cells:** Once opened, go to `Runtime` -> `Run all` in the Colab menu. The notebook will download the dataset, preprocess it, build and train the model, and then evaluate it.
3.  **Explore Outputs:** Observe the training progress, accuracy metrics, and the visual predictions of handwritten digits.

---

## 📸 Project Screenshots

Here are some visual insights into the project's execution and results:

### 1. Data Loading and Initial Glimpse
*Include screenshot here showing the output of `X_train.shape`, `y_train.shape` and the first few displayed MNIST digits.*
![Screenshot of Data Loading and Initial Glimpse](Ai_handwritten_recogniser
/first results.jpg)

### 2. Model Training Progress
*Include screenshot here showing the output of the model training (the epoch logs with loss and accuracy).*
![Screenshot of Model Training Progress](link-to-your-screenshot-2.png)

### 3. Model Evaluation and Final Accuracy
*Include screenshot here showing the output of `model.evaluate` with Test Loss and Test Accuracy.*
![Screenshot of Model Evaluation and Final Accuracy](link-to-your-screenshot-3.png)

### 4. Visual Predictions
*Include screenshot here showing the plot of predicted vs actual digits (green/red titles).*
![Screenshot of Visual Predictions](link-to-your-screenshot-4.png)

---

## 📈 Results

After training for 10 epochs, the model typically achieves an accuracy of **~97-98%** on the unseen test dataset, demonstrating its impressive ability to classify handwritten digits accurately.

---

## 🤝 Contribution

Feel free to fork this repository, experiment with different network architectures, add new features, or suggest improvements!

---

## 📜 License

This project is open-sourced under the MIT License.

---
