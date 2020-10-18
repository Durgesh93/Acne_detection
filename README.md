# Acne severity prediction using opencv


The directory structure for the project is as follows

.
├── acne_detection_opencv.ipynb
|
├── data
│   ├── acne_mild.jpg
|   |
│   ├── acne_severe.jpg
│   └── acne_zero.jpg
├── models
│   └── shape_predictor_81_face_landmarks.dat
└── README.md



```acne_detection_opencv`.ipynb``` is main jupyter notebook which contains the code.
```data``` folder contains images to be processed.
```models``` folder contains model data for face_landmarks
```README.md``` contains instruction to run the code.

requirements
The code requires python 3.6 to run

1. opencv
2. dlib
3. numpy

The code is inspired from [pimple detection code](https://answers.opencv.org/question/72176/detect-red-pimples-on-face-using-opencv/)
