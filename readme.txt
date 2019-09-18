1. Face recognition and detection through webcam
-->dataset folder contains all the images on which we have trained the model.
-->opencv folder has the opencv package along with haar cascade classifier.
-->20190504_103026.mp4 is the video i recorded for the demonstration.
-->dataset.py script is the script we are using for dataset creation.
-->train.py script is the script we are using for training the model.
-->detect.py scirpt is the script we are using for the face recognition and detection part.
-->trainner.yml is the file to which we saved our trained model, and load it before making predictions.
pipfile, pipfile.lock --> these were virtual env files.


2. Face recognition and detection through images and inputted video
-->dataset --> this folder contains the images of john and danerys
-->examples --> this folder contains the images on which we are testing our model.
-->output --> this folder contains the final created video with face detection and recognition.
-->videos --> this folder contains the inputted video.
-->encodings.pickle --> this is a pickle file where we are storing the encodings and later we load it back before making predictions.
-->face_encodings --> script having the logic to create facial encodings.
-->face_recognize --> script having the logic to recognize faces in images.
-->face_recognize_video --> script having logic to recognize faces in videos.