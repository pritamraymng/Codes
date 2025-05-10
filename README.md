# Description of project 


(a) Dataset used here can be found here             : https://www.kaggle.com/datasets/ismailpromus/skin-diseases-image-dataset                                
(b) Noise Removed (Cleaned) Images can be found here: https://drive.google.com/drive/folders/1TpaGRqVTySuPr_KVA2am6QDc6nSGS-fw?usp=sharing
(c) Color Features file                             : https://drive.google.com/drive/folders/1TpaGRqVTySuPr_KVA2am6QDc6nSGS-fw?usp=sharing
(d) Texture Features File                           : https://drive.google.com/drive/folders/1TpaGRqVTySuPr_KVA2am6QDc6nSGS-fw?usp=sharing

1. Tha pre-trained ResNet-50 model was combined with handcrafted features. The highest validation accuracy was found by running 20 sweeps of hyperparameters. File name: "resnet_handcode.ipynb"
2. With the best hyperparameters on the validation set, now the code is run on the test set. File name: "test1_handcode.ipynb"
