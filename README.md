## Real-Time Detection And Classification of Traffic Signs using YOLOv5s object detection algorithm.

### Directions to Run The Code

1) Open the main directory named RecogniSign in your command prompt.
2) Firstly install all the required dependencies using the requirements.txt fileIf you are using windows machine:
Type - pip install -r requirements.txt in your cmd.
Or if you are using anaconda promptType - conda install --file requirements.txt
3) Then go to the directory named Codes using the commandType - cd Codes
4) Before running the next command, put your test file in the directory named Test.
Type - python detect.py --source ../Test/{name of your file}
For eg- If your image name is test.jpg, then put your image in the directory named Test and
then run python detect.py --source ../Test/test.jpg
5) Above same step can also be used to test the model on video files.
6) For running on WebCam run python detect.py --source 0
7) A pop up window appears as shown below in Fig.2, showing the bounding boxes of all Traffic
signs present in that frame with their label and accuracy score. FPS for each frame is also
shown in the top-left corner of that window.
8) Also, the output results are saved in the directory named Results
