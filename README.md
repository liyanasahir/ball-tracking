# COLORED BALL TRACKING USING OPENCV
Python-OpenCV code for tracking multiple colored balls

## Working
The file trackballs.py tracks two colored balls(red and green) in the given HSV range and displays the traces on screen. 

#### Usage:
Run normally if reading from webcam:
`python trackballs.py`

Provide video name as argument when using an existing video: 
`python trackballs.py --video sample.mkv`

#### Limitations to work on:
 Tracks only the two colors within the defined range. 
 clearing excessive noise when using video source. 

