# Online-Authentication-for-Voting-Using-CNN
A secure deep learning–based web application designed to authenticate voters before election day using Convolutional Neural Networks (CNN). The system reduces long queues at polling stations by verifying voter identity in advance and notifying them with voting details. 

📌 Project Overview

This project integrates Deep Learning (CNN) with a Django web application to perform voter authentication prior to voting day.

Instead of verifying identity at the polling booth (which causes delays and long queues), this system:

Authenticates voters online beforehand
Confirms their identity using facial recognition
Sends them voting details (location & time)
Streamlines the actual voting process
🚀 Key Features
🔐 Secure Voter Authentication using CNN-based facial recognition
🌐 Django Web Application for backend management
📱 Responsive Web Design for accessibility across devices
📩 Automated Notifications (location & voting time)
⏳ Queue Reduction System at polling stations
🧠 Deep Learning Model Integration for identity verification
⚙️ Tech Stack
Frontend: HTML, CSS, JavaScript (Responsive Design)
Backend: Django (Python)
Machine Learning: Convolutional Neural Networks (CNN)
Database: SQLite / PostgreSQL
Libraries: TensorFlow / Keras / OpenCV
🧠 How It Works
Step 1: Registration
Voter registers on the platform
Uploads facial images for training/verification
Step 2: Model Processing
CNN model processes and learns facial features
Stores encoded representations securely
Step 3: Authentication (Before Voting Day)
User logs in and verifies identity via face recognition
CNN compares real-time input with stored data
Step 4: Verification Success
If matched, voter is authenticated successfully
Step 5: Notification System
Voter receives:
📍 Polling location
🕒 Assigned voting time
Step 6: Voting Day
Already authenticated voters go directly to polling station
Reduced waiting time and smoother flow
🎯 Objective

The main goal of this project is to:

Reduce overcrowding and long queues at polling booths
Improve efficiency of the voting process
Enhance security using AI-based authentication
Provide a seamless and user-friendly voter experience

