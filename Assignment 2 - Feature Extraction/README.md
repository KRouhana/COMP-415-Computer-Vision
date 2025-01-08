### **Learning Objectives**
- **Feature Detection & Matching:** Master fundamental techniques for detecting and matching distinctive points in images
- **Computer Vision Algorithms:** Implement and understand core computer vision algorithms including Harris Corner Detection and SIFT
- **Image Transformation Analysis:** Evaluate feature detection methods under various image transformations (scale, rotation)
- **Panoramic Image Creation:** Learn to combine multiple images through feature matching and image stitching

---
### **Computer Vision Concepts Covered**
- **Corner Detection:** Harris corner detector implementation and analysis
- **Scale Invariant Feature Transform (SIFT):**
  - Feature detection and description
  - Feature matching techniques
  - Scale and rotation invariance properties
- **Image Transformations:** 
  - Scaling and rotation effects on feature matching
  - Homography estimation
- **Image Stitching:**
  - Feature-based alignment
  - RANSAC for robust estimation
  - Image blending techniques (linear and multi-band)

---
### **Summary of the Problem and Deliverables**

#### **Part 1: Harris Corner Detection**
- Implement Harris corner detector from scratch using NumPy
- Test on multiple images including checkerboard and building
- Analyze threshold effects on corner detection
- Steps include:
  1. Image derivatives computation
  2. Square derivatives calculation
  3. Gaussian filtering
  4. Cornerness response calculation
  5. Non-maximum suppression

#### **Part 2: SIFT Features Analysis**
1. **SIFT Understanding:**
   - Describe the 4 main steps of SIFT
2. **Basic SIFT Matching:**
   - Match keypoints between two images
   - Analyze top matches
3. **Scale Invariance Testing:**
   - Test SIFT with various scaling factors (0.25, 0.6, 3, 5)
   - Analyze matching performance
4. **Rotation Invariance Testing:**
   - Test SIFT with various rotation angles (30°, 75°, 90°, 180°)
   - Analyze matching performance

#### **Part 3: Image Stitching**
- Create panorama from three different views
- Steps include:
  1. SIFT feature extraction and matching
  2. Homography estimation using RANSAC
  3. Image transformation
  4. Image blending implementation
  5. Analysis of different blending techniques

---