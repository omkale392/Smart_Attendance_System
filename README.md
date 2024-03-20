# Real-Time Car Number Plate Detection

This repository is dedicated to a Python-based project that applies OpenCV techniques for the real-time detection of Russian car number plates via webcam feed. It includes functionality to save the detected number plates.

# Prerequisites

Before running this project, ensure that you have the following installed:
- Python 3.x
- OpenCV library

You can install OpenCV using pip:
```shell
pip install opencv-python

# Usage
To interact with the project, use the following commands:

Add a new face to the dataset, which will be recorded via webcam:
**python Add_faces.py**

Record the attendance of the added face by pressing 'o'. This will generate a CSV file with the present date, name, and timestamp: **python test.py**
To display attendance and download it in CSV format, use Streamlit: **streamlit run app.py**

#Technologies
Python - The core programming language
OpenCV - Library used for computer vision tasks

#License
This project is licensed under the MIT License - see the LICENSE file for details.

#Acknowledgments
Hat tip to anyone whose code was used as inspiration.
Special thanks to the OpenCV community for their extensive resources.
