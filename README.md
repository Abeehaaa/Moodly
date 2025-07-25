# Getting Started with Moodly – Emotion Detection App

Moodly is an AI-based emotion detection web app. It scans your facial expression using your webcam or uploaded photo and predicts your mood using a deep learning model. Based on your emotion, it suggests motivational quotes or mood-matching songs.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) for the frontend and uses a Flask backend with a pre-trained Mini-Xception model trained on the FER-2013 dataset.

---

## Available Scripts

In the **backend** directory, you can run:

### `python app.py`

This starts the Flask server on [http://localhost:5000](http://localhost:5000)  
Make sure to install all dependencies with:

```bash
pip install flask flask-cors numpy opencv-python tensorflow keras pillow
```

In the **frontend** project directory, you can run:

### `npm install`

Installs all the required dependencies.

### `npm start`

Runs the frontend app in development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.  
You may also see any lint errors in the console.

---
