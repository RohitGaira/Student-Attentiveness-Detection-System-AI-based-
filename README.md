Student Attentiveness Detection System (AI-based)

Description:
This project focuses on analyzing student attentiveness in a classroom using computer vision and deep learning techniques. The system leverages real-time webcam input to assess whether a student is attentive based on head orientation, eye movement, and lip activity.

Key Features:

All the models are self trained using CNN.

Head Movement Detection: Uses MediaPipe and custom-trained CNN to determine if the student's head is facing forward or turned.

Lip Movement Detection: Identifies if the student is speaking or silent using a model trained on lip images.

Eye State Detection: Detects if eyes are open or closed to monitor drowsiness or distraction.

Attentiveness Scoring: Combines all three indicators to compute a real-time attentiveness score.

Database Logging: Stores timestamped attentiveness data using SQLite for later analysis and reporting.


Technologies Used: Python, OpenCV, Keras, TensorFlow, MediaPipe, SQLite
Impact: Enables educators or automated systems to monitor classroom engagement and identify students needing support.

