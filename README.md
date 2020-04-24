# minimal-face-detection

The Python script uses OpenCV to detect faces in images and videos.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install OpenCV.

```bash
pip install opencv-python
```
Download the [Harcascade](https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_frontalface_default.xml) from OpenCV.


## Usage

```python
import cv2

faces = face_cascade.detectMultiScale(gray,1.1,4) #detect_faces 
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
