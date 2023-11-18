# Accident-Detection-System

# **Accident Detection System with Deep Learning**

### **Introduction**
In recent years, there has been a global increase in distracted driving-related traffic incidents, leading to a rise in injuries, property damage, and fatalities. The urgency to address this issue has prompted the development of innovative solutions to track and examine driver behavior, aiming to reduce accident rates. Our project aligns with the Vision Zero initiative, striving to eliminate all traffic-related fatalities and serious injuries.

![WhatsApp Image 2023-11-19 at 2 18 11 AM](https://github.com/ashish6523/Accident-Detection-System/assets/108401537/2cc0bce9-ee01-4707-b5fb-9448f79aba90)


### Project Objective : 
The primary goal of this project is to develop an advanced Accident Detection System capable of recognizing accidents in real-time through live video feeds from CCTV cameras mounted on roads. To achieve this, each frame of the video undergoes analysis through a Convolution Neural Network (CNN) model specifically trained to distinguish between accident and non-accident related video frames.

###  Methodology

### Proposed Solution 1: CNN-Based Accident Detection 
We have implemented a CNN-based approach as our primary solution for detecting distracted drivers. This method leverages deep learning techniques to analyze various postures and circumstances of a distracted driver. The CNN model is trained on a dataset that encompasses diverse scenarios, and the results are thoroughly analyzed to validate its efficiency.

![WhatsApp Image 2023-11-19 at 2 18 11 AM (1)](https://github.com/ashish6523/Accident-Detection-System/assets/108401537/a3159f31-e187-4c49-b218-ac18a0edc36f)

![WhatsApp Image 2023-11-19 at 2 18 11 AM (2)](https://github.com/ashish6523/Accident-Detection-System/assets/108401537/9940d573-216d-4dec-8170-38643d142fee)

### **Proposed Solution 2: MobileNetV2 Architecture with Transfer Learning**
To enhance the efficiency of our accident detection system, we incorporated MobileNetV2 architecture as our second proposed solution. This architecture is employed for transfer learning, leveraging pre-trained weights to improve the model's ability to distinguish accident-related frames. The utilization of MobileNetV2 aids in achieving a balance between accuracy and computational efficiency.

![WhatsApp Image 2023-11-19 at 2 18 10 AM](https://github.com/ashish6523/Accident-Detection-System/assets/108401537/1f65db35-94ba-43e4-a94e-2a96ccbb7aa6)

![WhatsApp Image 2023-11-19 at 2 18 11 AM (3)](https://github.com/ashish6523/Accident-Detection-System/assets/108401537/16c5103c-09fa-4c03-bedc-afc0261fa31a)


### **Proposed Solution 3:  Transfer Learning with SpinalNet Fully Connected Layer**
For further refinement, we implemented transfer learning with a SpinalNet fully connected layer. This addition enhances the model's capacity to capture intricate features crucial for accident detection. The SpinalNet layer contributes to the overall robustness of the system and improves its performance in identifying complex accident scenarios.

![WhatsApp Image 2023-11-19 at 2 18 11 AM (4)](https://github.com/ashish6523/Accident-Detection-System/assets/108401537/844884d4-5399-417d-bf7a-156d95a38c25)

![WhatsApp Image 2023-11-19 at 2 18 10 AM (1)](https://github.com/ashish6523/Accident-Detection-System/assets/108401537/ad1ea7a2-d787-4ef1-b3f9-19b2c9840e6d)

![WhatsApp Image 2023-11-19 at 2 18 11 AM (5)](https://github.com/ashish6523/Accident-Detection-System/assets/108401537/e65acd4c-d6bb-48bf-9dd2-baf539e7b904)

## **Data Preprocessing**
Our dataset undergoes comprehensive preprocessing, including data augmentation and normalization. These steps are essential to ensure the model's generalization across various scenarios and postures of distracted drivers. Data augmentation helps increase the diversity of the training set, while normalization ensures consistent and standardized input for the neural network.

## **Comparative Analysis**

#### 1. CNN-Based Model (74.9 percent Accuracy): 
**Strengths:**
Hierarchical Feature Capture: Traditional CNNs excel in capturing hierarchical features from images through convolutional layers, making them well-suited for image recognition tasks.
Pattern Recognition: Their ability to learn intricate patterns makes them effective for handling complex scenarios.
Weaknesses:
Computational Efficiency: CNNs may face challenges in computational efficiency, especially on resource-constrained devices.
Limited Optimization: The model's performance optimization for diverse datasets might be constrained.

#### **2. MobileNetV2-Based Model (89.80 percent accuracy):**
**Strengths:**
Computational Efficiency: MobileNetV2 is specifically designed for mobile and edge devices, focusing on lightweight operations to improve computational efficiency.
Depthwise Separable Convolutions: Efficient depthwise separable convolutions contribute to faster inference times on devices with limited resources.
Weaknesses:
Accuracy Trade-off: MobileNetV2 might sacrifice some accuracy compared to more complex models designed for high-performance environments.
Handling Complex Features: It may be limited in effectively handling highly complex or intricate features in certain datasets.

#### **3. SpinalNetV2-Based Model (95.9184 percent accuracy):**
**Strengths:**
Hierarchical Feature Processing: SpinalNetV2 introduces spinal layers that capture and process features hierarchically, enhancing the model’s ability to learn intricate patterns.
Multiple Spinal Layers: The incorporation of multiple spinal layers allows the model to understand complex relationships in data, contributing to improved accuracy.


## Conclusion 
In conclusion, our Accident Detection System combines state-of-the-art deep learning techniques, including CNNs, transfer learning with MobileNetV2, and the integration of a SpinalNet fully connected layer. The system aims to contribute to the Vision Zero initiative by swiftly identifying accidents and minimizing reaction time, thereby reducing the overall number of traffic-related fatalities and serious injuries.
