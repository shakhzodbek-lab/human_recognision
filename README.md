# human_recognision
Sample Code for pedestrian recognision in Python


# Video Human Detection using OpenCV

## Overview

This Python script utilizes OpenCV to perform human detection in a video file. It employs a pre-trained Haar Cascade Classifier for full-body detection.

## Prerequisites

- Python 3.x
- OpenCV
  ```bash
  pip install opencv-python
  ```

## Usage

1. Clone the repository or download the script and the required XML file (`haarcascade_fullbody.xml`).
2. Make sure you have a video file (e.g., `123123.avi`) in the same directory as the script.
3. Run the script:
   ```bash
   python your_script_name.py
   ```
4. The script will display the video with rectangles drawn around detected human bodies.

## Parameters

- `cv2.VideoCapture('123123.avi')`: Change the video file name or path accordingly.
- `cv2.CascadeClassifier('haarcascade_fullbody.xml')`: Make sure the XML file path is correct.

## Controls

- Press 'q' to exit the video window.

## Customization

Feel free to adjust the parameters in the script, such as the scaleFactor and minNeighbors in the `detectMultiScale` function, to fine-tune the human detection according to your needs.

## License

This project is licensed under the [MIT License](LICENSE).

---

