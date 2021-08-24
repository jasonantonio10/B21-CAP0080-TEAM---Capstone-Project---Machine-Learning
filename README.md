# B21-CAP0080-TEAM---Capstone-Project---Machine-Learning
Repository for Machine Learning part of Bangkit 2021 Capstone Project titled "Skin disease image classification"

## Transfer Learning using MobileNetV2
* See 'requirements.txt' for packages that need to be installed.
* There is a header above each cell in the notebook "ModelSkinDiseaseClassification.ipynb" that explain what each cell does.
* Under "Preparing directories for dataset", set the main directory path as wished, along with the path to sub-directories that will be used as classes for the classification.
* Number of sub-directories needed will be the same as the no.of classes for classification.
* Name of sub-directories under training and testing directories will be the classes/labels name.
* After setting the right path to the needed directories, use the os.mkdir() function provided and run the whole cell once.
* In the cell under "Data random sampling and splitting into training and validation data", use the split_data function and adjust the splitting ratio as wished.
* Set the path to source directory from which images will be copied and set also the destination path to the respective sub-directories to which images will be copied.
* In the cell under "Image data augmentation and pre-processing using Keras ImageDataGenerator and MobileNetV2 preprocessing function" adjust paramaters for augmentation in the ImageDataGenerator class.

## Results
Achieved 83.7% training accuracy eventhough only managed to reach 64.47% validation accuracy due to imbalanced and high variance in image data. Further improvement is required. The use of image segmentation before feeding into the neural network may be tried, along with other sampling techniques.

