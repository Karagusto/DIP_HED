# DIP_HED
Comparisson Edge Detection between Canny and Holistic-Nested(Comparação entre Detecção de Bordas Canny e Holistic-Nested)

Student: Ricardo Augusto Fragoso Omena Lopes
ID: 12111638


To use:
- Download Pycharm(https://www.jetbrains.com/pycharm/) and install it.
- Download the project 'HED.rar' at(https://mega.nz/#!2c1XTQQY!1yeJXKdMvwlKmd8AdmUT7y9t21TKBvnKL_hIY2xoSu8) extract and  set on the path of pycharm 'File' -> 'Open Project'
- When you open the project you must go to 'file' -> 'settings' and under 'Project:' -> 'project interpreter' click on the '+' button on the right to install two packages: 'python-opencv' and 'imutils'.

to run:
- There are two .py files on the project, one for the use on images and another to uso on video.
- You must open the terminal and enter the 'holistically-nested-edge-detection' folder with 'cd holistically-nested-edge-detectio' command to be able to run.
- For the image code you must use the command 'python detect_edges_image.py --edge-detector hed_model --image images/j
apan.jpg' 
- For the video code you must use the command 'python detect_edges_video.py --edge-detector hed_model --input images/test.mp4'
*there are some images and videos on the images folder, but is best to use your own after*
- If you use 'python detect_edges_video.py --edge-detector hed_model' only, you will automatically use the webcam to capture the frames.

References:
- Holistically-Nested Edge Detection with OpenCV and Deep Learning, Available at: https://www.pyimagesearch.com/2019/03/04/holistically-nested-edge-detection-with-opencv-and-deep-learning/ 

- Holistically-Nested Edge Detection. Saining Xie. Dept. of CSE and Dept. of CogSci. University of California, San Diego. 9500 Gilman Drive, La Jolla, CA 92093

