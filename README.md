# Object-Detection-Model

This model takes video input in real time through which you can input hand images showing numbers from 0-5 and it outputs the result in real time.


To run the model we have two choices :
1. Use the model with the pretrained weights in the json and .h5 files.

  For this you need to download only the prediction,json and h5 files. Keep all of them in the same folder nad run the python file. Note that you should have all the 
  necessary python packages listed in the requirements.txt file on your system.
  
2. You can also download all the files except the json and h5 files and the run the train model file to retrain the model and then run the predictions file to check. 
   Note you can also add more data by running the collect data.
