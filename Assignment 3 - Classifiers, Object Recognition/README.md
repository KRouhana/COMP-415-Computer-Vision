### **Learning Objectives**
- **Image Classification:** Master fundamental machine learning techniques for image classification using SVM and Random Forest
- **Feature Extraction:** Learn to compute and utilize HoG features for classification
- **Face Detection:** Understand and implement multiple approaches to face detection including PCA and Viola-Jones
- **Model Evaluation:** Develop skills in hyperparameter tuning, model comparison, and performance evaluation

---
### **Computer Vision Concepts Covered**
- **Feature Engineering:**
  - Histogram of Oriented Gradients (HoG)
  - Principal Component Analysis (PCA)
- **Machine Learning Models:**
  - Support Vector Machines (SVM)
  - Random Forest Classification
  - Hyperparameter optimization
- **Face Detection Techniques:**
  - Eigenfaces using PCA
  - Viola-Jones detector
  - Sliding window approach
- **Performance Metrics:**
  - Classification accuracy
  - True/False Positives/Negatives
  - Model stability analysis

---
### **Summary of the Problem and Deliverables**

#### **Part 1: CIFAR10 Classification**
1. **Data Preprocessing:**
   - Resize images to 64x64 and convert to grayscale
   - Compute HoG features (8x8 pixels, 4x4 cells, 4 bins)

2. **SVM Classification:**
   - Implement non-linear SVM classifier
   - Tune 'gamma' and 'C' hyperparameters
   - Evaluate classification accuracy

3. **Random Forest Classification:**
   - Implement RF classifier with specified parameters
   - Compare performance with SVM
   - Analyze model stability across different random states

#### **Part 2: Face Detection**
1. **Dataset Preparation:**
   - Process CelebA dataset subset
   - Convert images to grayscale

2. **PCA Implementation:**
   - Implement Snapshot method for PCA
   - Display first five eigenfaces

3. **Face Detection Pipeline:**
   - Implement sliding window detection
   - Set and tune detection threshold
   - Label detected faces with bounding boxes

4. **Comparison and Analysis:**
   - Compare custom implementation with Viola-Jones detector
   - Evaluate detection performance
   - Analyze conditions where each method performs better
   - Document model performance and implementation steps

---