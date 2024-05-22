

# Deep Neural Fuzzy Model for Intrusion Detection

This repository contains the implementation of a Deep Neural Fuzzy Model for intrusion detection. The model integrates deep learning and fuzzy logic techniques to effectively detect intrusions in network traffic.
Intrusion Detection Systems (IDS) are crucial components in cybersecurity that monitor and analyze network traffic or system activities to detect signs of unauthorized access or malicious activities. The idea of this work is to study and implement deep learning approaches to intrusion detection to identify various types of attacks. Towards this approach to intrusion detection that harnesses the combined capabilities of deep neural networks (DNN), multilayer perceptron (MLP), long shortterm memory networks (LSTM), convolutional neural networks (CNN) and fuzzy logic within a unified deep neuro-fuzzy framework. The key differentiator of this system lies in its strategic integration with Principal Component Analysis (PCA) during the training phase, aiming to elevate feature representation and overall model performance. The distinctive feature of this system is the incorporation of PCA, a critical preprocessing step that plays a pivotal role in extracting salient features from the CICIDS2017 and CICDDOS2019 datasets. By leveraging PCA, the dimensionality of the dataset is substantially reduced, allowing the system to focus on essential information vital for effective intrusion detection. This reduction in dimensionality leads to a remarkable enhancement in feature representation, resulting in superior model performance. The integration of PCA acts as a catalyst in the training phase, facilitating the extraction of pertinent information and optimizing the deep neuro-fuzzy system for heightened accuracy and robust generalization capabilities. The results demonstrate that this innovative approach not only improves intrusion detection accuracy but also enhances the system's ability to adapt to diverse and dynamic threat landscapes. Overall, the strategic use of PCA in conjunction with a unified deep neuro-fuzzy framework sets this system apart, making 
it a promising advancement in the field of intrusion detection.

## Dataset
The dataset used for training and evaluation consists of two datasets:
- CICDDoS2019: [Link to Dataset](https://www.unb.ca/cic/datasets/ddos-2019.html)
- CICIDS2017: [Link to Dataset](https://www.unb.ca/cic/datasets/ids-2017.html)

Please refer to the respective links for more information on the datasets.

## Preprocessing
The preprocessing step involves cleaning and transforming the raw data into a format suitable for training the model. This includes data cleaning, feature engineering, and normalization.

## Model Training
The model training phase involves building and training the Deep Neural Fuzzy Model using the preprocessed data. The model architecture and hyperparameters are optimized to achieve high performance in intrusion detection.

## Deployment
The deployment code includes scripts and instructions for deploying the trained model into production environments. This ensures that the intrusion detection system can be effectively utilized for real-time monitoring and protection of network systems.

## Usage
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Deep-Neural-Fuzzy-Model-for-intrusion-detection.git

  

## Acknowledgments
- The CICDDoS2019 dataset was provided by the Canadian Institute for Cybersecurity (CIC).
- The CICIDS2017 dataset was provided by the Canadian Institute for Cybersecurity (CIC).

---
![Images](https://github.com/Vigneshpalan/Deep-Neural-Fuzzy-Model-for-intrusion-detection/blob/main/f1.png)

Feel free to customize this template according to your specific project details and requirements!
