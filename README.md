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
   * [ 1. Webscraping, Early EDA, and Cleaning ](#Webscraping_Early_EDA_and_Cleaning)
       * [ Webscraping ](#Webscraping)
       * [ Early EDA and Cleaning](#Early_EDA_and_Cleaning)
   * [ 2. Further EDA and Preprocessing ](#Further_EDA_and_Preprocessing) 
   * [ 3. Modelling and Hyperparameter Tuning ](#Modelling)
   * [ 4. Evaluation ](#Evaluation)
       * [ Future Improvements ](#Future_Improvements)
   * [ 5. Neural Network Modelling ](#Neural_Network_Modelling)
   * [ 6. Revaluation and Deployment ](#Revaluation)
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
<details>
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
</details>

