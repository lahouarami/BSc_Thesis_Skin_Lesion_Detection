# SKIN LESION DETECTION FROM DERMOSCOPIC IMAGES USING CONVOLUTIONAL NEURAL NETWORKS

# Author: Adrià Romero López
Advisor: Dr. Oge Marques from the Florida Atlantic University (FAU)

Co-Advisor: Dr. Xavier Giró-i-Nieto from the Universitat Politècnica de Catalunya (UPC)

The recent emergence of machine learning and deep learning methods for medical image analysis has enabled the development of intelligent medical imaging-based diagnosis systems that can assist physicians in making better decisions about a patient’s health. In particular, skin imaging is a field where these new methods can be applied with a high rate of success. 

This thesis focus on the problem of automatic skin lesion detection,  particularly on melanoma detection, by applying semantic segmentation and classification from dermoscopic images using a deep learning based approach. 

For the first problem, the U-Net convolutional neural network architecture is applied for an accurate extraction of the lesion region. 

For the second problem, the current model performs a binary classification (benign versus malignant) that can be used for early melanoma detection. The model is general enough to be extended to multi-class skin lesion classification. The proposed solution is built around the VGG-Net ConvNet architecture and uses the transfer learning paradigm. 

Finally, this work performs a comparative evaluation of classification  alone (using the entire image) against a combination of the two approaches (segmentation followed by classification) in order to assess which of them achieves better classification results.

Experimental results for the classification task are encouraging: on the ISIC Archive dataset, the proposed method achieves an accuracy on the top three best previously published results. The experimental results of the segmentation evaluations demonstrate that the proposed method can outperform other state-of-the-art models.


Keywords: Medical Image Analysis, Deep Learning, Medical Decision Support Systems, Convolutional Neural Networks, Transfer Learning, Machine Learning, Melanoma, Dermoscopy, Skin Lesions, Skin Cancer.
