# Gender-Age-Detection
![Uploading Screenshot 2024-06-29 124555.png…]()
![Screenshot 2024-06-29 124400](https://github.com/mandligeetha5/Gender-Age-Detection/assets/136496392/41848f0b-253a-4704-92a1-920fd6fcc65d)
# Objective:
To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture or through webcam.
# About the project
This project is a Python-based implementation of a model that can predict the age and gender of a person from an image or video. The model uses pre-trained deep learning models to detect and classify faces and predict age and gender.
The project contains below mentioned files:
#age_and_gender_Detection.ipynb: This file contains the code for the age and gender detection model. It uses OpenCV for face detection and pre-trained models for age and gender classification. The script can accept both image and video inputs and produces outputs with age and gender predictions.
#people.jpg: This file is a sample input file to test the model on image inputs
#people.mp4: This file is a sample input file to test the model on video inputs
->Model files
# Datasets
You can download the below mentioned files via this link -https://drive.google.com/uc?id=1T8Srjo1g82qrRC6A0IxhmZsm8kcWiEhq&export=download
#gender_net.caffemodel: Pre-trained model weights for gender detection.
#gender_deploy.prototxt: Model architecture for the gender detection model.
#age_net.caffemodel:Pre-trained model weights for age detection.
#age_deploy.prototxt:Model architecture for the age detection model.
#opencv_face_detector_uint8.pb: Pre-trained model weights for face detection.
#opencv_face_detector.pbtxt: Model architecture for the face detection model.
# Additional Python Libraries Required :
OpenCV
   pip install opencv-python
argparse
   pip install argparse
# Usage:
![Screenshot 2024-06-29 131759](https://github.com/mandligeetha5/Gender-Age-Detection/assets/136496392/63997bce-7e9e-4211-bc1c-767039582d0a)


