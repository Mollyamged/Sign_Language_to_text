# Sign_Language_to_text
Recognize American Sign Language (ASL) gestures in real-time and converting them  to text.
## 1. Install Required Libraries:
Install the necessary libraries using pip
pip install -q mediapipe
pip install tensorflow
## 2. Import Libraries:
-Copy and paste the provided code into a Jupyter Notebook.<br/>
-Make sure to import all required libraries including cv2, numpy, os, matplotlib, time, mediapipe, sklearn, keras, scipy, tensorflow.keras, and others.
## 3. Data Collection (Optional):
-If you want to collect your own gesture data, you need to create a directory structure for storing the data. You can do this manually or let the code create the directories for you.<br/>
-Make sure you have a webcam connected to your computer.<br/>
-When you run the data collection code, the webcam will activate but you would not be able to close it  until all the data is collected.<br/>
-The number of images collected depends on the number of categories (words) defined in your code. In this code, there are 9 categories (words). Therefore, the data collection process will continue until it finishes collecting 30 images for each word, resulting in a total of 270 images.<br/>
-Once the data collection process is complete, the camera feed window will close automatically, and the collected data will be saved in the specified directory structure for further processing and training of the gesture recognition model.<br/>
## 4. Train the Model (Optional):
You don't need to train the model it is already trained you can use it immediately
-Run the code related to data collection and preprocessing to gather training data and split it into sequences.<br/>
-Train the gesture recognition model by running the model training code.
## 5. Real-time Gesture Recognition:
-Once the model is trained, you can run the gesture recognition code. This will activate your webcam and start real-time gesture recognition.<br/>
-Gestures will be recognized and displayed on the screen based on the model's predictions.
## 6. Evaluation (Optional):
-If you want to evaluate the performance of the trained model, you can run the evaluation code. This will provide you with metrics such as loss and accuracy on a test dataset.<br/>
-If the accuracy is not satisfactory, you can modify the model, such as changing the layers or the activation function, or in the training code, in terms of changing the number of epochs, for example.
## 7. Exiting the Program:
Press 'q' on your keyboard to exit the real-time gesture recognition window. Note: make sure the q is small not capital<br/>
Once you're done, close the Jupyter Notebook.<br/>
<br/>
By following these steps, you should be able to run the code successfully and perform real-time gesture recognition using your webcam. If you encounter any errors or need further assistance, feel free to ask for help!
