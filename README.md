## 1- data preprocessing
## 2- LSTM :
               recall_score : 0.7877673672498589
               precision_score : 0.7878267057080199
               accuracy_score: 0.7881321090859257
               f1_score: 0.7874140608853802
## 3- Bilstm-SA : 
       ### data preprocessed:(11 epochs)
                  Test Accuracy: 0.7977
                  Test f1 score: 0.8328
                  Test precision: 0.8663
                  Test recall: 0.8037
       ### data non-preprocessed :(11 epochs)
                  Test Accuracy: 0.8107
                  Test f1 score: 0.7975
                  Test precision: 0.8174
                  Test recall: 0.7790
       ### Emojis Removed  :(11 epochs)
                  Test Accuracy: 0.8099
                  Test f1 score: 0.8003
                  Test precision: 0.8363
                  Test recall: 0.7689
       ### Non-arabic characters removed :(20 epochs)
                  Test Accuracy: 0.6999
                  Test f1 score: 0.6893
                  Test precision: 0.7383
                  Test recall: 0.6487
       ### Lemmatisation :(10 epochs)
                  Test Accuracy: 0.8127
                  Test f1 score: 0.8041
                  Test precision: 0.8358
                  Test recall: 0.7756
       ### Oversampling: (10 epochs)
                  Test Accuracy: 0.8769
                  Test f1 score: 0.8970
                  Test precision: 0.9162
                  Test recall: 0.8799
       ### (Oversampling + Lemmatisation): (10 epochs)
                  Test Accuracy: 0.8851
                  Test f1 score: 0.9033
                  Test precision: 0.9187
                  Test recall: 0.8887
## 4- Arabert :   
       ### data preprocessed:(4 epochs)
                  macro_f1: 0.8537773150786143
                  macro_precision: 0.8559025206394384
                  macro_recall: 0.8545235727316383
                  eval_accuracy: 0.8541143144332252
       ### (Oversampling + Lemmatisation): (4 epochs)
                  macro_f1: 0.9167411615817109
                  macro_precision: 0.9173708659175648
                  macro_recall: 0.9172294395960003
                  eval_accuracy: 0.9171232876712329
                 
