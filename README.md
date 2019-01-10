# DialectClassification
A machine learning project to classify English Dialects and Accents.				

Problem Statement:
Dialects are nothing but variation of pronouncing a particular language spoken by a group of people within a community. Dialects commonly represent the changing speaking patterns observed in the group of native speakers belonging to some particular region. These dialects are responsible for failure of Automatic Sound recognition systems. So Dialect Classification is an interesting Signal-Processing-Pattern-Recognition problem.  The problem statement of the project is to classify the dialects of British English. There are many dialects in British English language and for the project purpose we consider nine regions (dialects). 

Dataset:
The speech corpus IViE (Intonational Variation in English) should be used in the project. The dataset includes nine dialects of  British English, spoken across the nine various regions of the  British Isles. The speech is in read mode i.e. the speakers are reading sentences. The speakers read the cindrella story with intention of investigating cross-varietal and stylistic variations in English intonations across nine regions. The Read_ Up directory has 9 sub-directories (IDR1,IDR2,…..) which has 67 wav files in each sub-directory. The speakers are both male and female. 

Approach:
Read few articles regarding this problem, and propose suitable features that should be computed on a window of signal. Refer to speech literature for what is a suitable window. Then find a way to aggregate features at the audio file level. Perform train and test split, and report results of dialect classification with atleast 3 classifers – K Nearest Neighbour (K=3,5), Logistic Regression and SVM with Linear Kernel. You can use toolboxes for feature extraction and classifiers. 
