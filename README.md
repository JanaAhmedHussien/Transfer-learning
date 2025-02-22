# Facial Expression Recognition Using Pre-trained Models  

## Objective  
The objective of this assignment is to utilize **pre-trained deep learning models** to classify facial expressions into six categories:  
- Angry  
- Fear  
- Happy  
- Neutral  
- Sad  
- Surprise  

The goal is to preprocess the dataset, fine-tune pre-trained models, and evaluate their performance in recognizing facial expressions.  

---

## Instructions  

### 1. Data Preprocessing  
- Load and preprocess the facial expression dataset.  
- Resize all images to a uniform size (e.g., 48x48 or 64x64 pixels).  
- Normalize pixel values to a range of [0, 1].  
- Split the dataset into training, validation, and test sets.  

### 2. Model Architecture  
- Import at least **two pre-trained models**, such as **ResNet**, **VGG16**, or **AlexNet**.  
- Modify the pre-trained models by adding necessary layers for classification.  
- Apply **transfer learning** to leverage pre-trained weights for feature extraction.  

### 3. Model Training  
- Train each model on the facial expression dataset using an appropriate loss function, such as categorical cross-entropy.  
- Use an optimizer like **SGD** or **Adam** for gradient descent.  
- Track and plot training and validation loss and accuracy over epochs.  
- Implement **early stopping** to avoid overfitting.  

### 4. Evaluation  
- Evaluate the performance of both models on the test dataset.  
- Compare the results and draw conclusions regarding their accuracy, training time, and generalization.  


