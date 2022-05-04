# Anti-skeep-alarm-system-for-driving

Files:
you will see python file, wav file , txt file and .dat file

Antisleep_alarm.py :
If you run this file, facial detection for video streaming apps will begin.

Alarm.wav :
Alarm sounds are contained in this.wav file. It is one of the arguments that is passed.

shape_predictor_68_face_landmarks.dat :
This file contains 68-(x,y) coordinates that map to the facial structures of the face. It is another argument that is passed.

command to run in cmd.txt :
This text file contains the command to run in command prompt.


Here are some of the libraies you need to import :

from imutils.video import VideoStream
from imutils import face_utils
from scipy.spatial import distance as dist
from threading import Thread
import imutils
import time
import dlib
import cv2
import numpy as np
import playsound
import argparse

Procedure:
First we have to import all the above files then we have to check for any errors in importing the modules.
Second we have to run the command in the .txt file mentioned above in the command prompt.
then the video stream thread starts and the front camera opens.
the system checks the person eyes and determines whether the person is drowsy or not.


Conclusion:
This project plays a key role in reducing the catastrophic accidents caused by the truck drivers due to their drowsiness by warning with the help of an alarm.
We can implement this idea in cars and trucks  by which we can reduce the road accidents.

