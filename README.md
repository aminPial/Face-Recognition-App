# Face Recognition Module for Windows
This repository used `face_recognition module` from 
https://github.com/ageitgey/face_recognition. There is an working version
for `linux` in that repository. But for <b>`windows user`</b> the 
installation has been so difficult. We tried to solve this issue 
by providing **pre-built whl** in the repository and install from them.The two modules are:-

<code>dlib module: dlib-19.8.1-cp36-cp36m-win_amd64.whl</code>
<code>face-recognition module: face_recognition-1.2.3-py2.py3-none-any.whl </code>

## Getting Started

Make sure you have Python 3 and pip installed on your system.And then
run
<code>python install.py</code>. And then you can use **face_recognition
module in Windows**. After you install please follow the documentation
given in this awesome repository: https://github.com/ageitgey/face_recognition and use it.

**For ease of use there is already a code for face recognition from video input.**
Both faster and slower method with low and high accuracy. If you want to test it
out please follow below documentation.

## Video Input face Recognition Doc 
Todo:
1. Put your **face image** with naming image with your name in the database folder. e.g:<code>AminPial.jpg
(There is an image already in the database that is detecting the face in the video which is shown in GIF)</code>
2. Then run <code>python faster_recognition_low_acc.py</code> or <code>
python slower_recognition_high_acc.py</code>
3. The code will show something like the following GIF:
![Demo](AminPial.gif)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

