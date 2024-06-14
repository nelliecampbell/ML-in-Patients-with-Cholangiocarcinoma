# Machine learning model to predict the overall survival status (deceased/living) and the Overall survival in months in patients with Cholangiocarcinoma.

The overall goal for this project was to use a publicly available dataset from The Cancer Genome Atlas Program (TCGA) focusing on patients with cholangiocarcinoma (CCA). 
To date, CCA is the second most common liver cancer after hepatocellular carcinoma (HCC), and patients with its diagnosis have increased over the years (1). 
Even though CCA is a rare cancer, its incidence, however, says otherwise. CCA can develop in one of three anatomical locations, intrahepatic (iCCA), perihilar(pCCA), and distal (dCCA) (2). 
Over the years, the incidence and mortality of CCA have increased enough to make it a world health problem (3), especially the iCCA(2). Nevertheless, CCA remains a rare type of cancer yet to be diagnosed at its early stages. 
This has led to patients having limited treatment options at the time of diagnosis, and surgery is the only possible treatment modality for a cure.

## Workflow

Ingest Data  
Exploratory analysis  
Data Cleaning/Engineering  
ML Target Variable overall survival (Months)  
--Split Data into Target and Features  
--Handle categorical variables before feature selection  
--Feature selection  
--Define models and metrics  
--Cross-validation for the training set  
--Fit the training model and make predictions on the test set  
--Select the best model  
ML Target Variable overall survival status  
--Split Data into Target and Features  
--Handle categorical variables before feature selection  
--Feature selection  
--Define models and metrics  
--Cross-validation for the training set  
--Fit the training model and make predictions on the test set  
--Select the best model  
 

## Major Results

ML Target Variable overall survival (Months) : This target variable tells us the overall survival of patients in months. The best model identified was Linear Regression with an R^2 of 0.31.
ML Target Variable overall survival status: This Target variable tells us what the overall survival status is for the patients i.e. dead or alive. The best model identified was Random Forest with an F1 Score of 0.57.
Overall, the models were not exceptional based on their respective scores, however, this can be due to the limited dataset which comprised of 378 observations and 17 variables.
