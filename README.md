# Pneumonia Detection Using Chest X-ray Images
# Overview
This project applies deep learning techniques to detect pneumonia from chest X-ray images. Using a Convolutional Neural Network (CNN) built with TensorFlow and Keras, the model classifies images into Normal and Pneumonia-infected cases.

- Dataset
The dataset used in this project is the Chest X-ray Pneumonia Dataset from Kaggle, which contains labeled X-ray images categorized as:

- NORMAL – Healthy lung scans
- PNEUMONIA – Lungs infected with pneumonia

## Project Workflow
- Dataset Acquisition & Preprocessing

- Download dataset from Kaggle
- Extract and explore the dataset
- Preprocess images (resizing, normalization, grayscale conversion)
- Data Augmentation & Generators

- Apply augmentation techniques using ImageDataGenerator
- Split dataset into training and validation sets
-  Model Architecture
![Few Sample dataset previewed](https://github.com/Niel07-cyber/PNEUMONIA-MACHINE-LEARNING-MODEL/blob/main/Screenshot%202025-02-13%20214414.png)

- A CNN model with multiple convolutional and pooling layers
- Uses ReLU activation, MaxPooling, and Dense layers
- Final sigmoid activation for binary classification
- Model Training & Evaluation
![Few Sample dataset previewed](https://github.com/Niel07-cyber/PNEUMONIA-MACHINE-LEARNING-MODEL/blob/main/Screenshot%202025-02-13%20224516.png)

Train the CNN model on the dataset
Evaluate performance using accuracy and loss curves
Predictions & Testing
![Few Sample dataset previewed](https://github.com/Niel07-cyber/PNEUMONIA-MACHINE-LEARNING-MODEL/blob/main/Screenshot%202025-02-13%20224537.png)

Test the model with real X-ray images
Display predictions with confidence scores

![Few Sample dataset previewed](https://github.com/Niel07-cyber/PNEUMONIA-MACHINE-LEARNING-MODEL/blob/main/Screenshot%202025-02-14%20000300.png)

## Technologies Used
- Python
- TensorFlow & Keras
- OpenCV & PIL (for image processing)
- Matplotlib & Seaborn (for visualization)
- Jupyter Notebook
  
### Results & Insights
- The model successfully classifies chest X-rays into Normal and Pneumonia with high accuracy.
- The training phase demonstrates convergence, and the validation accuracy is stable.
- The model can generalize well when tested on unseen X-ray images.


#How to Run
- Clone the repository:
✅git clone https://github.com/your-username/pneumonia-detection.git

- Install dependencies:
✅pip install -r requirements.txt

- Run the Jupyter Notebook:
✅jupyter notebook
