# T3SSLNet: Tri-Method Self-Supervised Learning Based Pre-trained Network for MRI Brain Tumor Classification

## Overview

In medical imaging, specifically MRI brain tumor classification, the challenge of limited labeled data remains a significant barrier to developing robust and accurate deep learning models. To address this issue, we introduce **T3SSLNet**—a repository designed to leverage self-supervised learning (SSL) techniques for MRI brain tumor classification. SSL allows models to learn from large quantities of unlabeled data, which is particularly advantageous in medical domains where annotating data is time-consuming and costly.

**T3SSLNet** integrates three popular SSL methods—**SimCLR**, **MoCo**, and **BYOL**—each of which has proven highly effective in learning visual representations without the need for labeled data. By employing these SSL techniques, we aim to improve feature extraction from MRI scans and enhance model performance on downstream tasks like brain tumor classification.

The framework is designed to work with two backbone architectures: **ResNet** and **EfficientNet**, offering users the flexibility to choose the architecture that best suits their needs. Furthermore, T3SSLNet supports three distinct training configurations:

1. **Training without fine-tuning ResNet**: A quick evaluation mode that uses pre-trained ResNet weights to assess how well the SSL method generalizes to the MRI brain tumor classification task.
   
2. **Training with fine-tuning ResNet**: This mode fine-tunes the ResNet backbone for better adaptation to the MRI data, improving the model’s overall classification performance.
   
3. **Training with fine-tuning EfficientNet**: EfficientNet is known for its efficiency in balancing accuracy and computational cost. Fine-tuning this architecture provides another approach for achieving high performance in MRI classification.

The primary goal of **T3SSLNet** is to offer a structured framework for exploring SSL in healthcare, specifically for medical image analysis. By optimizing models through SSL pre-training and fine-tuning, T3SSLNet bridges the gap between cutting-edge machine learning techniques and their practical applications in clinical diagnostics.

This project provides a valuable resource for researchers and developers looking to harness the power of SSL for MRI brain tumor classification, and ultimately, improve diagnostic accuracy in medical imaging tasks.
### Data Distribution
![data_distribution](https://github.com/user-attachments/assets/a1ddb8b6-8a69-490e-a764-97a662d5f068)


## Methodology



## Results
### SimCLR
![SimCLR_LossVsAccuracy](https://github.com/user-attachments/assets/9a98c836-ff05-45b4-925c-9bb02442da8f)
### MoCo
![MoCo_LossVsAccuracy](https://github.com/user-attachments/assets/63c6119b-5eb5-47e8-b7d2-25444fb4705f)
### BYOL
![BYOL_LossVsAccuracy](https://github.com/user-attachments/assets/21bccc19-3972-4689-9f2f-57637f9516dd)

If you find **T3SSLNet** helpful in your research or projects, we kindly request that you show your support by starring ⭐, forking 🍴, and citing our repository. Your citation helps to acknowledge the work and effort put into developing this project, and your support encourages further contributions to the open-source community.

**Citation**  
To cite **T3SSLNet** in your research, please use the following:

```
@misc{T3SSLNet2024,
  author = {Md. Nasif Safwan,Souhardo Rahman,Mahamodul Hasan Mahadi,Taharat Muhammad Jabir,Iftekharul Mobin(Corresponding Author)},
  title = {T3SSLNet: Tri-Method Self-Supervised Learning Based Pre-trained Network for MRI Brain Tumor Classification},
  year = {2024},
  howpublished = {\url{https://github.com/nasifsafwan/T3SSLNet}},
}
```

Don't forget to **⭐ star** and **🍴 fork** the repository! Your support is greatly appreciated and helps spread this work to a wider audience.
