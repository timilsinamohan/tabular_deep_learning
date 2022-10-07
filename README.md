# tabular_deep_learning
Transfer Learning in a tabular data via image conversion.

This notebook provides the procedure to convert the tabular data to images and then apply transfer learning to classify the images.

I have used Python: 3.7.13 version, Keras: 2.4.0 and tensorflow: 2.3.0
Following are the Python library dependencies:
1. Matplotlib (https://matplotlib.org/)
2. Tab2Img (https://pypi.org/project/tab2img/)
3. Keras (https://keras.io/)
4. Scikit Learn (https://scikit-learn.org/stable/)
5. Tensorflow (https://www.tensorflow.org/)

For the dataset, I have used the breast cancer data from the scikit library. The data is splitted as 75% training and 25% testing. The pretrained
model is used from the keras library.

The results are as follows:
**Baseline Logistic Regression Classifier approach:**
Accuracy:0.944, Precision:0.936, Recall:0.948, F1-score:0.942

T**ransfer Learning with Image Classification approach:**
Accuracy:0.902, Precision:0.895, Recall:0.895, F1-score:0.895

The transfer learning is so powerful, even the task is not related the accuracy of the model is quite high but not high as logistic regression. However, if
the task would have been related we could expect much higher evaluation metric. 

