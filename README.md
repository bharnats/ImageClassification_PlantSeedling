# Plant Seedlings_Image Classification
## Objective:
This project is to build an image classifier for plant species by building a CNN architecture and training it to classify plant seedlings. To further improve the performance, a filter is created with OpenCV to mask the background of the images and improved the accuracy by 3%.
## Data Description:
The dataset is available here https://www.kaggle.com/c/plant-seedlings-classification/data?select=train
The Dataset contains images of plant seedlings at various stages of  grown. Each image has a filename that is its unique id. The dataset comprises 12 plant species. The goal of the projectis to create a classifier capable of determining a plant's species from a photo.
## Dataset
The data file names are:
* images.npy
* Label.csv
The original files are from Kaggle.Due to the large volume of data, the images are converted to images.npy file and the labels are  also  put  into  the  Labels.csv. The list of Species is as follows:
`Black-grass`
`Charlock`
`Cleavers`
`Common Chickweed`
`Common wheat`
`Fat Hen`
`Loose Silky-bent`
`Maize`
`Scentless Mayweed`
`Shepherds Purse`
`Small-flowered Cranesbill`
`Sugar beet`
## Context:
* Can We differentiate a weed from a crop seedling?
The ability to do so effectively can mean better crop yields and better stewardship of the environment.The Aarhus University Signal Processing group, in collaboration with University of Southern Denmark, has recently released a dataset containing images of unique plants belonging to 12 species at several growth stage
## Libraries Used in This Project
* openCV
* tensorflow
* Keras
* scikit-learn
## Possible Further Improvements
* Consider some pre-trained models, e.g. InceptionResNetV2.
* Generate more training data.
* Increase the number of layers to be re-trained.
