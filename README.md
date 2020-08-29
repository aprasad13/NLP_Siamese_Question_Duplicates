# NLP_Siamese_Question_Duplicates

Many times there are several questions that are already asked in quora, or other platforms. This notebook shows a method which can rectify this problem or in other words I can say that it can detect the two duplicate questions. To achive this task I have used <strong>Siamese networks</strong> which consists of two parallel layers of embedding + LSTM + deep_layer

Click on [Jupyter Notebook](https://github.com/aprasad13/NLP_Siamese_Question_Duplicates/blob/master/Siamese_Model_Question_Duplicates.ipynb) to access the code and click [Quora Questions](https://drive.google.com/drive/folders/10LjGuJQFNAf_5NqM2DyRlJ2V4anfFUNt?usp=sharing) to access the dataset

## Overview

- Imported the Data
- Splitted the data into train and test set
- Converted the questions(data) into tensors
- Created the validation set
- Created a function for data generator
- Created a function to implement <strong>Siamese model</strong>.
- Computed <strong>Triplet Loss with Hard Negative Mining</strong>
- Trained the Siamese model(Optimiser = Adam) and checked the performance on validation set 
- Evaluated the the model on test data and achieved an <strong>accuracy of 71.5%</strong>
- Created a predict function which helped in Testing with our own questions
