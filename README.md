# Pneumonia-Classification-with-Chest-X-ray-using-Depthwise-CNN-and-Partial-transfer-learning

The layers in this network is using depthwise seperable convolutional layers, with the addition of batch normalization to enhance the learning of this model. The weights of the inital layers were transferred from VGG16, and subsequent layers trained on the chest x-ray dataset. 


The dataset can be obtained here: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia


**Credits**
This project and idea of using seperable ConV layers was inspired by this user: https://www.kaggle.com/aakashnain/beating-everything-with-depthwise-convolution?kernelSessionId=4028995, where individual parameters and dataset seed changes were experimented. 
