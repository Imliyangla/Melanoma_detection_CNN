# Melanoma detection
> This project aims to develop a custom convolutional neural network (CNN) for accurately detecting melanoma, a deadly form of skin cancer. Leveraging a dataset of 2357 images showcasing various skin diseases, the CNN model will be trained to classify and distinguish between malignant and benign lesions, aiding in early diagnosis and treatment.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- `Background`: The project addresses the critical need for early detection of melanoma, a deadly form of skin cancer responsible for a significant portion of skin cancer-related deaths.
- `Aim`: The aim is to develop a custom convolutional neural network to accurately classify skin lesions, particularly focusing on detecting melanoma.
- `Dataset used`: The dataset comprises 2357 images of malignant and benign skin lesions, sourced from the International Skin Imaging Collaboration (ISIC). It includes various oncological diseases such as melanoma, nevus, and squamous cell carcinoma, among others. The dataset exhibits class imbalances, necessitating augmentation techniques for model training.




Project pipeline:

1. `Data Understanding`: Defined paths for train and test images and counted the number of samples in both sets.
2. `Dataset Creation`: Created train & validation datasets with images resized to 180x180.
3. `Dataset Visualization`: Visualized one instance of all nine classes in the dataset.
4. `Model building & training- 1st attempt`: Built a CNN model to detect 9 classes after normalizing pixel values, choosing optimizer & loss function.
     the model was trained for ~20 epochs and assessed for overfitting/underfitting.
5. `Data Augmentation`: Implemented augmentation strategies to mitigate overfitting/underfitting.
6. `Model building & training on augmented data - 2nd attempt`: Evaluated effectiveness of the model after applying augmentation layer to reduce overfitting.
7. `Class Distribution Analysis`: Identified classes with the least samples and determined classes dominating the dataset.
8. `Class Imbalance Handling`: Used Augmentor library to rectify class imbalances.
9. `Final Model building & training`: Trained final model on balanced data for ~30 epochs.
10. `Model Validation & Conclusion`: Evaluated model performance by testing with test(unseen) data set for predictive abiblity. 







## Technologies Used
- tensorflow - version 2.16.1
- matplotlib - version 3.8.4
- Augmentor - version 0.2.12
- pandas - version 2.2.1
- numpy - version 1.26.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- would like to thank UpGrad for giving us the oppurtunity to work on this project.


## Contact
Created by [Imliyangla](https://github.com/Imliyangla) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->