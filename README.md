# Service Desk Ticket Classification Using CNN

This project implements a Convolutional Neural Network (CNN)–based text classification system to automatically categorize service desk tickets into predefined categories. The objective is to streamline customer service operations by reducing manual ticket handling and improving response efficiency.

## Project Workflow

### Load and Explore Data
- Loaded service desk ticket text from JSON files  
- Loaded word-to-index mappings and label data  

### Preprocessing
- Tokenized and padded text sequences  
- Converted ticket categories into numerical labels  

### Model Development
- Built a CNN architecture consisting of:
  - Embedding layer
  - 1D convolution layer
  - Fully connected (linear) layer  

### Model Training
- Trained the model using the Adam optimizer  
- Limited training to 3 epochs as specified  

### Evaluation
- Tested the model on unseen test data  
- Evaluated performance using:
  - Accuracy
  - Precision (per class)
  - Recall (per class)

## Result
The CNN-based classifier demonstrated effective performance in categorizing service desk tickets based on textual features, highlighting the potential of deep learning for automating customer support workflows.


