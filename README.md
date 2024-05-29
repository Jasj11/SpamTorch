# SpamTorch
SpamTorch Concept for ICT30016 Innovation
### Description
* The project code is completely done using Python
* Enronmod  and SpamAssassin CSV Dataset’s taken from figshare, link: https://figshare.com/articles/dataset/Curated_Dataset_-_Phishing_Email/24899952.
* Required packages installed, which are pandas, torch, nltk, sklearn, seaborn, matplotlib, genism, numpy
* LSTM Neural Classifier.
* Install Enronmod.csv and SpamAssassin.csv into the /train subdirectory on which you install the SpamTorchTrain.py file.
* Output file (predictions_with_emailid.csv)  produced which shows results of all test records with a note when the predicted Spam or Ham label is different to actual label for manual research.
* The program will skip Noisy data or where the label identifier is missing. In the case of CEAS_08 it does skip a large number of records but it still classify’s over 40000 records. For SpamAssassin.
* A confusion matrix  is also produced to get clear performance of the classification model
* Finally, Classification report has been produced.
* Place Spam2.csv in /Test directory
* Run Spamtorchtest.py option 1. Mismatched_instances.csvis produced to show wrong predictions
* Run retrain.py . It will use mismatched_instances to retrain lstm model.
* Rerun spamtorchtest.py and notice improvement in predictions.
