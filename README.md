# Smart Attendance System using Facial Recognition

## Description
The **Smart Attendance System using Facial Recognition** solves the challenges faced by teachers in taking attendance and maintaining student attention during classes.  
This system is suitable for **schools, colleges, and offices**, allowing attendance to be recorded **20 minutes at the start** and **20 minutes at the end** of a session.  

It automatically logs attendance, tracks students' presence, and helps manage records efficiently.

## Technologies Used
- Python  
- OpenCV  
- Haarcascade  
- Tkinter  
- NumPy, Pandas, Pillow, and other supporting libraries  

## Installation

**1. Clone the repository:**

git clone https://github.com/Dhar-21-06/Smart-Attendance-System-using-facial-recognition.git

**2. Navigate to the project directory:**

cd Smart-Attendance-System-using-facial-recognition

**3. Install the dependencies:**

pip install tk-tools
pip install opencv-contrib-python
pip install datetime
pip install pytest-shutil
pip install python-csv
pip install numpy
pip install pillow
pip install pandas
pip install times


## Usage
**1. Run the main program:**

python main.py

**2. Register New User:**

-Enter the user ID and name.
-Capture around 100 pictures for the user profile.

**3.Take Attendance:**

-Select an existing user and click Take Attendance.
-A camera screen will appear, displaying the person with their identity.
-If the person is not in the database, it will show Unknown.

**4. Notify Absentees:**

-The system can notify absentees based on the attendance records in the database.

## Folder Structure

-TrainingImage/ – Stores images captured for user profiles
-TrainingImageLabel/ – Contains trained labels and data files
-StudentDetails/ – CSV file with student information
-Attendance/ – Attendance records
-main.py – Main program to run the system
-haarcascade_frontalface_default.xml – Pre-trained Haar cascade file for face detection

## Features

-Face detection and recognition using LBPH Face Recognizer
-Automatic attendance logging
-Capture multiple images for accurate recognition
-Unknown user detection
-Absentee notification

## Future Improvements
-Integration with email/SMS notifications
-Web-based dashboard for monitoring attendance
-Real-time analytics for student attendance patterns

## Author
**Dharshini S**
**Email: dharshiv2101@gmail.com**
**GitHub: https://github.com/Dhar-21-06**
