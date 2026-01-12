#  AI-Based Emotion Music Recommendation System

An AI-powered music recommendation system that detects **human emotions from facial expressions** using a camera and plays **emotion-based music** from the **GTZAN dataset**.

This project is developed and executed entirely using **Google Colab**, integrating **Computer Vision**, **Deep Learning**, and **Music Recommendation** techniques.

---

##  Project Overview

The system captures a user’s facial image through camera access, detects the emotion using **DeepFace**, and recommends music that matches the detected mood.

This creates an intelligent, interactive, and personalized music experience.

---

##  Technologies Used

- **Python**
- **DeepFace** – Facial Emotion Detection
- **OpenCV** – Camera Access & Image Capture
- **Librosa** – Audio Feature Processing
- **GTZAN Music Dataset**
- **Google Colab**
- **Google Drive**

---

## 📸 How the System Works

1. User grants **camera access**
2. Facial image is captured using **OpenCV**
3. Emotion is detected using **DeepFace**
4. Detected emotion is mapped to a music genre
5. A song is selected from the **GTZAN dataset**
6. Music is played according to the detected mood

---

##  Emotion to Music Mapping (Example)

| Detected Emotion | Recommended Genre |
|------------------|------------------|
| Happy            | Pop / Disco      |
| Sad              | Blues / Classical|
| Angry            | Rock / Metal     |
| Neutral          | Jazz             |
| Surprise         | Electronic       |

---


---

##  Dataset Information

- **GTZAN Music Genre Dataset**
- Dataset is **not included** in this repository
- Stored and accessed via **Google Drive**
- Google Drive is mounted inside Google Colab

This method is used to handle large dataset sizes efficiently.

---

##  How to Run This Project (Google Colab)

 **Important:**  
This project was developed and tested using **Google Colab**.  
It is **recommended to run this project only on Google Colab** for proper functionality.

### Steps to Run

1. Open **Google Colab**  
   https://colab.research.google.com/

2. Upload the original `.ipynb` file 
3. Download datset from  link :  https://www.kaggle.com/datasets/carlthome/gtzan-genre-collection
4. upload on google drive
5. run the project



Why Google Colab?

No local setup required

Easy browser-based camera access

Seamless Google Drive integration

Free CPU/GPU support

Ideal for AI & ML projects

Key Features

✔ Real-time facial emotion detection
✔ Camera-based user interaction
✔ Emotion-based music recommendation
✔ Deep learning powered emotion analysis
✔ Scalable and extendable architecture

Future Enhancements

Web application using Streamlit / Flask

Spotify / YouTube Music API integration

Multi-user emotion detection

Personalized music history

Mobile application support

⚠️ Disclaimer

This project is created only for educational and research purposes.
The GTZAN dataset is used strictly for learning and experimentation.


Ashwin Daniel 

AI Developer | Machine Learning | Python

Feel free to explore the project and connect for collaboration!


---



