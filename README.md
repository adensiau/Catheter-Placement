# **🏥 Catheter Placement**

**Description**

This project focuses on classifying catheter placements in X-ray images using deep learning. A convolutional neural network (CNN) was trained to categorize catheter positions as normal, abnormal, or borderline. The goal was to assist in automated medical image analysis for improved clinical decision-making.


**🔍 Features**

* CNN-based classification of catheter placements
* Multi-class labeling (normal, abnormal, borderline)
* Data preprocessing and augmentation for improved model generalization
* Model explainability using LIME to visualize predictions

  
**📂 Dataset/Resources**

* X-ray images of catheters
* Annotations with catheter placement details
* Data preprocessing scripts for cleaning and augmentation

  
**⚙️ Tech Stack**

* Python, TensorFlow, Keras 
* OpenCV, NumPy, Pandas
* Matplotlib, Seaborn (for visualization)


**📊 Results & Insights**

* Addressed class imbalance by using data augmentation & weighted loss
* Model performance improved with EfficientNet over a basic CNN
* LIME-based explainability provided insights into prediction behavior

