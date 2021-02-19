# Real-Time-Attendance-System-Using-Face-Recognition

Attendance System with the applixation of Face Recognition Using face_recognition and make it real time using OpenCV

## Instruction :

1. Make sure you have installed all the libraries/packages in requirement.txt
1. First put all the images in 'img' folder with their person's(employees/students) name (for ex. rutvik.jpg, xyz.jpg)
2. Run main.py

## About Project: 

1. First of all, it will load all images placed in 'img' folder
2. Find respective face locations & encondings and put in respective array according label name (classname)
3. Using OpenCV by your webcam it will detect your/unknown face, face location & enconding
4. Compare your real time encoding with the ones placed in 'img' folder
5. If it will find maximum match with any image in 'img' folder, it will mark it label(person's)name and
6. Make Entry of that person with Name & Current Time
7. This project make sure not to make double entry, once attendance is done it'll not put entry in Excel sheet 2nd time

## Screenshots

* Directory Structure ...

![Input](snapshots/directory_structure.jpg?raw=true)

* CSV File ...

![Output](snapshots/attendance_csv.jpg?raw=true)
