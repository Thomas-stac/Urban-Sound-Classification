# Urban Sound Classification with Artificial Intelligence

## 📋 Brief description and context

The increasing urbanization of cities has made sound pollution a significant concern for public health. Recognizing this, I collaborated with **Orange Business Digital Services** to design an innovative system for urban sound classification using **deep learning**. This initiative aimed to enhance the monitoring and management of sound pollution in smart cities, particularly in Brussels.

The project leveraged advanced machine learning techniques to classify urban sounds into meaningful categories, facilitating better decision-making for urban planning and noise management. The final solution involved integrating multiple data sources, preprocessing audio data, and developing convolutional neural network models.

---

## 🏆 Achievements

- **Data Integration**: Consolidated data from public datasets like UrbanSound8K, ESC-50, and SONYC-UST-V2 to create a robust, diverse audio dataset.
- **Deep Learning Models**: Built and optimized CNN models (from scratch and pretrained) for sound classification, achieving high accuracy rates.
- **Audio Preprocessing**: Implemented advanced data augmentation techniques to enhance model generalization.
- **Feature Extraction**: Developed Log-Mel spectrogram-based inputs for effective sound classification.
- **Deployment**: Tested the model in real-world scenarios, validating its performance in dynamic urban environments.
- **Collaborative Innovation**: Partnered with Orange Business Digital Services to align AI solutions with the goals of smart cities.

---

## 🎯 Responsibilities

### Needs analysis
- Assessed the requirements for urban sound classification in smart city initiatives.
- Defined key sound categories relevant to urban noise pollution.

### Data preparation
- Collected and merged audio data from various sources.
- Applied preprocessing steps, including:
  - Noise reduction
  - Audio segmentation
  - Spectrogram transformation
- Augmented the dataset using time-stretching, pitch shifting, and noise addition.

### Model development
- Designed and trained three models:
  - **CNN from scratch**: Tailored architecture for urban sound features.
  - **Pretrained InceptionV3**: Fine-tuned for sound classification tasks.
  - **Pretrained EfficientNetB0**: Optimized for computational efficiency and accuracy.

### Evaluation
- Validated models on metrics such as precision, recall, and F1 score.
- Analyzed performance using confusion matrices and learning curves.

### Deployment
- Deployed the best-performing model for real-world testing in urban settings.
- Evaluated its ability to classify overlapping and ambient sounds.

---

## 🛠️ Technology stack

- **Programming Language**: Python
- **Libraries and Tools**:
  - TensorFlow/Keras: For deep learning model development.
  - Librosa: For audio processing and feature extraction.
  - Audiomentations: For data augmentation.
  - Matplotlib: For visualizing spectrograms and learning curves.
  - Pandas & NumPy: For data manipulation.

---

## 🔍 Sample results

### Classes:
- Examples of categorized sounds include:
  - Dog barking
  - Car horn
  - Jackhammer
  - Siren
  - Chainsaw

### Model Performance:
- **Best Model (CNN from scratch)**:
  - Validation Accuracy: **95.3%**
  - Test Accuracy: **95.4%**
- **EfficientNetB0**:
  - Validation Accuracy: **90.9%**
- **InceptionV3**:
  - Validation Accuracy: **85.3%**

---

## 🖥️ Key Code Snippets

The complete implementation of the data preprocessing, model training, and evaluation is included in the **notebook attached to this repository**. For detailed code, please refer to the notebook.

---

## ✨ Relevance to the i-CITY AI Platform Development

This project highlights essential competencies that directly relate to the development of the i-CITY AI platform:

1. **Audio Feature Engineering**:
   - Leveraged advanced audio preprocessing techniques to generate high-quality features for urban sound classification.
   - Relevant for ensuring the platform’s ability to handle varied sound data inputs effectively.

2. **Model Development and Optimization**:
   - Created scalable CNN architectures that achieve high performance.
   - Provides a foundation for implementing complex systems like RAG (Retrieval-Augmented Generation) modules.

3. **Real-World Deployment**:
   - Validated the model in dynamic environments, demonstrating its robustness in handling real-world variability.
   - Supports the creation of automated routing systems for noise detection agents.

4. **Security and Compliance**:
   - Ensured ethical handling and processing of audio data.
   - Aligns with i-CITY's emphasis on data security and regulatory compliance.

By addressing urban challenges with cutting-edge AI techniques, this project serves as a blueprint for integrating intelligent solutions into smart city ecosystems.
