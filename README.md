# Real-time Driver Drowsiness Detection

This is a Python application that uses neural networks and computer vision to detect whether a driver is drowsy or not. The application utilizes non-intrusive methods to accurately determine driver state in real-time and generate effective and acceptable warnings to increase driver alertness and safety.

## Prerequisites

To run this application, you need to have the following installed:

* Python
* Tensorflow
* NumPy
* matplotlib
* face_recognition
* PyObjC
* playsound

You can install NumPy, matplotlib, face_recognition, PyObjC, and playsound using pip:
```
pip install numpy matplotlib face_recognition PyObjC playsound

```
To install TensorFlow, you can follow the installation instructions on the TensorFlow website: https://www.tensorflow.org/install

## Usage 

To use the real-time drowsy detection webcam application:
1. Start the Jupyter Notebook server by executing the following command in a terminal:
    ```
    jupyter notebook
    ```
2. Once the Jupyter Notebook interface is open, navigate to `drowsy_detection_application.ipynb` and open it. 
3. Run all the cells in the notebook.
 
## Model Training
### Eye Aspect Ratio Classification
To classify eye state based on Eye Aspect Ratio (EAR):
1. Start the Jupyter Notebook server by executing the following command in a terminal:
    ```
    jupyter notebook
    ```
2. Once the Jupyter Notebook interface is open, navigate to `eye_aspect_ratio.ipynb` and open it. 
3. Run all the cells in the notebook.

### Convolutional Neural Network (CNN) Model
To run the CNN model:
1. Start the Jupyter Notebook server by executing the following command in a terminal:
    ```
    jupyter notebook
    ```
2. Once the Jupyter Notebook interface is open, navigate to `cnn_model.ipynb` and open it. 
3. Run all the cells in the notebook.

### Transfer Learning Model
You can either run a saved model or train a new model.<br><br>
Running a saved model
1. Run `transfer_learning.py`.
2. Type `1` at the prompt to run the saved model.

Training a new model

1. Run `transfer_learning.py`.
2. Type `2` at the prompt to train a new model.
 
 ## Authors
This application was created by Evangeli Silva [esilva2@albany.edu](esilva2@albany.edu), Andrew Okoro [aaokoro@albany.edu](aaokoro@albany.edu), Jahnavi Bonagiri [jbonagiri@albany.edu](jbonagiri@albany.edu) and Tobin Cherian [tcherian@albany.edu](tcherian@albany.edu) as part of the ICSI 531 course at the University at Albany.
