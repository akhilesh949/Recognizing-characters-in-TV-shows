# Face-recognition-of-known-people-in-video-frames-or-webcam-feed

This is a facial recognition software based on OpenCV python library.

Such a software can be used in making face-unlock system, recognizing characters in streaming services etc.

The library makes use of dlib's state-of-the-art face recognition built with deep learning. The model has an accuracy of 99.38% on the Labeled Faces in the Wild benchmark.

## Dependencies
Python 3.0

face_recognition
```
 pip install face_recognition
```

OpenCV 
```
conda install -c menpo opencv
```
The code will work on any python IDE.

To take input frames from the primary webcam instead of a video stream, just pass 0 as the argument in 

input_movie = cv2.VideoCapture(0)

in place of 

input_movie = cv2.VideoCapture('video_file_name.mp4')
