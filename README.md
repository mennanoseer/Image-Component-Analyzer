# Image Component Analyzer
This project is a web application built with Streamlit that allows users to upload images and analyze the components within those images using the YOLOv8 object detection model.
## Features
- Upload an image in JPG, JPEG, or PNG format.
- Analyze the uploaded image to detect various components.
- Display detected components with their confidence scores.
## Installation
To run this project locally, you need to have Python installed. Follow the steps below:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/image-component-analyzer.git
   cd image-component-analyzer
   ```

2. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage
 Run the following command:
```bash
streamlit run app.py
```
This will open a new tab in your default web browser with the Image Component Analyzer application.

## How to Use
1. **Upload an Image:**
   - Click on the "Choose an image..." button.
   - Select an image file from your local machine (supported formats: JPG, JPEG, PNG).
2. **Analyze Image:**
   - After the image is uploaded, it will be displayed on the screen.
   - Click the "Analyse Image" button to detect objects in the image.
   - The detected components along with their confidence scores will be listed below the button.

## File Structure
- `app.py`: The main Python script that runs the Streamlit application.
- `requirements.txt`: A list of Python packages required to run the application.
- `README.md`: This readme file.

## Dependencies
- `streamlit`: For creating the web interface.
- `ultralytics`: For the YOLOv8 model.
- `Pillow`: For image processing.


## Acknowledgments

- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) for the object detection model.
- [Streamlit](https://streamlit.io/) for the easy-to-use web application framework.
