

## Face Recognition System

This is a Python-based face recognition system that allows you to train a classifier on a dataset of faces, generate a dataset of face images, and detect faces in real-time using a webcam.

### Prerequisites

- Python 3.x
- OpenCV
- Pillow
- NumPy
- mysql-connector-python

### Installation

1. Clone the repository or download the code files.

2. Install the required dependencies using pip:

```bash
pip install opencv-python pillow numpy mysql-connector-python
```

3. Make sure you have a MySQL database set up with the necessary table structure. Update the database connection details in the code accordingly.

### Usage

1. Run the `face_recognition_system.py` script.

2. The GUI will appear with three buttons: "Training", "Detect the face", and "Generate dataset".

3. To train the classifier, click the "Training" button. This will train the classifier on the face images in the `data` directory and save the trained model to `classifier.xml`.

4. To generate a dataset of face images, fill in the name, age, and address fields, then click the "Generate dataset" button. This will capture 200 face images using the webcam and save them to the `data` directory with the user's ID.

5. To detect faces in real-time, click the "Detect the face" button. This will open a window showing the webcam feed with detected faces labeled.

### Contributing

If you find any issues or have suggestions for improvements, feel free to create a new issue or submit a pull request.
