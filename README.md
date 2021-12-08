## Real-Time Detection And Classification of Traffic Signs using YOLOv5s object detection algorithm.

### Directions to Run The Code-
#### 1) Open the main directory named RecogniSign in your command prompt.
```diff 
pip install requirements.txt
```

```diff 
cd Codes
```
#### 2) Before running the next command, put your test file in the directory named Test.
```diff
python detect.py --source ../Test/(name of your file)
````
#### For eg- If your image name is test.jpg, then put your image in the directory named Test and then run-
```diff
python detect.py --source ../Test/test1.jpeg
```
#### Above same step can also be used to test the model on video files.
#### 3) For running on WebCam run-
```diff
python detect.py --source 0
```
```diff
Check the sample video named - vidd1.mp4
```
### 4) Complete information and specifications are written in the pdf named Documentation.

### 5) Contibutors-
Aryan Garg & Kartik Aggarwal
