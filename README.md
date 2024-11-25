# Smart Class Attendance System  

## Overview  
The Smart Class Attendance System automates the attendance process by utilizing modern technologies such as OpenCV and facial recognition. This system captures real-time images or videos, processes them using advanced algorithms, and marks attendance automatically based on student identification.  

## Features  
- **Real-Time Face Detection and Recognition**: Uses OpenCV to detect and recognize students' faces during class.  
- **Interactive User Interface**: Built with Tkinter for an easy-to-use interface for students and administrators.  
- **Automated Attendance Marking**: Automatically records attendance when a student's face is recognized in real-time.  
- **Database Integration**: Utilizes an SQL database to store student data, attendance history, and facial images for efficient record management.  

## Technologies Used  
1. **OpenCV**: For real-time face detection and recognition.  
2. **Tkinter**: For creating the graphical user interface (GUI).  
3. **SQL Database**: To store and manage student data and attendance records.  

## How It Works  
1. **Face Detection**:  
   - A webcam captures real-time video or images of the classroom.  
   - OpenCV detects student faces in the frame.  
2. **Face Recognition**:  
   - The system matches detected faces with stored facial images in the database.  
3. **Attendance Marking**:  
   - Upon successful recognition, the student's attendance is automatically recorded in the database.  
4. **Database Management**:  
   - An SQL database maintains records of students, their facial data, and attendance logs.  
5. **Interactive UI**:  
   - Administrators and students can interact with the system through a Tkinter-based GUI.  

## Prerequisites  
- Python 3.x  
- OpenCV library  
- Tkinter (comes pre-installed with Python)  
- SQL database (e.g., MySQL, SQLite)  
- A functional webcam for real-time processing  

## Installation  
1. Clone this repository:  
   ```bash  
   git clone [repository URL]  
