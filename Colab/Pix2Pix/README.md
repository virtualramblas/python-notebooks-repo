## Pix2Pix for Satellite-to-Map Image Translation in Keras
Notebooks for the data preparation and training of a pix2pix GAN [Keras](https://keras.io/) implementation from [Jason Brownlee](https://machinelearningmastery.com/how-to-develop-a-pix2pix-gan-for-image-to-image-translation/) following [this paper](https://arxiv.org/abs/1611.07004) (the official paper implementation is in PyTorch). The purpose of this Keras model is satellite images translation into Google Maps images.  
This repo includes 2 notebooks:  
* [Data Preparation](https://github.com/virtualramblas/python-notebooks-repo/blob/main/Colab/Pix2Pix/Pix2Pix_for_Satellite_to_Map_Image_Translation_Data_Preparation.ipynb)  
* [Training](https://github.com/virtualramblas/python-notebooks-repo/blob/main/Colab/Pix2Pix/Pix2Pix_for_Satellite_to_Map_Image_Translation_Model_Training.ipynb)  
    
Execute the Data Preparation notebook first. The prepared training data would be saved in Numpy compressed array format in your mounted Google Drive (follow the instructions in the notebook itself for this task). Then execute the training: the preliminary saved data would be loaded from your Google Drive. At the end of the training you can programmatically save model checkpoint to your mounted Google Drive within the notebook itself.
