# MelanomaDetectionCNN
> CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosi


## Table of Contents
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The model overfit's initially due to which the validation and training accuracy were way off from each other
- Adding of data augmentation techniques like geometric transformations help reduce this gap
- Addition of a Dropout layer also helped in reducing the Overfit of the model
- We also observed a class imbalance in the DataSet
- We used Augmentor to add 500 samples to each class to reduce imbalance
- This helped us build the final model, and we achieved a training accuracy of ~90 and Validation accuracy of ~80

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python3
- tensorflow
- keras
- numpy
- augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@yashyasviagarwal] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->