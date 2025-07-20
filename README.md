# SignVRse – A VR Sign Language Learning App
Senior Year Project 
Empowering Communication Beyond Barriers

SignVRse is an immersive, multi-platform learning system designed to teach American Sign Language (ASL) using cutting-edge technologies like Virtual Reality, Computer Vision, and Mobile Applications. This project aims to break communication barriers and promote inclusive education by making ASL accessible, engaging, and interactive for all learners.

The system is composed of three key components:

Mobile App
Built with Kotlin, the Android application allows users to create accounts or access guest sessions.
Users can monitor their learning progress across categories (Alphabets, Numbers, Words, Phrases).
The app also provides access to offline ASL learning content and external educational resources.

VR Environment (Unity)
Developed in Unity, the VR component allows users to immerse themselves in a virtual world where they can practice ASL with guidance and feedback.
Learners can sign in, explore categorized VR lessons, and track their performance.
Real-time visual feedback is displayed based on their hand movements.

Gesture Feedback System (Python)
A Python-based module using OpenCV and MediaPipe detects and analyzes users' hand gestures.
The system scores their signs based on accuracy and provides immediate feedback in the VR space.
The feedback is also stored and reflected in the mobile app.

Together, these components deliver an end-to-end ASL learning solution that is intuitive, real-time, and user-centered. Whether you're a beginner or someone seeking to improve, SignVRse offers a powerful new way to connect through sign language.

## Project Overview

**Components:**
1. **Mobile App (Kotlin)**  
   - User registration and login  
   - Track lesson progress (Alphabets, Numbers, Words, Phrases)  
   - Access educational resources (YouTube videos, articles)  
   - Offline mode for saved content  

2. **VR App (Unity)**  
   - Immersive sign language lessons  
   - Real-life scenarios with hand gesture training  
   - Interactive VR progress panel  
   - Feedback mechanism using gesture recognition  

3. **Computer Vision & Feedback System (Python)**  
   - Real-time gesture recognition using OpenCV & MediaPipe  
   - Accuracy scoring for each sign  
   - Feedback integrated into VR and stored in the app database  

## 🧠 Technologies Used

- **Mobile**: Kotlin, Android Studio, Firebase Firestore  
- **VR**: Unity, C#, Firebase SDK  
- **Computer Vision**: Python, OpenCV, MediaPipe  
- **Database**: Firebase Firestore  
- **Tools**: Git, GitHub, Agile Scrum, Jira  

## Features

- Sign-in / Guest Mode for users  
- Real-time accuracy score feedback inside VR  
- Firebase-based user-specific progress tracking  
- Offline support for mobile learning  
- Dynamic VR lesson progress tracking with UI panels  

##  Folder Structure

```bash
SignVRse/
├── Android Studios - Mobile App/            # Kotlin-based mobile app
├── SignVRse-Unity Application/              # Unity-based VR learning environment
└── Sign Scoring System-python codes/        # Python-based gesture recognition system
└── README.md

