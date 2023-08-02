# Virtual Air Painting

This is an application that enables one to **vitually paint in the air** using their fingers. It is developed in python **on openCV, TfLite and Mediapipe**.
So go ahead and recreate your imaginations in the air!

[![Made with Python](https://img.shields.io/badge/Made%20with%20-Python-red?style=for-the-badge&logo=python)](http://www.python.org/)
[![Made with TfLite](https://img.shields.io/badge/Made%20with%20-Tf%20Lite-yellow?style=for-the-badge&logo=tensorflow)](http://www.tensorflow.org/)

## Project Source
Final Year project of Group : 6 of Bengal College of Engineering and Technology, Durgapur.

### Cloning
Use the link below to close this repository to your machine.
```bash
$ https://github.com/Abhay0809/Virtual-Painter
```
## Directory Contents
```bash
$ cd Virtual-Air-Painting/
$ tree
.
├── Assests
    ├── Sample_run.mp4
    └── iphone_Sample_run0.mp4 
├── Images
    ├── 1.png
    ├── 2.png
    ├── 3.png
    └── 4.png    
├── __pycache__
├── templates
    └── index.html
├── README.md
├── app.py
├── cam.py
├── painter.py
├── track_hands.py
└── requirements.txt


1 directory, 14 files
```

### Pre-requisites
These are the required dependencies needed to setup the environment
```
$ pip3 install -r requirements.txt
```
### Instructions
> 1. To run on local machine **without a Flask server**.
```bash
$ python run painter.py
```
> 2. To run as a local host on a **Flask server**.
>- Run the Flask app
```bash
$ python run app.py
```
>- On your phone's browser enter your machine's ip and port 5000. Say ip is 192.168.0.15.
```
192.168.0.15:5000
```

### Usage:
- Use your index finger to draw.
- To change color/ use eraser, use index and middle fingers to select it by hovering on it.
- Continue painting!

