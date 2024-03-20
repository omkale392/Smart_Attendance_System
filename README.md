# Real-time Facial Recognition Attendance System

This project implements a facial recognition-based attendance system using Python, OpenCV, and machine learning. It's designed to automate attendance recording in educational or corporate settings through real-time face detection and recognition.

## Features

- **Face Registration:** Captures facial images to build a personalized dataset for each individual.
- **Attendance Recording:** Automatically identifies individuals and logs their attendance with timestamps.
- **Interactive Attendance Dashboard:** Uses Streamlit to display and manage attendance records, with options to download the data.

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV
- Pandas
- scikit-learn
- Streamlit

### Installation

1. Clone the repository:

git clone https://github.com/yourusername/facial-recognition-attendance.git

2. Install the required Python packages: **pip install -r requirements.txt**

## Usage
1) Data Collection: Run Add_faces.py to register a new individual's face data: **python Add_faces.py**
2) Record Attendance: Launch test.py to start the attendance recording process: **python test.py**
3) View Attendance Records: Execute app.py to run the Streamlit application and manage attendance data: **streamlit run app.py**

### Built with
Python - Programming language used.
OpenCV - Open Source Computer Vision Library for image processing.
scikit-learn - Machine learning library for Python.
Streamlit - Open-source app framework for Machine Learning and Data Science projects.




