# A. Deep-Learning projects
## 1. DL_comp1
### Description
In this competition, you are provided with a supervised dataset X consisting of the raw content of news articles and the binary popularity (where 1 means "popular" and −1 means "unpopular", calculated based on the number of shares in online social networking services) of these articles as labels. Your goal is to learn a function f from X that is able to predict the popularity of an unseen news article.

[Competition1 full description](https://nthu-datalab.github.io/ml/competitions/Comp_01_Text-Feature-Engineering/01_Text_Feature_Engineering.html)
### Features
- BeautifulSoup
- Preprossesor of contents
- The Bag-of-Word model
- Random Forest Classifier
### Accuracy
around 60% 

## 2. DL_comp2
### Description
In this competition, you have to train a model that recognizes objects in an image. Your goal is to output bounding boxes for objects. 
Dataset: PASCAL VOC2007
The dataset contains 20 classes. The train/val data has 5012 images containing 12608 annotated objects. We have preprocessed training dataset(5012 images) and testing dataset(4953 images) for you. 

[Competition2 full description](https://nthu-datalab.github.io/ml/competitions/Comp_02_Object-Detection/02_Object_Detection.html)
### Features

### Accuracy
Public MSE = 0.12298

## 3. DL_comp3
### Description
In this work, we are interested in translating text in the form of single-sentence human-written descriptions directly into image pixels. For example, "this flower has petals that are yellow and has a ruffled stamen" and "this pink and yellow flower has a beautiful yellow center with many stamens". You have to develop a novel deep architecture and GAN formulation to effectively translate visual concepts from characters to pixels.

More specifically, given a set of texts, your task is to generate reasonable images with size 64x64x3 to illustrate the corresponding texts. Here we use Oxford-102 flower dataset and its paired texts as our training dataset.

[Competition3 full description](https://nthu-datalab.github.io/ml/competitions/Comp_03_Reverse-Image-Caption/03_Reverse-Image-Caption.html)
### Features

### Accuracy
Evaluation Score = 0.5

