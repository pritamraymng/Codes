# Description of project 


(a) Dataset used here can be found here             : https://www.kaggle.com/datasets/ismailpromus/skin-diseases-image-dataset  

(b) Noise Removed (Cleaned) Images can be found here: https://drive.google.com/drive/folders/1TpaGRqVTySuPr_KVA2am6QDc6nSGS-fw?usp=sharing

(c) Color Features file                             : https://drive.google.com/drive/folders/1TpaGRqVTySuPr_KVA2am6QDc6nSGS-fw?usp=sharing

(d) Texture Features File                           : https://drive.google.com/drive/folders/1TpaGRqVTySuPr_KVA2am6QDc6nSGS-fw?usp=sharing

Details of the codes are listed as below:

1. The pre-trained ResNet-50 model was combined 'with' handcrafted features. The highest validation accuracy was found by running 20 sweeps of hyperparameters. File name: "resnet_handcode.ipynb". The runs in wandb can be seen here: https://wandb.ai/ma23m018-indian-institute-of-technology-madras/mtech_project2?nw=nwuserma23m018

2. With the best hyperparameters on the validation set, now the code is run on the test set. File name: "test1_handcode.ipynb". The runs in wandb can be seen from here: https://wandb.ai/ma23m018-indian-institute-of-technology-madras/mtech_project1_test2?nw=nwuserma23m018

3.  The pre-trained ResNet-50 model was combined 'without' handcrafted features. The highest validation accuracy was found by running 20 sweeps of hyperparameters. File name: "without_handcode.ipynb". The runs in wandb can be seen here: https://wandb.ai/ma23m018-indian-institute-of-technology-madras/mtech_project_wh1?nw=nwuserma23m018

4.  With the best hyperparameters on the validation set, now the code is run on the test set. File name: "test_without_hand.ipynb". The runs in wandb can be seen here: https://wandb.ai/ma23m018-indian-institute-of-technology-madras/mtech_project_wh1test_new?nw=nwuserma23m018

5.  The color feature were extracted by a python code and saved in a '.csv' file format. File name: "color.ipynb"

6.  The texture features were extracted by a python code and saved in a '.csv' file format. File name: "texture.csv"

7.  The entire noise removal process of the entire dataset was done by a python code. File name: "final_on_full_data.csv"
