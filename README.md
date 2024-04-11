# HAND GESTURE DETECTION WITH MEDIAPIPE

In this project we uses pre-trained Mediapipe Hand Gesture Classification model. Hand Gesture Classification model uses hand landmarks produced by MediaPipe Hands Model to classify a hand pose as onr of the 10 hand gesture classes namely (okay,peace,thumbs up,thumbs down,call me,stop,rock,live long,fist,smile).

You can see the model_card.pdf for model architecture. 
I added code_explanation.txt for code explanation.


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/zihath/hand_gesture
    ```

2. Install dependencies:
    ```bash
    cd hand_gesture
    pip install -r requirements.txt
    ```

## Usage
Run the python file:
 ```bash
   python hand_gesture_detection.py
 ```
While running the python file , the live camera window will pop up and it will make prediction on live window . For example : 

![image](https://github.com/zihath/hand_gesture/assets/133570794/266908b4-3428-4c66-bd12-063f030a1d1e)


     
