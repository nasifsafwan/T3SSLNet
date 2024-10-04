# T3SSLNet: Tri-Method Self-Supervised Learning Based Pre-trained Network for MRI Brain Tumor Classification

T3SSLNet is a repository focused on MRI brain tumor classification through the use of self-supervised learning (SSL) techniques. The repository implements three widely-used SSL methods—**SimCLR**, **MoCo**, and **BYOL**—to pre-train deep neural networks for feature extraction from MRI images. These SSL approaches offer a powerful alternative to traditional supervised learning by leveraging large amounts of unlabeled data, making them particularly suited for medical imaging tasks where labeled data is scarce or expensive to obtain.

Each SSL model in T3SSLNet has been adapted to work with two different backbone architectures—**ResNet** and **EfficientNet**—and offers three modes of operation:

1. **Training without fine-tuning ResNet**: This mode uses a pre-trained ResNet backbone without further fine-tuning. It provides a quick evaluation of the model's ability to generalize on MRI brain tumor classification tasks using SSL pre-trained weights.
   
2. **Training with fine-tuning ResNet**: This mode fine-tunes the ResNet backbone, allowing for better feature extraction and adaptation to the specific characteristics of MRI data. Fine-tuning helps improve the model's performance on the downstream classification task.
   
3. **Training with fine-tuning EfficientNet**: EfficientNet, known for its balance of accuracy and efficiency, is used as the backbone in this mode. Fine-tuning EfficientNet can offer performance improvements and is evaluated as an alternative to the traditional ResNet backbone for MRI classification.

T3SSLNet provides a structured framework for researchers and practitioners to explore different SSL methods and backbone architectures for MRI-based brain tumor classification. By offering a variety of training configurations, T3SSLNet enables users to assess the impact of self-supervised learning on medical imaging tasks and optimize models for improved diagnostic accuracy.

This repository is a valuable resource for exploring SSL in the healthcare domain, helping bridge the gap between advanced machine learning techniques and real-world clinical applications.
