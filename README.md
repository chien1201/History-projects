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
- Data Augmentation
- YOLO v4
- Mean Square Error
- Bounding Box Regression

### Accuracy
Public MSE = 0.12298

## 3. DL_comp3
### Description
In this work, we are interested in translating text in the form of single-sentence human-written descriptions directly into image pixels. For example, "this flower has petals that are yellow and has a ruffled stamen" and "this pink and yellow flower has a beautiful yellow center with many stamens". You have to develop a novel deep architecture and GAN formulation to effectively translate visual concepts from characters to pixels.

More specifically, given a set of texts, your task is to generate reasonable images with size 64x64x3 to illustrate the corresponding texts. Here we use Oxford-102 flower dataset and its paired texts as our training dataset.

[Competition3 full description](https://nthu-datalab.github.io/ml/competitions/Comp_03_Reverse-Image-Caption/03_Reverse-Image-Caption.html)
### Features
- Stable Diffusion
- GAN
- Generator & Discriminator
- Data Augmentation

### Accuracy
Evaluation Score = 0.5

## 4. The "Flappy Bird" game (LAB14)
### Description
In this lab, we will introduce the conception of Markov Decision Process(MDP) and two solution algorithms, and then we will introduce the Q-Learning and SARSA algorithm, finally we will use the Q-learning algorithm to train an agent to play "Flappy Bird" game. Then, change the update rule from Q-learning to SARSA(with the same episodes). Give a brief report to discuss the result(compare Q-learning with SARSA based on the game result).

[LAB14 full description](https://nthu-datalab.github.io/ml/labs/14_Q-Learning/14_Q-Learning.html)
### Features
- Reinforcement Learning
- on-policy vs off-policy
- PyGame Learning Environment(PLE)
- Agent training

### Result
[1. Watch the q-learning gameplay demo](q_learning.mp4)

[2. Watch the SARSA gameplay demo](SARSA.mp4)

## 5. Visualization & Style Transfer (LAB11-2)
### Description
Part I (A Neural Algorithm of Artistic Style)
It's about learning how to load and use a pretrained model from tensorflow library and discusses some techniques to visualize what the networks represent in the selected layers. In addition, introducing an interesting work called neural style transfer, using deep learning to compose one image in the style of another image. My execution is to make the building image into the style of starry night of Vincent van Gogh.

Part II (AdaIN)
AdaIN can transfer arbitrary new styles in real-time, combining the flexibility of the optimization-based framework and the speed similar to the fastest feed-forward approaches. At the heart of this method is a novel Adaptive Instance Normalization (AdaIN) layer aligning the mean and variance of the content features with those of the style features. Instance normalization performs style normalization by normalizing feature statistics, which have been found to carry the style information of an image in the earlier works. A decoder network is then learned to generate the final stylized image by inverting the AdaIN output back to the image space. Implement AdaIN layer and use single content image to create 25 images with different styles. We use MSCOCO 2014 testing dataset as our content dataset, while using WikiArt testing dataset as style dataset. 

[LAB11-2 full description](https://nthu-datalab.github.io/ml/labs/11-2_Visualization_Style-Transfer/11-2_Visualization_Style-Transfer.html)
### Featurea
- VGG19
- Visulaize CNN
- Content and style representations
- Guided-Backpropagation
- AdaIN
  
### Result
[1. The original](kao.png)

[2. The starry night style](kao_starry_night.png)

[3. The 25 styles from AdaIN](outputs.png)

(The outputs in jupyter notebook is deleted due to the large data size it contains.)
