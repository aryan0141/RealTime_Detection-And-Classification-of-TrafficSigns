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

### Check the sample video named - vidd1.mp4
### Complete information and specifications are written in the pdf named Documentation.

### Contibutors-
Aryan Garg & Kartik Aggarwal
