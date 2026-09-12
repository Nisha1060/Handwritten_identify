# Handwritten Digit Recognition
A simple **Machine Learning project** that recognizes handwritten digits using the **MNIST dataset** and the **K-Nearest Neighbors (KNN)** algorithm.

## About the Project
In this project, I used the **MNIST handwritten digit dataset** to train a KNN classifier that can recognize digits from **0 to 9**.
I also experimented with basic image processing using **OpenCV**

##  Technologies Used
* 🐍 Python
* 🤖 TensorFlow / Keras
* 📊 Scikit-Learn
* 🔢 NumPy
* 📈 Matplotlib
* 🐼 Pandas
* 👁️ OpenCV
* 🖼️ PIL
* 
## Dataset
The project uses the **MNIST dataset**, which contains:
* **60,000** training images
* **10,000** testing images
* Image size: **28 × 28 pixels**
* Digits: **0–9**

## How It Works
```text
MNIST Dataset
      ↓
Load Images
      ↓
Visualize Data
      ↓
Flatten Images
      ↓
Train KNN Model
      ↓
Test Model
      ↓
Predict Digit
Each `28 × 28` image is converted into **784 pixels** before being passed to the KNN model.

## Model
The project uses the **K-Nearest Neighbors (KNN)** classifier with:
```python
KNeighborsClassifier(n_neighbors=3)
```
## Image Processing
The project also includes experiments with custom images and image transformations such as:

* Grayscale conversion
* Image rotation
* Image inversion
* Image visualization
OpenCV is used for some of these image-processing operations.

## Getting Started
Install the required libraries:
```bash
pip install tensorflow scikit-learn numpy matplotlib pandas opencv-python pillow
```
Then open the Jupyter Notebook:
```text
Handwritten.ipynb
```
Run the cells step by step to train the model and make predictions.
## 📁 Project Structure
Handwritten.py
 mod.jpeg
 README.md
## Project Goal
The main goal of this project is to understand the basic workflow of **Machine Learning and Image Classification** using handwritten digits.

## Future Improvements
* Improve preprocessing of custom images
* Try different values of `k`
* Compare KNN with other algorithms
* Build a Neural Network
* Build a CNN for better image recognition
* Create a simple web interface for digit prediction

## Conclusion
This project is a simple introduction to **handwritten digit recognition using Machine Learning**.
It helped me understand how image data can be processed, visualized, and used to train a classification model.



