# One-Shot-Learning-on-Omniglot-data
One shot learning using siamese twins architecture on Omniglot dataset


## Table of Contents
<details open>
<summary>Show/Hide</summary>
<br>

1. [ File Descriptions ](#File_Description)
  * Dataset
  * File Structure
2. [ Technologies Used ](#Technologies_Used)    
3. [ Structure ](#Structure)
4. [ Executive Summary ](#Executive_Summary)
   * [ 1. Why use One-Shot Learning ](#Why use One-Shot Learning)
</details>

## File Descriptions
<a name="File_Description"></a>
<br>
* <strong> [Dataset](https://github.com/brendenlake/omniglot) </strong>: The Omniglot dataset is a collection of 1623 hand-drawn characters from 50 alphabets. For every character there are just 20 examples, each drawn by a different person at resolution 105x105. Each image is paired with stroke data, a sequence of [x,y,t] coordinates with time (t) in milliseconds. This data is split as 30 alphabets used for training and the other 20 used for validation of the model.

![Raw Dataset](https://raw.githubusercontent.com/brendenlake/omniglot/master/omniglot_grid.jpg)
  
* <strong> File Structure </strong>:
  <a name="File Structure"></a>
  >image_background  
  >>Gujarati
  >>>Character01
  >>>>20 images

## Tecnologies Used:
<a name="Technologies_Used"></a>
<br>
* <strong>Python</strong>
* <strong>Pandas</strong>
* <strong>Numpy</strong>
* <strong>Matplotlib</strong>
* <strong>Open CV</strong>
* <strong>Scikit-Learn</strong>
* <strong>Keras</strong>
* <strong>Tensorflow</strong>

<a name="Executive_Summary"></a>
## Executive Summary


<a name="Why use One-Shot Learning"></a>
### Why use One-Shot Learning
In conventional image processing, an image is put through a CNN(Convolution Neural Network) to extract features from which an object/edge is detected or classified, but this is very computationally intense and requires a very large training set to alleviate all bias. Another issue is that when a new set of training data is added the model has to be re-trained. So one-shot learning proposes to extract features from a small set of training data and make a faster prediction based on similarity.
Ex Face unlock in phones take only multiple images of and feature for your face and store it on device but when a new face is added it does not have re-train the entire model, it extracts the features from each image and compares for similarity thus reducing the time it takes to unlock while still being reliable.
<br>
