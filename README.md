# 🩸 **Decoding Cellular Complexity: A Deep Learning Approach to Blood Cell Image Classification**

## 🔍 **Project Overview**
Welcome to the *Decoding Cellular Complexity* project! This research focuses on leveraging advanced deep learning techniques to classify blood cell images, aiming to enhance diagnostic accuracy in medical imaging. The project utilizes a hybrid model combining **InceptionV3** and **Xception**, achieving a remarkable **98.51% test accuracy**, setting a new standard for medical diagnostics.

## 🌟 **Key Features**
### 📂 **Dataset**
- 17,092 high-resolution blood cell images, sourced from the **Hospital Clinic of Barcelona**.
- Expert clinical pathologists ensured accurate image annotations for high-quality data.
  
### 🧠 **Deep Learning Models**
- **CNNs (Convolutional Neural Networks)**, **U-Net**, **ResNet-50**, **VGG-16**, **DenseNet-201**, **MobileNet-V2**.
- **Supervised Contrastive Learning** for enhanced feature extraction.
- **Hybrid Model** combining **InceptionV3** and **Xception** architectures.

### 📈 **Performance Highlights**
- **Hybrid Model (InceptionV3 + Xception):** Achieved an impressive **98.51%** test accuracy.
- **Xception Model:** Delivered a **97.89%** test accuracy.
- **Supervised Contrastive Learning:** Reached **96.35%** accuracy.
- Comprehensive evaluations were performed, including **data shuffling** and **cross-validation**.

### 🩺 **Applications**
- **Automated Blood Cell Classification**: Enhancing diagnostic systems for more accurate results.
- **Disease Detection**: Early identification of conditions like **leukemia**, **autoimmune disorders**, and other **hematologic diseases**.

## 🛠️ **Methodology**

### 🔄 **Data Preprocessing**
- Resized images to a standard **224x224 pixels** for model consistency.
- Split data into **70% training** and **30% testing**, ensuring **class-stratified** sampling.
- Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to handle class imbalance.

### 🚀 **Model Training**
- Utilized **transfer learning** with pre-trained architectures and fine-tuned classification layers.
- **Optimization strategies** included **Adam**, **RMSprop**, and **SGD** optimizers for enhanced convergence.

### 📊 **Evaluation Metrics**
- Accuracy, **Precision**, **Recall**, **F1-score**, and **Confusion Matrix** were used to evaluate model performance.
- Conducted a **comparative analysis** between models, considering factors like **data shuffling** and **validation**.

## 📊 **Results**
### **Test Accuracy** of Top Models:

| Model                        | Train Accuracy | Test Accuracy |
|------------------------------|----------------|---------------|
| **Hybrid (InceptionV3 + Xception)** | **99.75%**        | **98.51%**     |
| **Xception**                  | **99.34%**        | **97.89%**     |
| **Supervised Contrastive Learning** | **98.39%**        | **96.35%**     |

## 🧪 **Conclusion**
This project demonstrates the power of hybrid deep learning models in transforming **blood cell image classification**. By achieving high accuracy and reliability, these models provide valuable insights into improving medical diagnostics and reducing human error in healthcare.

## 🚀 **Future Work**
- **Explore** additional deep learning architectures for further improvements.
- **Expand** the study with more diverse datasets from various medical institutions.
- **Integrate** this framework with real-time diagnostic tools for clinical deployment.

## 🤝 **Contributors & Acknowledgments**
This project was a collaborative effort of:

- **Likhitha Marrapu**
- **Shivani Battu**
- **Chandini Karrothu**
- **Anuranjani Thota**
- **Hanan Muhajab**
- **Areej Muhajab**
- **Kambiz Ghazinour**
- **Stacy Miner**
- **Betis Baheri**
- **Safa Shubbar**

A special thanks to the **Hospital Clinic of Barcelona** for providing the dataset and expert annotations.

Deep learning technologies in medical imaging not only improve diagnostic precision but also accelerate the process, enabling **timely interventions** that can save lives and redefine how healthcare leverages imaging.

---

For detailed implementation and the full code, please refer to the repository.
