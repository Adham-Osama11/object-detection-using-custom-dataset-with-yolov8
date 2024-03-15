# object-detection-using-custom-dataset-with-yolov8
This project is about categorizing items using AI
To approach the output required i used yolo-v8 model to train it on a custom dataset and detect objects, 
and i used roboflow to create my dataset.
I started by creating my dataset by taking screenshots of product on the app that i am training this model for,
then i uploaded these screenshots to roboflow and entered the classes of the objects that will be detected,
then i started labeling the objects in the screenshots by their ocrrect classes.
i splitted the screenshots into a combination of 70% trainingset , 20% validation set, 10% testing set.
the training set is used to train the model with, the validation is used to validate that the training went correctly, and
the testing set is confirm that it is actually working.
After finishing the dataset i used the link of it from roboflow to link it in yolo then i began training the model and validating it then testing,
all the results are provided in the colab notebook.
In the the results you will see how it detected the objects but you will see that the results are not quite accurate because our dataset was not big enough 
if we provided it with more data to be trained with it will be much better.
