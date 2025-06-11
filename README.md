# CNN-Based Classification of Neutrophils in Microscopy Images
This project implements a Convolutional Neural Network (CNN) to differentiate between healthy neutrophil cells and those forming Neutrophil Extracellular Traps (NETs) in microscopy images. The goal is to support biomedical research by introducing a scalable, automated solution for accurate neutrophil classification and NET quantification.


Objectives:

•	Develop, train, and evaluate a CNN model for classifying neutrophil cells in microscopy images.
•	Investigate effective architectures (e.g., ResNet34) and identify optimal hyperparameters that significantly impact performance.
•	Evaluate the challenges and limitations of using a CNN-based approach to distinguish visually similar cell states.


Project Highlights:

•	Model Architecture: The ResNet34-based CNN achieved the best performance, with 72% accuracy, compared to other ResNet architectures in classifying microscopy images.
•	Preprocessing Techniques: Applied CLAHE to enhance image contrast and used data augmentation to address class imbalance and improve model generalization.
•	Robust Evaluation: Performed multiple training runs using different random seeds to validate consistency and reliability.
•	Comprehensive Metrics: Evaluated using precision, recall, F1-score, and prediction confidence, ensuring a balanced and realistic performance assessment.


Biomedical Applications:

•	Microscopy Image Analysis: Enables high-throughput classification of neutrophil states, reducing reliance on manual review.
•	Immunology Research: Assists in quantifying NET formation to study immune response mechanisms.
•	Clinical Diagnostics: Supports decision-making by automating cell classification related to inflammatory and immune conditions.


Conclusion:

This study demonstrates the effectiveness of CNNs—specifically ResNet34—in differentiating between healthy neutrophils and those forming NETs in microscopy images. Through effective preprocessing and comprehensive evaluation, the model offers a promising tool for biomedical imaging, contributing to immunological research and clinical diagnostics.
