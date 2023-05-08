# Education Inequality Overview
## Introduction
The purpose of this project is to determine if school performance predicted by socioeconomic factors. We will use average student performance on ACT and SAT exams, along with basic information and  statistics on the schools that these students attend. 

## Requirements
Software used in this project consists of Google Colab for data preperation and analysis, and excel for the storing of data sets. 

## Data
The data we use in this project comes from EdGap, https://www.edgap.org/#5/37.875/-96.987, and the National Center for Education Statistics, https://nces.ed.gov/ccd/pubschuniv.asp. The EdGap data can be found in the Data folder of this repository, while the NCES data can be found at the following dropbox link: https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0 

## Data Preperation
To prepare the data for this project, we went through both original data sets getting rid of null values where appropriate and replacing out of range values with nulls for later imputation. We also created train and test sets for the data and using an iterative imputer replaced the remaining null values. We were left with two files, "df_train.csv" which contains the prepared training set, and "df_test.csv" which contains the prepared test set. Both of this files can be found in the Data folder. The notebook which executes the preperation is called "DATA_3320_Education_Inequality_Data_Preparation_Hope_Crosier.ipynb" and can be found in the Notebooks folder. 

## Data Analysis
To analyze the data for this project, we fit our data to linear regression models attempting to determine which model led to the most accurate prediction based on the socioeconomic factors we had in our data frames. The code for this analysis can be found in the Notebooks folder in the file called "DATA_3320_Education_Analysis_Hope_Crosier.ipynb". All graphs and models intended for use in a final project conclusion will come from this notebook, and the conclusion slides can be found under the Communication folder under the file named ""

## Author
Hope Crosier is the author of this repository. She is a undergraduate computer science student at Seattle University, and her linked in here: https://www.linkedin.com/in/hope-crosier/

## License
This repository and all corresponding code components are liscenced under the MIT License

