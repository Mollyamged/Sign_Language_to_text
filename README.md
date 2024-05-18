# AI-coach
Knowing the correct and incorrect exercise position for the side plank exercise.
## 1. Install Required Libraries:
Install the necessary libraries using pip <br/>
pip install -q mediapipe <br/>
pip install tensorflow
## 2. Import Libraries:
-Open the code into a Jupyter Notebook.<br/>
-Make sure to import all required libraries including cv2, numpy, os, matplotlib, mediapipe, sklearn, keras, seaborn, tensorflow.keras, and others.
## 3. Data Collection:
-The project aleardy has its own data in one folder named "Data" contain two folders named "1" and "0" , one for the correct images (1) and two for the incorrect images (0) <br/>
### Optionally:
-You can add more images if you want by take pictures of you doing the execrsice or just get it by download it from any resource  and add them to the right folder <br/>
-Make sure you add the correct execrsice technique images in folder 1 and the incorrect in folder 0 <br/>
## 4. Train the Model (Optional):
You don't need to train the model it is already trained you can use it immediately<br/>
### Optionally:
-If you want to train it Run the code in the file named "AICoachModel" to gather training data and preprocess it and split it into sequences.<br/>
-Train the AI coach model by running the model training code.
## 5. Real-time pose detection:
-Once the model is trained, you can run the execution code. This will activate your webcam and start real-time pose detection for side plank execrsice.<br/>
-Poses will be recognized and the screen will display "correct" colored green for the right technique and "incorrect" colored red for the wrong technique.
## 6. Evaluation (Optional):
-If you want to evaluate the performance of the trained model, you can run the evaluation code. This will provide you with metrics such as loss , accuracy , confusion_matrix , loss curves , accuracy curves , confusion_matrix and classification report<br/>
-If the accuracy is not satisfactory, you can modify the model, such as changing the layers or the activation function, or in the training code, in terms of changing the number of epochs, for example.
## 7. Exiting the Program:
Press 'q' on your keyboard to exit the real-time pose detection window. Note: make sure the q is small not capital<br/>
Once you're done, close the Jupyter Notebook.<br/>
<br/>
By following these steps, you should be able to run the code successfully and perform real-time pose detection for side plank execrsice using your webcam. If you encounter any errors or need further assistance, feel free to ask for help!
