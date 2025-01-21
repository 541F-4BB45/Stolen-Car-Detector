# Stolen Car Detector
A stolen car detector that takes as input a CSV file containing stolen license plates aswell as a video. It then outputs a CSV file containing the license plates detected in the video that were also present in the input CSV containing the license plate numbers of the cars 
that were stolen. It also outputs a the video containing bounding boxes for the cars and license plates that is detected in the video.

## Features
- Supports CSV files which are universally used.
- contains database integration with the MySQL database allowing for conversion between files and tables.
- Uses the MOT tracker repository to allow tracking of cars.

## How to get it running
1. **Database**
- You must download and install MySQL and create a local instance of the database on your computer.
- In the util1.py and delete table records files there are global variables named: password (database password) and instance (database name).
- You must change these to your MySQL database name and password or else it wont work

2. **OpenCV**
- You must open the terminal
- write "pip list" and press enter
- check if you have opencv-python-headless installed
- if you do please use "pip uninstall opencv-python-headless"

## Interfaces
![Main Interface](/repo/C1.JPG)
![Output Video](/repo/C2.JPG)
