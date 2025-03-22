# Face Recognition and QR Code-Based Attendance System

## Overview
This project is a face recognition-based attendance system designed for gym management. It utilizes OpenCV, TensorFlow, and MTCNN for facial recognition and integrates QR code-based authentication. The system ensures secure and efficient attendance tracking with cloud integration and live notifications.

## Features
- **Face Recognition**: Uses MTCNN for face detection and TensorFlow for feature extraction and classification.
- **QR Code Authentication**: Provides an additional layer of security.
- **Cloud Integration**: Stores attendance records securely using AWS/Azure.
- **Unauthorized Access Alerts**: Sends live notifications for unregistered individuals.
- **Cross-Platform Accessibility**: Works on PC and mobile devices.
- **User Management**: Allows admins to add, update, and remove users.

## Technologies Used
- **OpenCV** – For image processing and real-time face detection.
- **TensorFlow** – For deep learning-based face recognition.
- **MTCNN** – For multi-task cascaded face detection.
- **Python** – Core programming language.
- **Flask/FastAPI** – Backend API for system integration.
- **AWS/Azure** – For cloud storage and authentication.
- **SQLite/MySQL** – Database for storing attendance records.
- **Twilio/API Gateway** – For sending real-time alerts.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/AshutoshJha-007/face-recognition-attendance.git
   cd face-recognition-attendance
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the application:
   ```sh
   python app.py
   ```

## Usage
1. Register users by adding their face data and generating a QR code.
2. Users scan their QR code at the entrance.
3. The system verifies their face and records attendance.
4. Admins can monitor logs and receive alerts for unauthorized access.

## Project Structure
```
face-recognition-attendance/
│-- app.py            # Main application file
│-- models/           # Trained deep learning models
│-- database/         # Attendance records
│-- static/           # QR codes, images
│-- templates/        # Web interface (if applicable)
│-- utils/            # Helper functions
│-- requirements.txt  # Dependencies
│-- README.md         # Project documentation
```

## Future Enhancements
- Mobile app integration for remote management.
- Real-time analytics and dashboard.
- Multi-camera support for large-scale deployment.

## Contributing
Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For queries, reach out to me at:

