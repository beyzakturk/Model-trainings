# Roboflow
Roboflow is a computer vision platform that allows users to build computer vision models faster and more accurately through the provision of better data collection, preprocessing, and model training techniques. Roboflow allows users to upload custom datasets, draw annotations, modify image orientations, resize images, modify image contrast and perform data augmentation. It can also be used to train models.

The entire workflow can be co-ordinated with teams within the framework. For model training, there’s a bunch of model libraries already present such as EfficientNet, MobileNet, Yolo, TensorFlow, PyTorch, etc. Thereafter model deployment and visualization options are also available hence encompassing the entire state-of-art.

## Steps To Use Roboflow in Object Detection:
1.Dataset Loading

2.Labeling

3.Organise

4.Process

5.Train

6.Deploy

7.Display

Roboflow has an account set up for each user. Now we will discuss each of the steps in the task of object detection.

![image in roboflow](https://assets.website-files.com/5f6bc60e665f54545a1e52a5/613bd4a5e9125214f5647303_flow-graphic-mobile.png)

### Dataset Loading
Roboflow has both public and private datasets. Public datasets can be accessed from the website itself and private datasets can be uploaded by users.

![image in roboflow](https://2486075003-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-M6S9nPJhEX9FYH6clfW%2Fuploads%2FEUyPdts5UjIqRdNoZ4np%2FCreate%20a%20new%20project.png?alt=media&token=0d3b7f82-4f39-4402-98fc-d5df1f571bda)

We can select any dataset we feel like from these or upload our own custom dataset from the ‘your dataset’ section. If you wish to use public datasets make sure to fork it after opening. After forking a dataset if we wish we can also add our own images. 

### Labeling
Public datasets come with annotations. For custom datasets, we need to make sure to have annotations. Roboflow annotations aren’t always available to all users but users can contact them for the service. Labelling images can be done with a free open source software LabeIImg in python. Labelling is basically drawing bounding boxes to get the notations of where exactly the object is present in the image. Roboflow has the feature to correct annotation errors and provide statistics of images with and without annotations.

![image in roboflow](https://blog.streamlit.io/content/images/2021/03/Blood_Cell.gif)

### Organise
Team collaboration is easily possible using roboflow team sharing. For every version of changes made to data will be reflected directly to anyone from the team using it. There’s also an option for public sharing which will be reflected in the roboflow community. 

![image in roboflow](https://i.pinimg.com/originals/40/df/96/40df962a6e7d9e0db97fff1e3be0f9f8.gif)

### Process
Various steps are involved in processing such as a health check of the dataset could be done to check if the dataset is imbalanced for classification models and other such insights about data. 
![image in roboflow](https://blog.roboflow.com/content/images/2020/02/detection.gif)

> Thnx for read!

![image in git](https://raw.githubusercontent.com/Potential17/Potential17/master/github-logo-octocat-.gif)
