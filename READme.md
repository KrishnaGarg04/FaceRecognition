# **Face Recognition Using PCA & Eigenfaces**

## **Overview**

This project implements **Face Recognition** using **Principal Component Analysis (PCA)** and **Eigenfaces**. PCA reduces dimensionality while preserving key facial features, enabling efficient recognition and reconstruction.

## **Workflow**

1. **Data Preprocessing**: Load, grayscale, and flatten images.
2. **Train-Test Split**: Organize data into training & testing sets.
3. **PCA Application**: Compute **eigenfaces** from the covariance matrix.
4. **Feature Extraction**: Project images onto **top principal components**.
5. **Face Reconstruction**: Recreate images using eigenfaces.

## **Key Features**

✅ **Dimensionality Reduction** for efficient processing.\
✅ **Eigenfaces-based Classification** using Euclidean distance.\
✅ **Image Reconstruction** from principal components.

## **Setup & Execution**

### **Dependencies**

Install required libraries:

```bash
pip install numpy pandas matplotlib pillow scikit-learn  
```

### **Run the Code**

```python
python face_recognition.py  
```

## **Results & Future Work**

- PCA extracts essential face features with minimal data loss.
- Future improvements: **Deep Learning (CNNs), LDA for better classification.**

