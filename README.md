# mediapipe_on_RPi
## Development environment
- Raspberry Pi CM4
- Raspberry Pi OS - Bullseye/Bookworm
- [Camera libraries](https://github.com/atsss/opencv_on_RPi)
    - OpenCV 4.5.1
    - Picamera2
- IMX219
- [boot/config.txt](https://github.com/atsss/RPi_configs/blob/main/bookworm/imx219.txt)

## Docs
- MediaPipe for Python
> https://developers.google.com/mediapipe/solutions/vision/gesture_recognizer/python
- MediaPipe exampels
> https://developers.google.com/mediapipe/solutions/guide

## How to install
1. Clone this repository and move the directory
2. Install OpenCV and Picamera2
```
chmod +x installer.sh
bash installer.sh
```
3. Test
```
cd scripts && python test_picamera.py
```
