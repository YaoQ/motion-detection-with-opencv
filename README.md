# motion-detection-with-opencv
Thanks to **Adrian Rosebrock**, he gives us a very awesome project that using Respberry Pi, Python and OpenCv to detect motion. Details you can read this website:[Home Surveillance](http://www.pyimagesearch.com/2015/06/01/home-surveillance-and-motion-detection-with-the-raspberry-pi-python-and-opencv/).

I has ported this intesting project to pcDuino8 Uno.

### hardware
- pcDuino8 Uno
- Webcam

### software
- Python
- OpenCV
- imutils

### steps
#### 1. Download source code
```bash
$ git clone https://github.com/YaoQ/motion-detection-with-opencv 
```
### 2. Connect webcam
Plug the webcam input pcDuino8 Uno, and the webcam could be recognized as /dev/video0. 

### 3. Test
```bash
$ python motion-detector.py -c conf.json
```

