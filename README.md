# Project Name
> Melanoma Cancer Detetction Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Build a CNN Model to detect Melanoma, a type of Skin Cancer which can be deadly if not detected early. 
- A solution that can evaluate images and alter dermatologists about the presence of Melanoma.
- The project is inspired to support the efforts to reduce the deaths caused by skin cancer. Nueral Netwroks have proven to be effective models and its usage would help considerably. 
- The dataset consists of 2357 images of malignant and benign oncological diseases which were formed from International Skin Imaging Collaboration.
- All the images were sorted according to the classification taken ISIC.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The initial Model built was underfitting and the accuracy was not good. The model built is very initial model with mo dropouts or batch normalization. Training and validation losses have been going down as the number of epochs increased. There isnt much difference in training and validation accuracy and both training and validation accuracy is low which suggests that model is underfitting and needs improvement.
- After data augmenting the model seems to be a good model. There isnt much different between training and validation accuracies and training and validation loss both. However, the accuracy is stil low which suggests the areas of improvement in terms of class imbalance. 
- Class Imbalance surely helped as it prevented model from being baised towards a certain set of classes. Along with class rebanace, ffter tweaking hyperparamaters and model architecture by adding one more Convoluational layer, model accuracy significantly increased. As the epochs proceeded, there hasn been lesser difference in training and testing accuracies. 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - 2.15.0
- matplotlib - 3.7.1
- numpy - 1.25.2
- pandas - 2.0.3
- keras - 2.15.0
- Augmentor-0.2.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@jayasingh0742-coder] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->