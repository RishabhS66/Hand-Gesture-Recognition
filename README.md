# Hand Gesture Recognition using Deep Neural Networks

```
Coded By: Rishabh Srivastava & Chandan Agrawal
```
## Introduction:

Hand gesture recognition has great value in many applications such as augmented reality (virtual reality), sign language interpreters for the disabled, and robot control. Hand gestures can also be used as a tool of communication between computer and human.

The main aim of the project is to recognize and classify hand gestures to their correct meaning with the maximum accuracy possible. For attaining the above-mentioned objective, a deep neural network model has been implemented. The small-scale model built for the project can be considered as a precursor for larger models with more hand gesture classes that can be used for sign language recognition.

## Methodology:

A data set of 78 images representing different hand gestures has been used for training and testing the neural network model. The images fall into one of the 4 classes of hand gestures – <b>left</b>, <b>right</b>, <b>palm</b>, and <b>peace</b> sign. The images are passed as input to the neural model along with their associated labels.

The neural network model is composed of 4 convolutional layers. Convolutional layers are not fully connected, and thus are relatively cheaper in terms of memory and computer power needed. 

Activation function used for all layers is the Rectified Linear Unit (ReLU).
<br>
<div align = "center">
  <kbd>
    <img src = "https://user-images.githubusercontent.com/39689610/117568758-e3254c00-b0df-11eb-98c1-5bb258a5edcc.png" width="600" height="400">
  </kbd>
</div>
<br>

## Results:

After training, the accuracy obtained for testing data set was **76.47 %**, and the maximum training accuracy was observed to be **100 %**.
<br>
<div align = "center">
  <kbd>
    <img src = "https://user-images.githubusercontent.com/39689610/117569638-3dc0a700-b0e4-11eb-912e-84dc8c5bd079.png" width="500" height="300">
  </kbd>
</div>
<br>

The plots for **loss** and **accuracy** as training proceeded is shown in the next figure.
<br>
<div align = "center">
  <kbd>
    <img src = "https://user-images.githubusercontent.com/39689610/117569664-5b8e0c00-b0e4-11eb-841d-4bcf0ddf43cd.png" width="550" height="300">
  </kbd>
</div>
<br>

The following figure shows images of hand gestures with their true labels, and the predicted labels by the neural network model after training.
<br>
<div align = "center">
  <kbd>
    <img src = "https://user-images.githubusercontent.com/39689610/117569741-cb9c9200-b0e4-11eb-9dad-8ea5600afb25.png" >
  </kbd>
</div>
<br>

## Notes:

1. Upload the file _HandGestureRecognition.ipynb_ in Google Colab to avoid version incompatibility problems. After uploading, just run the notebook.
2. You can also view my notebook at the link https://colab.research.google.com/drive/1BgMfFjjCFkYJ1GSB4RPwCZyaKV_nerFd?usp=sharing
3. Link to data set: https://github.com/chan4899/Gesture-Recognition.git


