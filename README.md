# Sign-Language-Recognizer
Sign Languages are a set of languages that use predefined actions and movements to convey a message. These languages are primarily developed to aid deaf and other verbally challenged people. They use a simultaneous and precise combination of movement of hands, orientation of hands, hand shapes etc.


In this project, we aim towards analyzing and recognizing various words from a database of sign images. Database consists of various images with each image clicked in different light condition with different hand orientation. With such a divergent data set, we are able to train our system to good levels and thus obtain good results.
# Getting Started
## Requirements


- [Python 3.11.8]([[docs/CONTRIBUTING.md](https://pypi.org/project/pip/)](https://www.python.org/downloads/release/python-3118/)) 
- following package
   - openCV
   - tensorflow
   - mediapipe
   - sklearn
   - matplotlib
 
  
## Running
If you want to run this project locally perform following steps 


1. Clone this repository
2. Create local folder in your device for cloned Repositry 
3. Open Visual Studio Code (VS Code).
4.  Select Start-> clone Git Repositry, put link and select the folder

## Installing Requirements
- Open a terminal within VS Code by selecting from Navigation Bar "Terminal" -> "New Terminal" from the menu.
- pip install -r requirements.txt


## How to deal with Code
- Be careful when you run code if you meet the variable that take the path of dataset you should put the local path of dataset which is downloaded with this repo.
- Collecting Keypoint Values for training and testing can take up to 45 minutes.
- Training model takes 20 minutes.


## WorkFlow
<img src="/Architecture.png" width="600" >

  






