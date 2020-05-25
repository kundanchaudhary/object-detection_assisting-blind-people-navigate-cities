# Assisting Blind People Navigate Cities via Object Detection

## Description:
Walking without sight brings the risk of falls and collisions. Such accidents often require medical condition and can change the walking habits of blind people and reduce their confidence as independent travelers. The city area looks like quite a dangerous place for blind people. How do we reduce the risk of such accidents? One of the ways we can assist blind people is by providing them with description of the objects in their field of view.

## Objective:
My goal for this project is to develop an object detection model which would provide a detailed descriptions of objects in the field of view to assist blind people navigate around cities.

## Methodology:
The general approach involved in this project is image preprocessing and image feature extraction using pre-trained models.

Here, I built an object detection model with 5 classes (person, pole, tree, traffic light, and car). For this, I took pictures and videos of my neighborhood in San Jose and labeled each objects in the image using LabelImg. Trained the model and tested the object detection model to find out if it can detect the objects we have it trained on.

## Results/Conclusions:
I was able to demonstrate the performance of my custom-made object recognition model. It can detect the objects it was trained on very well with a mAP (mean average precision) score of 0.39 for 0.5IOU. With larger dataset, the score can be further increased to result in a robust model. Additionally, object recognition model can be embedded with voice to convert the text descriptors (such as objects in the field of view including their sizes and positions) to assist the blind people navigate cities.

## References:

[1] https://towardsdatascience.com/training-tensorflow-object-detection-api-with-custom-dataset-for-working-in-javascript-and-vue-js-6634e0f33e03

[2] https://towardsdatascience.com/creating-your-own-object-detector-ad69dda69c85

[3] https://github.com/rafaelpadilla/Object-Detection-Metrics

[4] https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/
