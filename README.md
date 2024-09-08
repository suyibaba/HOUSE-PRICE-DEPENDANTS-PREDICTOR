# HOUSE-PRICE-DEPENDANTS-PREDICTOR


    Estimating the sale prices of houses and the imoact on the various independent variables on the house price
  
  
Various types of linear regression algorithm where use for the model development.
      Linear regression was used as it is an algorithm used to predict values that are continuous in nature
      
      
To predict the sale prices i used the following linear regression algorithms: Ordinal Least Square (OLS) algorithm, Ridge regression algorithm, Lasso regression algorithm.These algorithms can be feasibly implemented in python with the use of the scikit-learn package.


Finally, i concluded which model is best suitable for the given case by evaluating each of them using the evaluation metrics provided by the scikit-learn package. R square


                                  **Steps Involved
                                  Importing the required packages into our python environment
                                  Importing the house price data and do some EDA on it
                                  Data Visualization on the house price data
                                  Feature Selection & Data Split
                                  Modeling the data using the algorithms
                                  Evaluating the built model using the evaluation metrics
            
      
      
      
The Notebook containing all the inputs and Outputs are in the file already


![image](https://user-images.githubusercontent.com/64482231/186757625-398ba4a2-cbc5-4de9-ac43-640c208f6cdc.png)


                    this shows a more linear relationship between crime rate and housing price
                    Also no outliers visible
                    
                    
![image](https://user-images.githubusercontent.com/64482231/186757840-5aa65c35-6d01-4ef7-9ebe-d351f9001825.png)

                Above is the correlation between the variables
                
![image](https://user-images.githubusercontent.com/64482231/186758042-11fb252b-e04f-4dba-8239-04521fe9446b.png)
                LINEAR REGRESSION PREDICTION USING OLS ORDINARY LEAST OF SQUARE METHOD
                FROM THE P VALUE, WE CAN SAY THERE IS A RELATIONSHIP BETWEEN THE PRICE VARIABLE AND THE ROOM NUMBER
   
   
![image](https://user-images.githubusercontent.com/64482231/186758258-91960c32-f368-4707-bed8-a94a369edfd9.png)

                    LINEAR REGRESSION PREDICTION USING SKLEARN LIBRARY
                    
             
     
We can see that, every model while rounding the output values will result in a score of 0.75 (75%) above which means our model performs well on our dataset and can be used to solve real-world problems.
