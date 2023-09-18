# Yolov7_detect_face
Using yolo v7 detect face
# Clone the repository
```
git clone https://github.com/conggalam12/Yolo-v7.git
```
# Install requirement
```
pip install -r requirements.txt
```
# Download and setup weights
```
mkdir weights
cd weights
wget https://github.com/conggalam12/Yolo-v7/releases/download/weights/face_detection.pt
```
# How to use
```
python detect.py --source [path_image] --weights [path to weight] 
```
The result save in folder run/detect 
# Change folder save
```
python detect.py --source [path_image] --weights [path to weight] --project [path to folder]
```
# Example 
![detect](https://github.com/conggalam12/Yolo-v7/blob/main/runs/detect/exp2/giadinh.jpg)

![detect](https://github.com/conggalam12/Yolo-v7/blob/main/runs/detect/exp3/123123.jpg)

