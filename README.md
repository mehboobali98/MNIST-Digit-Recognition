# MNIST-Digit-Recognition

The popular MNIST dataset is used for the digit recognition task using different machine learning algorithms such as KNN and SVM with HOG features. A simple feed forward neural network is also used for comparision with the machine learning models. A detailed report in IEEE format is also provided in the documents folder.

# Results

| Model             | Accuracy |
| ----------------- | -------- |
| KNN (k=3)         | 99.97    |
| SVM (poly kernel) | 98.38    |
| FFNN              | 97.98    |

# Directory Structure

<pre>
📦MNIST-Digit-Recognition
┣ 📂Documents
┃ ┗ 📜Detailed Report.pdf
┣ 📂Notebooks
┃ ┣ 📜MNIST using FFNN.ipynb
┃ ┣ 📜MNIST Using KNN.ipynb
┃ ┗ 📜MNIST Using SVM and HOG.ipynb
┣ 📂Trained models
┃ ┣ 📜linearSVM.pkl
┃ ┣ 📜nonlinear-Poly.pkl
┃ ┗ 📜nonlinear-Rbf.pkl
┗ 📜README.md
 </pre>

# Future Work

- Use Convolutional Neural Networks (CNN) for the classification task.
- Read digits from images using OpenCV.
