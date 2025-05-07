# RevoltronX-test

# YOLO-Based Room & Object Detection with AI Action Integration

This project uses YOLOv8 for real-time object detection in a webcam feed and integrates AI actions with a simple chatbot that interacts with the user. It also logs detected objects with confidence scores and timestamps into an Excel sheet, while triggering chatbot actions based on detected objects.

## Features

- **Object Detection**: Uses YOLOv8 model to detect objects in a live video feed from a webcam.
- **AI Actions**: Specific actions are triggered for each detected object (e.g., "Would you like to open Netflix?" for TV, "Need assistance?" for person detection).
- **Excel Logging**: Detected objects with their confidence scores and timestamps are logged into an Excel sheet.
- **Chatbot Interaction**: Text-to-speech (using `pyttsx3`) announces the AI actions triggered based on the detected objects.

## Requirements

To run this project, you need the following Python libraries:
- **ultralytics**: YOLOv8 for object detection.
- **opencv-python**: To capture video and display the detection results.
- **pyttsx3**: To convert text (AI action) to speech.
- **pandas**: For handling and storing the Excel log.
- **datetime**: For timestamp generation.
- **openpyxl**: For reading and writing Excel files.

### Installation

Install the required dependencies:

```bash
pip install ultralytics opencv-python pyttsx3 pandas openpyxl
