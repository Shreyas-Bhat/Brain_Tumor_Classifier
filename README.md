# Brain_Tumor_Classifier

* Used brain MRI images dataset - https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection
* This is a binary classification problem: 
* ```NO``` - no tumor, encoded as 0
* ```YES``` - tumor, encoded as 1
 ![image](https://user-images.githubusercontent.com/56354373/116769624-0ce4d000-aa5b-11eb-8bfb-cb39ba4219d4.png)

=====================================================================================================================
### Results 
* Used transfer learning on CNN based models - 
* Got validation accuracy of 53 using *ResNet101v2* and 72 using *InceptionV3*
* Since, the data is towards the lower end(98 images) I had to use data augmentation, increasing the number of images
* However, the data is still low for the model to train hence, the accuracy doesn't increase and loss doesn't decrease uniformly 
* Can use *OneShot* detection(*siamese network*) to deal with this problem

#### InceptionV3 model
![image](https://user-images.githubusercontent.com/56354373/116769687-8e3c6280-aa5b-11eb-8d5d-3ace89c4ea4d.png)
