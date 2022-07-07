# MLPublicPres_Baybayin
ML3 Public Presentation with Norman Lapid, Mark Acot and Pauline Guevara

Executive Summary

As Filipino data scientists, the proponents developed a real-time Optical Character Recognition (OCR) model that recognizes baybayin script in response to the call for cultural preservation. The model can recognize Baybayin script in real-time with _**98.51%**_ accuracy using a mobile camera or webcam. A dataset of `38,000` photos of `19` different handwritten Baybayin characters was utilized to train the deep neural networks. The dataset was resized and data augmentation was peformed to prepare the data. A baseline `Convolutional Neural Network (CNN)`, `VGG-16`, `Resnet50`, `Efficientnet B0`, and state-of-the-art `CoAtNet` were all evaluated. The `VGG-16` model obtained the best results, with an accuracy of 98.51%. This is comparable to various previous studies that have an accuracy in the range of 84% - 96.5%, and the other letter classification models trained on the EMNIST dataset, with the highest accuracy of 95.88% for VGG-5(Spinal FC). It is notable that in this study, the older VGG-16 model was able to outperform the newer CoAtNet model.
