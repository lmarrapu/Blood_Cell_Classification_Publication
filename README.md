# Decoding Cellular Complexity: A Deep Learning Expedition in Blood Cell Image Classification

## Project Overview
This project presents an advanced framework for blood cell image classification, leveraging cutting-edge deep learning techniques. By using a meticulously curated dataset, we achieved exceptional accuracy, advancing the field of medical diagnostics. The hybrid InceptionV3-Xception model excelled, attaining a test accuracy of 98.51%.

## Key Features
- **Dataset**: High-resolution images sourced from the Hospital Clinic of Barcelona, annotated by clinical pathologists.
- **Deep Learning Models**: 
  - Convolutional Neural Networks (CNNs), U-Net, ResNet-50, VGG-16, DenseNet-201, MobileNet-V2.
  - Supervised Contrastive Learning.
  - InceptionV3 and Xception.
  - Hybrid Model combining InceptionV3 and Xception.
- **Performance Highlights**:
  - Hybrid model achieved the highest accuracy of 98.51%.
  - Models assessed for robustness using data shuffling and cross-validation.
- **Applications**:
  - Automated blood cell classification for improved diagnostics.
  - Early detection of diseases like leukemia and autoimmune disorders.

## Methodology
1. **Data Preprocessing**: Standardized image dimensions, class-stratified splits, and SMOTE for class imbalance handling.
2. **Model Training**:
   - Utilized transfer learning and customized layers for feature extraction and classification.
   - Optimized models using Adam, RMSprop, and SGD optimizers.
3. **Evaluation**:
   - Metrics include accuracy, precision, recall, F1-score, and confusion matrices.
   - Comparative analysis conducted across architectures with and without data shuffling.

## Results
The following table highlights the top three models based on their highest test accuracy:

| Model                         | Train Accuracy | Test Accuracy | Precision | Recall | F1 Score |
|-------------------------------|----------------|---------------|-----------|--------|----------|
| Hybrid (InceptionV3 + Xception) | 99.75%        | 98.51%        | 98.53%    | 98.51% | 98.52%   |
| Xception                      | 99.34%         | 97.89%        | 97.92%    | 97.89% | 97.89%   |
| Supervised Contrastive Learning | 98.39%       | 96.35%        | 96.35%    | 96.35% | 96.35%   |

## Conclusion
This project demonstrates the potential of hybrid deep learning models in enhancing diagnostic accuracy. It underscores the importance of robust preprocessing and model evaluation strategies for real-world medical applications.

## Future Work
- Exploration of additional deep learning architectures.
- Application to more diverse datasets.
- Integration with real-time diagnostic tools.

## Authors and Acknowledgments
This project was developed by:
- Shivani Battu
- Likhitha Marrapu
- Chandini Karrothu
- Anuranjani Thota
- Hanan Muhajab
- Areej Muhajab
- Kambiz Ghazinour
- Stacy Miner
- Betis Baheri
- Safa Shubbar
