# SpamTorch
SpamTorch Concept for ICT30016 Innovation
### Description
* The project code is completely done using Python
* CEAS_08  and SpamAssassin CSV Dataset’s taken from kaggle, link: hhttps://figshare.com/articles/dataset/Curated_Dataset_-_Phishing_Email/24899952ttps://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/code.  A sequential emailid column added to both files to provide an easy means to identify records in output files.
* Required packages installed, which are pandas, torch, nltk, sklearn, seaborn, matplotlib, genism, numpy
* LSTM Neural Classifier.
* Install CEAS_08.csv and SpamAssassin.csv into the /train subdirectory on which you install the SpamTorchTrain.py file.
* Output file (predictions_with_emailid.csv)  produced which shows results of all test records with a note when the predicted Spam or Ham label is different to actual label for manual research.
* The program will skip Noisy data or where the label identifier is missing. In the case of CEAS_08 it does skip a large number of records but it still classify’s over 40000 records. For SpamAssassin.
* A confusion matrix  is also produced to get clear performance of the classification model
* Finally, Classification report has been produced.
