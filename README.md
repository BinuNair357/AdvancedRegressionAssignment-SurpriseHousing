# Project Name
> AdvancedRegression-SurpriseHousing
Creating model on Surprise housing dataset using Lasso and Ridge regression



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company wants to know:
	- Which variables are significant in predicting the price of a house
	- How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusion
1. Optimum value for lambda in ridge regression is 200
2. Optimum value for lambda in lasso regression is 0.001
3. r2_score in train dataset: r2_score for ridge: 0.938, r2_score for lasso: 0.944
4. r2_score in test dataset: r2_score for ridge: 0.919, r2_score for lasso: 0.914
5. Using Ridge the top 5 +ve Predictors are :
    * OverallQual_Excellent         
    * OverallQual_Very Good  
    * 1stFlrSF            
    * TotalBsmtSF       
    * GrLivArea         
6. and top 5 -ve coefficients for Ridge are : 
    * OverallQual_Below Average
    * YearRemodAdd_Age        
    * Neighborhood_MeadowV    
    * OverallCond_Below Average 
    * Neighborhood_Edwards     
7. Using Lasso the top 5 +ve coefficients are for 
    * RoofMatl_WdShngl       
    * OverallQual_Very Good   
    * RoofMatl_CompShg        
    * TotalBsmtSF            
    * GrLivArea               
8. and top 5 -ve coefficients for Lasso are :
    * Age                        
    * OverallCond_Average        
    * OverallCond_Below Average   
    * YearRemodAdd_Age            
    * OverallQual_Below Average   

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - sklearn - version 1.0.2
- library - pandas - version 1.18.1
- library - numpy - version 1.18.1
- library - seaborn - version 0.12.0
- library - matplotlib - version 3.1.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@BinuNair357] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->