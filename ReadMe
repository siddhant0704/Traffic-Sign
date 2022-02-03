# Automatic Traffic Sign Detection

Automatic traffic sign detection and recognition is an important part of an Advanced Driver Assistance Systems (ADAS). 
Traffic symbols have several distinguishing features that are used for their detection and recognition. We were able to classify road signs on 43 differently labelled images. 
Our model was successfully able to classify the image based on their true description. We were able to detect blurry and dark road signs and classify them correctly. 
The performance of the system can be improved by increasing the number of divided regions.

Process:

In the real-world, traffic sign recognition is a two-stage process:
Localization: Detect and localize where in an input image/frame a traffic sign is.
Recognition: Take the localized ROI and actually recognize and classify the traffic sign.

Deep learning object detectors can perform localization and recognition in a single forward-pass of the network.

Challenges with the dataset :
There are a number of challenges in the dataset, the first being that images are low resolution, and worse, have poor contrast. These images are pixelated, and in some cases, 
it’s extremely challenging, if not impossible, for the human eye and brain to recognize the sign.

In order to successfully train an accurate traffic sign classifier we’ll need to devise an experiment that can preprocess our input images to improve contrast.

The shape of data is (39209,32,32,3) which means that there are 39,209 images of size 32×32 pixels and the last 3 means the data contains colored images (RGB value).

Dividing the Dataset :
      To classify the images into their respective categories, we will build a CNN model (Convolutional Neural Network). CNN is best for image classification purposes.
      
Model Training :
After building the model architecture, we then train the model using model.fit(). We tried with batch size 32 and 64. Our model performed better with 64 batch size. 
And after 15 epochs the accuracy was stable. We have used a total of 15 epochs to train our model and at the end of the training the model has a decent accuracy of over 90%.

Evaluating Model performance:
s the weights get updated the accuracy of the model increases. Simultaneously the error function decreases. To check the model parameters we run the trained model on the validation set and it is seen that the accuracy of the model is decent in the validation set. From the validation set we get the desired weight which can be used in the test set for prediction on a new set of data.

