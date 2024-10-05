# T3SSLNet: Tri-Method Self-Supervised Learning Based Pre-trained Network for MRI Brain Tumor Classification

This repository, **T3SSLNet**, focuses on MRI brain tumor classification using self-supervised learning (SSL) techniques. It incorporates three prominent SSL methods—**SimCLR**, **MoCo**, and **BYOL**—to pre-train deep neural networks for feature extraction from MRI images. These SSL methods present a compelling alternative to traditional supervised learning by utilizing large quantities of unlabeled data, making them particularly useful in medical imaging, where labeled data can be scarce or expensive to obtain.

T3SSLNet implements SSL models with two different backbone architectures—**ResNet** and **EfficientNet**—offering three distinct modes of operation:

1. **Training without fine-tuning ResNet**: In this mode, the model uses a pre-trained ResNet backbone without additional fine-tuning, providing a quick evaluation of its generalization ability on MRI brain tumor classification tasks with SSL pre-trained weights.

2. **Training with fine-tuning ResNet**: This mode fine-tunes the ResNet backbone, enhancing feature extraction and better adapting to the unique characteristics of MRI data. Fine-tuning helps improve the model’s performance on the downstream classification task.

3. **Training with fine-tuning EfficientNet**: Known for its balance of accuracy and efficiency, EfficientNet is used as the backbone in this mode. Fine-tuning EfficientNet offers performance improvements and serves as an alternative to the ResNet backbone for MRI classification.

T3SSLNet provides a robust framework for researchers and practitioners to explore the impact of different SSL methods and backbone architectures on MRI-based brain tumor classification. By offering a variety of training configurations, it enables users to optimize models for improved diagnostic accuracy, advancing the application of SSL in medical imaging.

This repository bridges the gap between advanced machine learning techniques and real-world clinical applications, making it a valuable resource for exploring SSL in healthcare.

Here are methodology of our research:

![block_Diagram_V3(LargerFonts)](https://github.com/user-attachments/assets/90df36f7-d039-4719-b601-7cfb18317d47)


If you find **T3SSLNet** helpful in your research or projects, we kindly request that you show your support by starring ⭐, forking 🍴, and citing our repository. Your citation helps to acknowledge the work and effort put into developing this project, and your support encourages further contributions to the open-source community.

**Citation**  
To cite **T3SSLNet** in your research, please use the following:

```
@misc{T3SSLNet2024,
  author = {MD. Nasif Safwan},
  title = {T3SSLNet: Tri-Method Self-Supervised Learning Based Pre-trained Network for MRI Brain Tumor Classification},
  year = {2024},
  howpublished = {\url{https://github.com/username/T3SSLNet}},
}
```

Don't forget to **⭐ star** and **🍴 fork** the repository! Your support is greatly appreciated and helps spread this work to a wider audience.
