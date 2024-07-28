# EMNLP2024 Code Repository

Welcome to the official code repository for our EMNLP2024 submission: **"Automated Tone Transcription and Clustering with Tone2Vec."** 

This repository contains all the experimental details and code discussed in our paper.

## **1. Repository Contents**

### **1.1 Code Structure**
- **Code_emnlp2024.ipynb**: Jupyter notebook containing all experimental code, conducted in Google Colab.
- **emnlp_weights/**: Directory containing pre-calculated Tone2Vec representations.

### **1.2 Experiment Results**

#### **1.2.1 MLPs**
| Model    | Accuracy (%) | Variance |
| -------- | ------------ | -------- |
| Best CNN | 61.01        | 0.1052   |
| MLP (3)  | 11.94        | 0.2880   |
| MLP (4)  | 10.54        | 0.2015   |
| MLP (5)  | 12.65        | 0.2089   |
| MLP (6)  | 20.84        | 0.1894   |
| MLP (7)  | 26.93        | 0.1669   |

#### **1.2.2 Traditional Machine Learning Models**
| Model         | Accuracy (%) | Variance |
| ------------- | ------------ | -------- |
| Best CNN      | 61.01        | 0.1052   |
| XGBoost       | 24.12        | 0.2625   |
| SVM           | 39.34        | 0.1984   |
| Random Forest | 16.63        | 0.2667   |
| GBM           | 24.12        | 0.2115   |
| KNN           | 13.11        | 0.2627   |

### **1.3 Model Parameters**
- **VGG**: Total trainable parameters: 134,271,683
- **ResNet**: Total trainable parameters: 11,171,779
- **DenseNet**: Total trainable parameters: 6,950,659

### **1.4 Detailed Code Structure**
The notebook is structured to align with the paper's sections and tables:
1. **Tone2Vec** (Section 5): Focus on pitch-based similarity tone representation, dialect clustering, and variance analysis.
2. **Tone Transcription** (Section 6.2): Details methods and results for tone transcription accuracy across different conditions (Tables 2 and 3).
3. **Tone Clustering** (Section 7.2): Results in Tables 4, 5, and Figure 6, exploring tone clustering to identify data patterns and groupings.
4. **Additional Experiments**: Conducted during the rebuttal stage to address reviewer feedback and validate findings.

**Please Note:** This is an anonymous version intended for review purposes only. 

The official package will be released upon acceptance of the paper. **Please do not distribute this version.**

