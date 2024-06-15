# AI Attendance System Using Facial Recognition

<div style="display: flex; justify-content: flex-end;">
    <img src="https://miro.medium.com/v2/resize:fit:1400/1*DKSQVZdEa2GEv2ksxWViTg.gif" width="400" />
</div>

> **Note**: Create a folder named "ImageList" and add decent and clean images of the candidates.

This project implements an AI-based attendance system leveraging facial recognition technology. It captures images from a directory, processes them to extract facial features, and uses these features to recognize faces in real-time video feed from a webcam. When a face is recognized, the system marks the attendance by recording the name and current time in a CSV file.

#### Key Features:
- **Image Processing**: Loads images from a specified directory and extracts facial encodings using the `face_recognition` library.
- **Real-time Face Recognition**: Captures video from the webcam, processes each frame to detect and recognize faces, and displays the recognized names on the screen.
- **Attendance Marking**: Records the attendance of recognized individuals by logging their names and the current time in a CSV file.
- **Error Handling**: Ensures robustness by handling cases where no face is detected in an image, preventing runtime errors.

This project combines computer vision, machine learning, and real-time data processing to automate the attendance tracking process, making it efficient and user-friendly.



