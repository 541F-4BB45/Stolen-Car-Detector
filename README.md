# Stolen Car Detector
A stolen car detector that takes as input a CSV file containing stolen license plates aswell as a video. It then outputs a CSV file containing the license plates detected in the video that were also present in the input CSV containing the license plate numbers of the cars 
that were stolen. It also outputs a the video containing bounding boxes for the cars and license plates that is detected in the video.

## Features
- Supports CSV files which are universally used.
- contains database integration with the MySQL database allowing for conversion between files and tables.
- Uses the MOT tracker repository to allow tracking of cars.

## Interfaces
