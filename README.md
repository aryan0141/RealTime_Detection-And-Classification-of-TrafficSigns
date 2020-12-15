## Real-Time Detection And Classification of Traffic Signs using YOLOv5s object detection algorithm.

### Directions to Run The Code
#### Open the main directory named RecogniSign in your command prompt.
```diff 
pip install requirements.txt
```

```diff 
cd Codes
```
#### Before running the next command, put your test file in the directory named Test.
```diff
python detect.py --source ../Test/(name of your file)
````
#### For eg- If your image name is test.jpg, then put your image in the directory named Test and then run-
```diff
python detect.py --source ../Test/test.jpg
```
#### Above same step can also be used to test the model on video files.
#### For running on WebCam run $ python detect.py --source 0
##### A pop up window appears as shown below in Fig.2, showing the bounding boxes of all Trafficsigns present in that frame with their label and accuracy score. FPS for each frame is also shown in the top-left corner of that window.
#### Also, the output results are saved in the directory named Results

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
