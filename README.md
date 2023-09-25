                                                                      Oriented Object Detection Challenge Summary Report

Candidate Name: Pallavi Jadhav
                pallavi.jadhav27@gmail.com

Date: 25th September 2023

1. Introduction
This report provides a summary of the work completed for the Oriented Object Detection Challenge. The challenge aimed to develop a model capable of detecting and classifying oriented objects within images.

2. Data Preprocessing
2.1 Resizing Images
•	Resized all images to a uniform size of 512x512 pixels to create consistent input data.
•	Created a new directory to store resized images.
2.2 Converting to RGB Color Space
•	Converted images to the RGB color space to ensure uniformity in color representation.
•	Saved the RGB images to a separate directory.
2.3 Combining XML Annotations into CSV
•	Combined XML annotations for oriented objects into a single CSV file.
•	Extracted information such as bounding box coordinates and orientation direction.

3. Data Analysis and Preparation
•	Removed unnecessary columns from the dataset.
•	Detected and handled outliers in the data.
•	Applied label encoding to convert the target column (orientation_direction) into numerical values.
•	Observed class imbalance in the target column and addressed it using oversampling with RandomOverSampler.

4. Model Development
4.1 Initial Model
•	Developed an initial classification model with a neural network.
•	Achieved low accuracy.
4.2 Hyperparameter Tuning
•	Explored hyperparameters, including activation function, regularization strength, and learning rate.
•	Achieved an improved accuracy of 66% on the test dataset.

5. Model Evaluation
•	Evaluated the model on the test dataset.
•	Calculated the confusion matrix to assess classification performance.
•	Observed some misclassifications, indicating room for improvement.

6. Conclusion
In conclusion, this project involved the development of a model for oriented object detection. Despite initial challenges and low accuracy, through hyperparameter tuning, we achieved a substantially improved accuracy of 66% on the test dataset. There is still potential for further enhancements, especially in handling misclassifications and addressing class imbalance.

7. Future Improvements
•	Explore more advanced architectures and techniques, such as object detection frameworks (YOLO, SSD) and pre-trained models.
•	Experiment with different data augmentation strategies to improve model robustness.
•	Investigate the use of focal loss to further address class imbalance.
•	Continue fine-tuning hyperparameters for better performance.
