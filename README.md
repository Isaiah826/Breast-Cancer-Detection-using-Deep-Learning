![cancer _cell](cancer cell(7).jpg)
Breast cancer is one of the leading causes of death worldwide, presenting significant challenges for both researchers and medical professionals. Early detection is critical in improving survival rates, and medical imaging has become a vital tool in cancer detection, monitoring, and posttreatment follow up. However, manual interpretation of medical images can be time consuming, prone to human error, and subject to bias. This project utilizes deep learning techniques to automate and enhance the accuracy of breast cancer severity interpretation, helping to overcome these limitations.
In recent years, deep learning has demonstrated promising results in breast cancer detection by automatically extracting features from medical images. In this project, we apply deep learning techniques to the BreakHis dataset, which consists of 7,909 microscopic biopsy images of both benign and malignant breast tumors. These images were taken at four different magnification levels: 40X, 100X, 200X, and 400X. The primary goal of the project is to develop and compare deep learning models that can accurately classify breast tumors as either benign or malignant.

This repository contains three experiments using deep learning models to evaluate their performance in detecting and classifying breast cancer images:
1. CNN with Data Augmentation
2. Transfer Learning with VGG16
3. Transfer Learning with VGG19

We employed pretrained VGG16 and VGG19 models as feature extractors, adding custom fully connected layers for classification. No data augmentation was applied to the transfer learning models, while the CNN model incorporated data augmentation techniques.

Metrics Used for Evaluation: Accuracy,  Precision, Recall Loss
CNN with Augmentation: Achieved 100% accuracy on both the training and testing sets, with a precision score of 90% and a recall of 82.4% on the testing set.
 Transfer Learning with VGG16: Achieved 100% accuracy on both the training and testing sets, with a precision score of 87.6% and a recall of 92.6% on the testing set.
 Transfer Learning with VGG19: Achieved 100% accuracy on both the training and testing sets, with a precision score of 87.39% and a recall of 89.1% on the testing set.


