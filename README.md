# One-Shot-Learning-on-Omniglot-data
One shot learning using siamese twins architecture on Omniglot dataset


## Table of Contents
<details open>
<summary>Show/Hide</summary>
<br>

1. [ File Descriptions ](#File_Description)
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
<details>
<a name="File_Description"></a>
<summary>Show/Hide</summary>
<br>
    
* <strong>[ Data ](https://github.com/awesomeahi95/Hotel_Review_NLP/tree/master/Data)</strong>: folder containing all data files
    * <strong>1.tripadvisor_scraped_hotel_reviews.csv</strong>: webscraped data before any changes
    * <strong>2.hotel_reviews_structured.csv</strong>: data after balancing and cleaning
    * <strong>3.x_train_data.csv</strong>: training data with x values from preprocessed dataset
    * <strong>3.y_train_data.csv</strong>: training data with y values from preprocessed dataset
    * <strong>4.x_test_data.csv</strong>: test data with x values from preprocessed dataset
    * <strong>4.y_test_data.csv</strong>: test data with y values from preprocessed dataset
* <strong>[ Images ](https://github.com/awesomeahi95/Hotel_Review_NLP/tree/master/Images)</strong>: folder containing images used for README and presentation pdf
* <strong>[ Models ](https://github.com/awesomeahi95/Hotel_Review_NLP/tree/master/Models)</strong>: folder containing trained models saved with pickle
    * <strong>Adabooost.pkl, Decision Tree.pkl, KNN.pkl, Logistic Regression.pkl, Naive Bayes.pkl, Neural Network.pkl, Random Forest.pkl, Stacking.pkl, SVM.pkl, Voting.pkl, XGBoost.pkl</strong>
