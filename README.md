# Somatosensory-control-car-based-on-kinect
Elderly people with limited mobility often need smart assistive devices. For the elderly, it is more difficult to use a complex controller. Therefore, we plan to design a smart car robot based on human posture recognition. The robot is controlled by the Raspberry Pi and can distinguish different postures based on the human bones recognized by the kinect, such as steering, forward, backward, camera steering, and robotic arm pitching. , End effector opening and closing operations.

1. Hardware:
1) The TH-ROBOT raspberry pi car of XiaoR Technology, equipped with a 3 DOF manipulator, camera, raspberry pi 3B and motor drive board.
2) Kinect2.0 sensor, with infrared sensor, depth perception, gesture recognition and other functions.
3) A laptop, Win10 system, as the host computer, connect to Kinect, and wirelessly connect to Raspberry Pi.

2. Software:
1) Putty: used for SSH communication with the Raspberry Pi, and enter the command line to control the Raspberry Pi.
2) WinSCP: Used to transfer files conveniently and intuitively with Raspberry Pi.
3) Notepad++: Conveniently write Python script code for Raspberry Pi to call.
4) Microsoft Visual Studio2019: used for C++ environment construction, C++ code writing and debugging.
5) OpenCV2: used for image processing, drawing, displaying images, etc.
6) Pthread: Multithreaded package, manages multithreaded code.
7) Kinect SDKs for Windows: some link libraries and header files related to Kinect.
