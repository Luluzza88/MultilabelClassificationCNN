# MultilabelClassificationCNN
Final Project of Data Science Course that I've worked on at WBS Coding School.

**Building a Multilabel Classifier using Convolutional Neural Network and Transfer Learning with Tensorflow Keras**


## Background 
The pollution of the planet and our environment has always increased and governments and international organizations are failing to deal with this crisis. The effects on nature, marine animals and biodiversity are catastrophic and sometimes irreversible. Revolutionary waste management, intelligent waste sorting or smart bins in city centers could be developed with the help of computer vision, and recycling could be automated through image recognition processes.

For the purpose and given time on this project I decided to build a Multilabel Classification Model, where one Image, can be classified into two or more classes. For example, one image can display different types of litter. To build a base model, an open image dataset was used. The dataset is based on COCO annotations and was made for object detection purposes using pretrained models. All images are labeled into 60 categories or 28 subcategories and the dataset holds almost 5000 annotations, e.g. Bounding Boxes, Segmentation. 

Images that are taken in the wild often contain more objects, have different backgrounds or even contexts. Detecting trash in the wild can be a very challenging problem because it needs a model that is aware of the vast diverse features that make out the real world. 

*WORK STILL IN PROGRESS (10.12.21)

**DATASET**
http://tacodataset.org/

## Explorations in Trash Detection

This repository contains some of my attempts to classify images using the TACO dataset, using Keras, Tensorflow and Scikit-Learn. The problem is a multi-label classification problem with a very imbalanced dataset and limited  

My attempts so far include:
- A Convolutional Neural Network trained only on images of the TACO dataset.
- Transfer Learning using the VGG16 pre-trained model and a dense network layer
- Transfer Learning using the Xception pre-trained model and a dense network layer
- Transfer Learning using the Xception pre-trained model and a random forest

Unfortunately, the results aren't too good in terms of accuracy, even with massive use of data augmentation. Turns out it's *really* hard to teach a machine the context needed to show when a plastic bottle is just a plastic bottle and when it is actually trash

**DEPENDENCIES** numpy, scipy, scikit-learn, Tensorflow Keras



