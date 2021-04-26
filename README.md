# EORA TestTask- eye blink detection

## Description
You need to implement a system that detects eye blink of a person in real-time mode. There is a useful guide that you can follow, describing how to implement eye blink detection from a given image. Your task is to continue the work applying the algorithm to detect eye blink of a certain duration. Also, be ready to answer questions about all the underlying mathematics.  

## Requirements
The source of video could be a file or a stream from a web camera.
On a video in the upper-left corner should be a caption that contains a number of blinks at the current time.
If eyes are closed for more than two seconds, a caption “Alert!” must appear on the video. The colour of the caption should be red.
You can use OpenCV, Dlib and whatever you find useful
Minimum resolution of a video: 480p.
There should be one person on a video. Height of a person’s face should be at least 1/3 of the height of the video in terms of pixels.  

## How to run
1. clone repository
2. open the ```.ipynb``` notebook in google colab or any other jupyter environment
3. make sure the files
> blink_detection2.mp4
> shape_predictor_68_face_landmarks.dat

are in the same working directory
4. run the notebook
5. download and play the file output.mp4
