### **Learning Objectives**
- **Deep Learning for Computer Vision:** Understand and implement CNNs for image classification
- **Network Architecture Design:** Learn the impact of different architectural choices on model performance
- **Transfer Learning:** Understand the benefits of using pre-trained models and fine-tuning
- **Object Detection:** Gain practical experience with state-of-the-art object detection models
- **Model Evaluation:** Develop skills in training, validating, and testing deep learning models

---
### **Computer Vision Concepts Covered**
- **Convolutional Neural Networks:**
  - Convolution layers and kernel sizes
  - Activation functions (ReLU)
  - Pooling operations
  - Fully connected layers
- **Deep Learning Techniques:**
  - Data splitting strategies
  - Batch processing
  - Learning rate optimization
  - Loss functions
  - Transfer learning
- **Modern Architectures:**
  - Shallow CNN design
  - ResNet18 architecture
  - YOLOv8 for object detection
- **Performance Analysis:**
  - Training vs validation loss
  - Overfitting detection
  - Model comparison metrics

---
### **Summary of the Problem and Deliverables**

#### **Part 1: CIFAR-10 Classification**
1. **Shallow CNN Implementation:**
   - Build specified architecture with multiple conv layers
   - Train on CIFAR-10 dataset
   - Monitor GPU usage

2. **Training and Evaluation:**
   - Split data (50k training, 5k validation, 5k test)
   - Implement training loop with specified parameters
   - Plot training metrics and analyze overfitting
   - Report test accuracy

3. **Architecture Analysis:**
   - Experiment with different kernel sizes (3x3 vs 5x5)
   - Compare performance and runtime
   - Analyze impact factors

4. **ResNet18 Implementation:**
   - Train both from scratch and pre-trained
   - Compare performance with shallow CNN
   - Analyze impact of transfer learning

#### **Part 2: Real-World Object Detection**
1. **Data Collection:**
   - Capture Montreal street scene

2. **YOLOv8 Implementation:**
   - Deploy pre-trained model
   - Perform object detection
   - Count and classify detected objects

3. **Visualization:**
   - Display original and annotated images
   - Present detection results

---