# Pneumonia_readmission_survival_ML

The codes for survival ML predictive models for pneumonia readmission risks in middle-aged and elderly patients. 

- We used the time-to-event algorithms provided by the scikit-survival library, available at http://jmlr.org/papers/v21/20-729.html.

- The hyperparameter optimisation was performed using GridSearchCV on the training set. The performances of the tuned models were compared on the validation set. 

- The best model was tested on the hold-out set.

- We used the SurvSHAP package (available at https://github.com/MI2DataLab/survshap) to investigate the importance of each feature in the best model. 
