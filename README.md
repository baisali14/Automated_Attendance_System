# Automated Attendance System using Face Recognition
This project is an attendance system that uses face recognition to record attendance. It utilizes the OpenCV and face_recognition libraries to detect faces in webcam footage and compares them to a pre-existing set of known faces. If a match is found, the script will display the name of the matched person on the webcam footage and also stores the attendance in "Attendance.xlsx" file.

## Working Video
<a href="https://player.vimeo.com/video/830162805" target="_blank">
  <img src="/workingvideoss.png" alt="Video Screenshot" width="400px" height="225px">
  <div class="play-button"></div>
</a>



## Prerequisites
* Python 3
* OpenCV
* Face_recognition
* openpyxl
* PIL
* numpy

## How to use
1. Clone the repository
2. git clone https://github.com/yourusername/attendance-system-face-recognition
3. Install the required libraries
* pip install opencv-python
* pip install face_recognition
* pip install openpyxl
* pip install pillow
* pip install numpy
4. Add the images of the students in the "ImagesAttendance" folder.
5. Run the script
* python face_recognition_attendance.py
6. The script will start capturing images from the webcam and compares the faces in the webcam footage with the images in the "ImagesAttendance" folder. If a match is found, it will display the name of the matched person on the webcam footage and also mark attendance in "Attendance.xlsx" file
7. Press 'q' to exit the script

## Limitations
* The script currently only works with one webcam at a time
* The script only recognizes faces that are in the "ImagesAttendance" folder
* The script only records attendance once per person per run

## Future work
* Add the ability to work with multiple webcams at a time
* Add the ability to add new faces to the "ImagesAttendance" folder during runtime
* Add the ability to record attendance multiple times per person per run
* Make the script more efficient by using more advanced techniques such as deep learning

## Contributing
* If you want to contribute to this project, feel free to create a pull request. Any contributions, big or small, are welcome.

## Authors
* [Ranodeep Banerjee](https://github.com/ranodeepbanerjee)
* [Baisali Roy](https://github.com/baisali14)
* [Swagata Das](https://github.com/SwagataDas123)
* [Ankit Pal](https://github.com/AnkitPl778)

## Acknowledgments
* Phillip Wang for creating the face_recognition library.
