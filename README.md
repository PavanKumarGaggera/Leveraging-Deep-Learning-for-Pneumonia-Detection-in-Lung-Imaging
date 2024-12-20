# Leveraging Deep Learning for Pneumonia Detection in Lung Imaging

### Abstract
This project leverages advanced deep learning models to address the critical challenge of diagnosing pneumonia from chest X-ray images. Using Convolutional Neural Networks (CNNs), particularly VGG16 and VGG19 architectures, the model is trained on a comprehensive dataset of 5,856 annotated pediatric chest X-ray images provided by Voxel51. This project underscores the transformative role of AI in healthcare, offering rapid and accurate diagnostic solutions, particularly for vulnerable populations such as international students.

### Key Features
Deep Learning Models: VGG16 and VGG19 architectures for classification.
Dataset Utilization: High-quality annotated chest X-rays categorized as normal, bacterial, and viral pneumonia.
Visualization Tools: Matplotlib, Seaborn, and FiftyOne for dataset analysis and quality assurance.
Performance Metrics: Accuracy, precision, recall, and F1-scores evaluated for robust model performance.
Problem Addressed: Cost-effective and accessible diagnostics for pneumonia, especially for underserved groups.

### Dataset
The dataset, hosted on Kaggle, consists of:
5,856 Chest X-ray Images: Annotated for normal, bacterial, and viral pneumonia cases.
Demographic: Pediatric patients aged 1-5 years.
Labels: Disease type, randomized patient ID, and image number for systematic processing.

### Visualization
Traditional Methods:
Matplotlib: Image quality inspection.
Seaborn: Class distribution analysis through bar plots and pie charts.

### Advanced Visualization:
Voxel FiftyOne: Interactive dataset management, annotation browsing, and real-time inspection for improved data quality.

### Results
The VGG19 model achieved the following:
Training Accuracy: 96.68%
Validation Accuracy: 86.54%
Final Testing Accuracy: 94%
Performance Metrics:
Precision: 0.93 (Normal), 0.94 (Pneumonia)
Recall: 0.91 (Normal), 0.96 (Pneumonia)
F1-Scores: 0.92 (Normal), 0.95 (Pneumonia)
Note: Observed overfitting suggests the need for enhanced regularization techniques or data augmentation.

### Technologies Used
Programming Language: Python
Libraries:
TensorFlow
Matplotlib
Seaborn
Voxel FiftyOne
Model Architectures:
VGG16
VGG19

### Conclusion
This project demonstrates the capability of deep learning to revolutionize medical diagnostics, particularly for pneumonia detection in pediatric patients. Despite challenges like overfitting, it establishes a strong foundation for developing accessible diagnostic solutions leveraging artificial intelligence.
