# Colorectal_Histology
This project aims to predict subtypes of colorectal cancer using a Convolutional neural network (CNN). 

Datasets obtained from https://www.cancer.gov/ccg/research/genome-sequencing/tcga

[QuPath] (https://qupath.readthedocs.io/en/stable/docs/starting/annotating.html) is used for annotating images.

## Project goal
Multiclass classification of histological images of human colorectal cancer into 4 subtypes:
   - 'CMS1'
   - 'CMS2'
   - 'CMS3'
   - 'CMS4'

## Approach
Images are split into training, validation, and test datasets with a split ratio of 0.8/0.2/0.2. The training dataset is used to train the CNN model;
the validation dataset is used to assess and record the prediction performance during the training process to avoid overfitting and help choose the model
with the best performance; the test dataset is used to evaluate the model and compare the prediction performance using 5-fold cross-validation (CV).
The performance of the method is evaluated using several metrics, including AUROC (Area Under Receiver operating characteristic), accuracy, precision, recall, and  f1-score. 

# Contact
If you have any questions, do not hesitate to contact me at `khojasteh.hb@gmail.com`, I will be happy to assist.
