# Education - Introduction
The purpose of this project is to determine if school performance predicted by socioeconomic factors. We will use average student performance on ACT and SAT exams, along with basic information and  statistics on the schools that these students attend. 

## Data
The data we use in this project comes from EdGap, https://www.edgap.org/#5/37.875/-96.987, and the National Center for Education Statistics, https://nces.ed.gov/ccd/pubschuniv.asp. The EdGap data can be found in the Data folder of this repository, while the NCES data can be found at the following dropbox link: https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0 

## Data Preperation
To prepare the data for this project, we went through both original data sets getting rid of null values where appropriate and replacing out of range values with nulls for later imputation. We also created train and test sets for the data and using an iterative imputer replaced the remaining null values. We were left with two files, "df_train.csv" which contains the prepared training set, and "df_test.csv" which contains the prepared test set. Both of this files can be found in the Data folder. The notebook which executes the preperation is called "DATA_3320_Education_Inequality_Data_Preparation_Hope_Crosier.ipynb" and can be found in the Notebooks folder. 
