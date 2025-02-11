# Using CNN identifying fake Indian notes
 Identifies if given Indian note is fake or not

## Overview
Counterfeit currency is a growing problem that affects the economy and financial security. This project aims to develop a **deep learning-based detection system** using **Convolutional Neural Networks (CNNs)** to differentiate between **genuine and fake Indian currency notes**. The model is trained on images of ₹2000 and ₹500 notes to identify counterfeit currency efficiently.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)
- [License](#license)

## Features
✔ Uses CNNs for counterfeit detection with high accuracy.  
✔ Trained on images of **₹2000 and ₹500 notes**.  
✔ Image preprocessing techniques for enhanced detection.  
✔ Efficient real-time classification for practical implementation.  
✔ Overcomes limitations of traditional hardware-based detection methods.  

## Dataset
The dataset consists of **genuine and counterfeit Indian currency images**. Preprocessing steps include resizing, augmentation, and feature extraction to improve model learning.

## Technologies Used
- **Programming Language**: Python
- **Frameworks & Libraries**:
  - TensorFlow/Keras (for CNN model training)
  - OpenCV (for image preprocessing)
  - NumPy, Pandas (for data handling)
  - Matplotlib, Seaborn (for data visualization)
- **Jupyter Notebook / Spyder IDE**

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/hrithiksai18/Using-CNN-identifying-fake-Indian-notes.git
   cd Using-CNN-identifying-fake-Indian-notes
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script to train and test the model.

## Usage
1. Load the dataset and preprocess images.
2. Train the CNN model using labeled currency data.
3. Evaluate model performance on test images.
4. Use the trained model for real-time currency verification.

## Results
The CNN model achieves **high accuracy** in detecting counterfeit notes. Performance metrics include:
- Accuracy: **~97%**
- Precision, Recall, and F1-Score for detailed analysis.

## Future Enhancements
🔹 Integrate with **mobile applications** for real-world usability.  
🔹 Expand dataset to include **more denominations** for better generalization.  
🔹 Implement **transfer learning** for improved performance.  

## Contributors
- **Hrithik Sai Grandhisiri** ([GitHub](https://github.com/hrithiksai18))
- **Team Members**

## License
This project is open-source and available under the **MIT License**.
