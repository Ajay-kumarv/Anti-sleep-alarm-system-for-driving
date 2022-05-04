# Anti-skeep-alarm-system-for-driving

Files:
you will see python file, wav file , txt file and .dat file

Antisleep_alarm.py :
If you run this file, facial detection for video streaming apps will begin.

Alarm.wav
Alarm sounds are contained in this.wav file. It is one of the arguments that is passed.






here are some of the libraies you need to import :

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
