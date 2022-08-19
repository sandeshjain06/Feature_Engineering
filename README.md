
# Feature_Engineering  -  Missing Values 

1. Missing Values - Complete Case Analysis Problem - Delete the values


        - Discarding those observations where values in any of the variables are missing.
        - Means analyzing those observations for which there is information in all the variables in the dataset.



2. Handling Missing values by Imputating values with Mean , Median .

        
        1. Univariate Imputation : To fill the values if we are taking values from 1 feature only .
                SimpleImputator class is available in sklearn library to work with univariate.
                For numerical - mean , median , random value , End of distribution values.
                For categorial  - mode  . 

       2. Multivariate Imputation -  KNN Imputer , Iterative Imputer
       If we are taking values from more than 1 feature to fill the missing values then called as multivariate imputation.


3. Handling Missing values with Random values and End of Distribution values.





4. Handling Categorial values with Mode and Missing Keyword 

5. Handling Numerical and Categorial values by Random sample Imputation

6. Multivariate Imputation - KNN Imputer , Iterative Imputer 
