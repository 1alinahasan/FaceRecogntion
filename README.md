# Face Recognition Using PCA (Eigenfaces)

This project implements a basic **face recognition system** using **Principal Component Analysis (PCA)**, commonly known as the **Eigenfaces approach**. The goal is to reduce the dimensionality of facial image data while preserving the most significant variations that distinguish different faces.

## Objective
To build a facial recognition pipeline by projecting face images into a lower-dimensional feature space (face space) using PCA and performing recognition based on similarity in this reduced space.

## Dataset
- Face image dataset organized in folders (one folder per subject)
- Images are preprocessed and converted into numerical feature vectors
- Dataset contains multiple images per individual to support training and testing

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- SciPy

## Methodology
1. Load and preprocess face images  
2. Convert images into flattened feature vectors  
3. Standardize data using feature scaling  
4. Apply **PCA** to extract principal components (Eigenfaces)  
5. Project images into PCA feature space  
6. Perform face recognition using distance-based similarity  
7. Evaluate recognition performance  

## Key Concepts
- Principal Component Analysis (PCA)
- Eigenfaces
- Dimensionality Reduction
- Face Space Projection
- Feature Standardization
- Similarity-Based Classification

## Results
- PCA successfully reduces high-dimensional image data while retaining facial structure
- Eigenfaces capture dominant facial variations
- Recognition performance improves with optimal number of principal components

## How to Run
1. Clone the repository  
2. Update the dataset path in the notebook  
3. Install required dependencies  
4. Run all notebook cells sequentially  

## Future Improvements
- Add classification models (SVM, KNN)
- Tune number of PCA components
- Improve preprocessing (face alignment, normalization)
- Extend to real-time face recognition

## Author
**Alina Hasan**  
BS Computer Science, University of Missouri Kansas City
