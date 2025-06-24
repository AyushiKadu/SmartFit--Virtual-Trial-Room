# 🧥 SmartFit – Virtual Trial Room

SmartFit is a computer vision–based virtual try-on web application built using **Python**, **OpenCV**, and **Flask**. It enables users to visualize clothing on themselves in real-time using a webcam. The app features gender-based and size-based filtering for a personalized try-on experience, simulating how selected clothes would look without needing to physically try them on.

## 🚀 Features

- Real-time virtual try-on via webcam
- Face and body detection using OpenCV and dlib for clothing overlay alignment
- Gender and size filtering of clothing items
- Flask-based web interface for smooth interaction
- Responsive design and user-friendly UI

## 🛠️ Tech Stack

- **Language**: Python 3.6  
- **Web Framework**: Flask, Flask-SocketIO  
- **Computer Vision**: OpenCV (`opencv-contrib-python==3.4.5.20`), dlib  
- **Other Libraries**: pandas, pillow, pyglet, seaborn, imutils, pyotp  
- **Database (optional)**: MySQL client

## 🧪 Installation & Setup

Follow the steps below to set up the project environment using `conda` and `pip`.

```bash
# Step 1: Create a Conda environment with Python 3.6
conda create -n tf python=3.6

# Step 2: Activate the environment
conda activate tf

# Step 3: Install all required dependencies
pip install pillow
pip install pandas
pip install seaborn
pip install opencv-contrib-python==3.4.5.20
conda install -c conda-forge dlib
pip install --only-binary :all: mysqlclient
pip install pyotp
pip install pyglet
pip install flask
pip install flask-socketio
pip install imutils
