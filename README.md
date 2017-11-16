# MSBD-6000B-Proj_2
Flower images classification applying transfer learning
# Predicted_Result
In this floder, the predicted result of test images stores in it, which is a txt file, 
each line denotes the predicted class of 0~4 corresponding to the sequence of test images.
# Report
In this floder, the report of this project stores in.
# TrainingProcess_Document
In this floder, the training process of the transfer learning model was recorded in the pdf file, including all 40 epochs 
of training, accuracy and the highest accuracy.
# Flowers
In this floder, the data set was stored here. Subfloders included train, val, test which denoted each type of data.
# model
The best model with the accuracy of 94% was stored here. TL.pkl
# image_Preprocessing.py
It is the image preprocessing code which mainly used for resize the image to 224*224 and rebuilt new image floders.
# transfer_Learning.py
It is the code of training the model.
# use_Model.py
It is the function of applying the best model to predict test images.
# Note
The code and the model must be corresponding to the facility with GPU.
