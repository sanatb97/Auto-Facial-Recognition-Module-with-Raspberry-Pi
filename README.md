<h1>Auto-Facial-Recognition-Module-with-Raspberry-Pi</h1>

<h4>A simple module to achieve facial recognition using Raspberry Pi 3 Model B and a Raspberry Pi Camera Module v2.</h4><br>
<h4>Implemented using OpenCV.</h4><br>
<h4>HaarCascade Classifier and LPBH FaceRecognizer have been used for face detection and recognition</h4>
<br>
<h3>Order of Execution of programs:</h3>
<ul><li>$ python cam_test.py  - This is to test whether your camera module/webcam is working.
  </li><li>$ python facedetection.py   -This is to check whether the camera detects a face</li>
  <li>$ python datagather.py         -This is to create a user entry and add 50 images of his/her face to the folder "dataset"</li><li>$ python trainer.py         -This is to train the ML model to recognize the given faces</li>
  <li>Add the name of the Face added in the datagather step in the "recognizer.py" file in the names list.Then,<br>
    execute $ python recognizer.py    -This will detect and recognize the trained faces on the live camera feed.</li></ul>

  

 

