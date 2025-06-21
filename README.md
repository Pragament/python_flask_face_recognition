![Screenshot (76)](https://github.com/user-attachments/assets/816ce16d-8bed-40b7-8b90-6cb19d8f69df)# python_flask_face_recognition
# python_flask_face_recognition

Flask web app
INPUTS:
    An MP4 video or link 
    One or more face images of a specific person (front, left, and right profiles)
OBJECTIVE:
    From the uploaded video, detect and extract all video frames where the given person appears, using face recognition (TensorFlow model), and display:
        1.The frame(s) where the person appears
        2.The timestamp of each frame

STEP-BY-STEP:
     Video Preprocessing---->Face Model Integration---->Frame-by-Frame Face Detection----> Flask Integration


# Face Matching Web App (TensorFlow-based)

This is a Flask-based web application for face detection and matching in video files using TensorFlow (FaceNet + MTCNN).  
Users can either upload a `.mp4` video or provide a YouTube link.  
The app extracts frames where any uploaded face matches appear.



## Screenshots

### Upload Interface

![Screenshot (76)](https://github.com/user-attachments/assets/9f621b76-072b-40b5-beb9-445cc5fe24e7)

### Detection Results
![Screenshot (75)](https://github.com/user-attachments/assets/98ec38c0-11f1-4da6-a8cb-f5bae051cfef)


## ⚙️ Tech Stack

- **Backend:** Flask (Python)
- **Face Detection:** MTCNN (TensorFlow-based)
- **Face Embedding:** Keras-FaceNet (TensorFlow backend)
- **Frontend:** Tailwind CSS

---

## 🧪 Features

- Upload MP4 or paste YouTube link
- Upload multiple reference face images
- Frame skipping and drop-initial frame options
- Automatic face detection, embedding comparison
- View matched frames with timestamps



## 🚀 Getting Started

- Clone Repository
- pip install -r requirements.txt
- pip install opencv-contrib-python
- pip install yt-dlp
- python app.py




   
