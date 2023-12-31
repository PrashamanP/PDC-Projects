# Imbalanced-Breast-Cancer-Classification-Using-Transfer-Learning

## ABSTRACT

Accurate breast cancer detection using automated algorithms remains a significant challenge in the literature. Despite numerous attempts to address this issue, an exact solution is yet to be found. The problem is exacerbated by imbalanced datasets, where the number of instances of a particular class far exceeds that of others. This paper proposes a framework based on transfer learning to address these challenges, focusing on histopathological and imbalanced image classification. The EfficientNet-B0 serves as the base model, enhanced with state-of-the-art techniques to improve overall system performance. Utilizing the ImageNet dataset as the source domain, the learned knowledge is applied to the target domain of histopathological images. Experimentation on a large-scale dataset of 277,524 images demonstrates the superior performance of the proposed framework compared to existing literature. Numerical simulations on a supercomputer provide guidelines for transfer learning and imbalanced image classification.

## KEYWORDS

Federated Learning, Breast Cancer Detection, Imbalanced Data, Transfer Learning, Privacy-Preserving Machine Learning

## INTRODUCTION

The challenge of accurately detecting breast cancer using automated algorithms persists in the literature, exacerbated by imbalanced datasets. This paper introduces a transfer learning-based framework to address the complexities of breast cancer detection, specifically focusing on histopathological images with imbalanced class distribution.

The approach leverages EfficientNet-B0 as the foundational model, enhancing its performance through cutting-edge techniques. Transfer learning principles are embraced, applying knowledge gained from the ImageNet dataset (as the source domain) to the target domain comprising histopathological images. Extensive experimentation on a dataset of 277,524 images demonstrates the superior performance of the proposed framework compared to existing methodologies in the literature.

Breast cancer remains a significant global health concern, ranking as the second leading cause of cancer-related mortality among women. Despite advancements in cancer theragnostic approaches, particularly for the Invasive Ductal Carcinoma (IDC) subtype, breast cancer remains a formidable challenge. This project builds upon the proposed solution, employing the transfer learning paradigm to classify histopathological images.

## Result

In this study, we employed the EfficientNet architecture in a federated learning framework with 10 clients, preserving data privacy. Parallelism enhanced model efficiency, enabling faster convergence and concurrent task execution. Results demonstrated EfficientNet's superiority over Logistic Regression in classification accuracy within a federated learning setup, highlighting the benefits of advanced neural networks and parallelism.

 ## Conclusion

The use of EfficientNet proves effective in breast cancer image classification, demonstrating efficiency and accuracy. Federated learning with 10 decentralized clients enables collaborative model training without centralizing patient data, enhancing robustness and privacy compliance.

The integration of parallelism optimizes model efficiency, crucial for scalability in distributed networks. EfficientNet surpasses logistic regression in federated learning, capturing intricate hierarchical features. In decentralized settings, where data complexity and diversity demand sophistication, EfficientNet excels, making it a preferred choice for breast cancer image classification in federated learning.
