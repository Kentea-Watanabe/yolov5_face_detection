# yolov5_face_detection

![image](https://user-images.githubusercontent.com/87839643/204943641-100a5602-f59e-4a77-9b6a-7e198d6a09d6.png)


## Demo
```
!git clone https://github.com/Kentea-Watanabe/yolov5_face_detection.git

!git clone https://github.com/ultralytics/yolov5 # clone repo
!pip install -qr yolov5/requirements.txt  # install dependencies (ignore errors)
%cd yolov5
```

```
import torch
from IPython.display import Image, clear_output

!python detect.py --source ../test_img/test.jpg --weights ../weight/face_detection_best.pt --img 416
```
