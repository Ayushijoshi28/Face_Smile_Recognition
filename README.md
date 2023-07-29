# Face and Smile Recognition
This Python script uses the OpenCV library to perform real-time face and smile recognition from a video feed (e.g., a webcam). The script captures frames from the video and detects faces and smiles using Haar cascades classifiers provided by OpenCV. If the script detects a face and a smile simultaneously for five consecutive frames, it captures a selfie and saves it as "selfie.png".

## How the Script Works
1. The script loads the Haar cascade classifiers for face and smile detection provided by OpenCV.

2. It initializes the video capture object to access frames from the webcam (or any other video source).

3. The script enters a loop where it continuously captures frames from the video feed.

4. For each frame, it converts the image to grayscale and detects faces using the face cascade classifier.

5. For each detected face, it extracts the region of interest (ROI) and looks for smiles using the smile cascade classifier within that ROI.

6. If a smile is detected within a face for five consecutive frames, the script captures a selfie and saves it as "selfie.png".

7. The script uses colored rectangles to highlight the detected faces and smiles in real-time.

8. Pressing the 'x' key on the keyboard terminates the script and stops the video capture.

## Usage
1. Ensure you have OpenCV installed (pip install opencv-python) and a webcam connected to your system.

2. Run the script, and a window named "Preview" will open, showing the webcam feed with face and smile recognition.

3. If the script detects your face and a smile simultaneously for five consecutive frames, it will capture a selfie and save it as "selfie.png" in the same directory as the script.

4. Press the 'x' key on the keyboard to close the "Preview" window and stop the video capture.

## Important Note
Please note that face and smile detection using Haar cascades can have limitations, and the accuracy may vary depending on the lighting conditions, face orientation, and other factors.

## Example Output

![Screenshot (8)](https://github.com/Ayushijoshi28/Face_Smile_Recognition/assets/88037464/f4695f34-e03b-4d5e-bcf1-1a093d384a1e)
