![Alt Text](https://scx1.b-cdn.net/csz/news/800/2017/honeybees.jpg)

# Health Status of Bee Hives
## Detecting the Health Status of Honeybees with Neural Networks


## Introduction

The use of neocorticoids and other pesticides against insects is a growing problem because they are targeting not only the target insects which can act as pests but also useful ones like honey bees. There is a rapid decrease in the number of insects. Also it was shown before that insecticides can reduce the defense strength of the bee hives against the [varroa mites](https://www.nature.com/articles/s41598-019-44207-1). Without these insects the agriculture will lose a major contributor to the pollination of plants, which can lead to crop failures and famines.
I want to predict the health status of bee hives based on a [kaggle dataset](https://www.kaggle.com/jenny18/honey-bee-annotated-images) that contains 5,100+ bee images annotated with location, date, time, subspecies, health condition, caste, and pollen. 
The first steps will be getting an overview about the dataset and how the different annotations of the pictures are distributed, then I want to build a basic classification models using supervised or unsupervised machine learning and then improve the prediction if possible with CNN and improving it. The final goal it will be to use GCP and Google Vision. The major challenges of this data set will be the different sizes and quality of the bee images and the testing of the model on bee hive livestreams.
The success of this project will be defined by the accuracy of the detection of the health status of bee hives in the real world and the usability for primary stakeholders like beekeepers. 


## Python Modules used:
Pandas / NumPy / Matplotlib / Seaborn / Plotly / Sklearn / Tensorflow / Opencv / Keras

## Conclusion
- [x] Cleaned and balanced the data.
- [x] Made a decent Base Model. 
- [x] Created a CNN that exceeds the Base Model. 
- [x] Moved into the Google Cloud. 
- [x] Created a Google Vision Model.
- [ ] Installed a live tracking device of Temperature and Humidity. 
- [ ] Created an app for detecting the health status of bee hives with GCP


The main goal the make a model that predicts the health status of beehives was fullfilled. The Convolutional Neural Network that I created predicts the test images with an accuracy of 98%. That means the model is right in 98% of the cases.

## Future Work
Implementing an Object Detection Model in GCP to predict live stream images of beehives and track the humidity and temperature of the beehives with a graphical interface.

## Files and Folders

- Bee_images_EDA_and_Basemodel.ipynb : Jupyter Notebook with Exploratory Data Analysis (EDA), python code, visualizations and documentation of the Honey Bee Images Classification
- Bee_Hive_EDA.ipynb : Jupyter Notebook with Exploratory Data Analysis (EDA), python code, visualizations and documentation of the Data of Beehives (Temperature, Humidity, Weight, Flow) 
- Health of Beehives.pdf : Presentation of the results of the Data Visualization
- plots : Folder with images of the plots