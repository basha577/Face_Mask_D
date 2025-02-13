# Face_Mask_Detection

# Requiremnts:
pip install tensorflow keras numpy opencv-python imutils pillow


# Run Command for Image Detection
python "Face Mask Image.py" --face face_detector --model mask_detector.model --confidence 0.5


# Run command for Real-time Video Detection
python "Face Mask Video.py" --face face_detector --model model.h5
