### Project: Classify Kaggle Consumer Finance Complaints

### Highlights:

 - This is a **multi-class text classification (sentence classification)** problem.
 - The purpose of this project is to **classify social media posts into a number of different classes (labels)**. 
 - The model was built with **Convolutional Neural Network (CNN)** and **Word Embeddings** on **Tensorflow**.

### Data: [Kaggle Consumer Finance Complaints](https://www.kaggle.com/cfpb/us-consumer-finance-complaints)

### Train:

 - Command: python train.py training_data.file parameters.json
 - Example: ```python train.py ./data/repsolutions.csv.zip ./parameters.json```
 
 A directory will be created during training, and the best model will be saved in this directory. 

### Predict:

 Provide the model directory (created when running ```train.py```) and new data to ```predict.py```.
 - Command: python predict.py ./trained_model_directory/ new_data.file
 - Example: ```python predict.py ./trained_model_1503432509/ ./data/small_samples.json```

### Reference:
 - [Implement a cnn for text classification in tensorflow](http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/)
