# PAN Card Tampering Detector

This project is a web-based application for detecting tampering or forgery on PAN cards using OpenCV and Flask. It compares the input PAN card image against the original format to check for discrepancies. Flask is used as the backend to serve the web application, where users can upload PAN card images. OpenCV handles the image processing, detecting anomalies like alterations in text, layout, or security features.

### Key Features:
- **Image Upload**: Users can upload PAN card images via the web interface.
- **Forgery Detection**: The application uses OpenCV to analyze the image for any tampering (e.g., inconsistent fonts, altered text, mismatched dimensions).
- **Results Display**: After analysis, the result is displayed on the web page, indicating whether tampering is detected.

### Technologies Used:
- **Flask**: For building the web interface and handling user requests.
- **OpenCV**: For image processing and tampering detection.
- **Python**: As the core language for logic and integrations.

