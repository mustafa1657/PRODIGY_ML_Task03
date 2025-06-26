# PRODIGY_ML_TASK03 - Cat vs Dog Image Classification using SVM

## About the Project
This is Task 3 of my Machine Learning internship at Prodigy InfoTech. In this task, I built a model to classify images of **cats and dogs** using the **Support Vector Machine (SVM)** algorithm.

## Dataset Used
- Dataset Source: Kaggle (Dogs vs. Cats Dataset)
- I used the PetImages folder which contains two subfolders: Cat and Dog.
- Images were loaded from both folders, processed, and labeled (0 for cat, 1 for dog).

## What I Did
- Loaded and resized all images to 32x32 pixels to reduce computation time and memory usage.
- Converted the images to grayscale and flattened them to feed into the SVM model.
- Labeled the data: 0 for cats, 1 for dogs.
- Split the dataset using train_test_split.
- Trained a **Support Vector Classifier (SVC) from sklearn.svm.
- Evaluated the model using accuracy score and tested it with a few images.

## Libraries Used
- numpy
- opencv-python (cv2)
- scikit-learn
- os

## Challenges Faced
- Many corrupted or unreadable images in the dataset; I handled these using try-except blocks.
- Training took some time, so resizing to 32×32 helped improve speed without losing much accuracy.

## Results
- The model was able to successfully classify cat and dog images.
- Printed prediction results and confirmed through visual inspection.

## Conclusion
This task gave me hands-on experience in working with image data, applying preprocessing techniques, and using SVM for classification in machine learning.
