# mediapipe_on_RPi
## Development environment
- Raspberry Pi CM4
- Raspberry Pi OS - Bullseye/Bookworm
- [Camera libraries](https://github.com/atsss/opencv_on_RPi)
    - Picamera2
- IMX219
- [boot/config.txt](https://github.com/atsss/RPi_configs/blob/main/bookworm/imx219.txt)

## Docs
- MediaPipe for Python
> https://developers.google.com/mediapipe/solutions/vision/gesture_recognizer/python
- MediaPipe exampels
> https://developers.google.com/mediapipe/solutions/guide

## How to run script
1. Clone this repository and move the directory
```
chmod +x installer.sh
bash installer.sh
```
2. set up vitualenv (Optional)
```
virtualenv --system-site-packages -p /usr/bin/python3 venv
source venv/bin/activate
```
3. Run
```
python recognize.py
```
