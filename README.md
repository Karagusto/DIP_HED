# PDI_HED
Comparisson Edge Detection between Canny and Holistic-Nested(Comparação entre Detecção de Bordas Canny e Holistic-Nested)

To use:
- Download Pycharm(https://www.jetbrains.com/pycharm/) and install it.
- Now you must download the github project and set on the path 'File' -> 'Open Project'
- When you open the project you must go to 'file' -> 'settings' and under 'Project:' -> 'project interpreter' click on the '+' button on the right to install two packages: 'python-opencv' and 'imutils'.

to run:
- There are two .py files on the project, one for the use on images and another to uso on video.
- You must open the terminal and enter the 'holistically-nested-edge-detection' folder to run
- For the image code you must use 'python detect_edges_image.py --edge-detector hed_model --image images/j
apan.jpg' 
- For the video code you must use 'python detect_edges_video.py --edge-detector hed_model --input images/test.mp4
*there are some images on the images folder, but is best to use your images after*
- If you use 'python detect_edges_video.py --edge-detector hed_model' only you will automatically use the webcam to capture the frames.

References:
- Holistically-Nested Edge Detection with OpenCV and Deep Learning, Available at: https://www.pyimagesearch.com/2019/03/04/holistically-nested-edge-detection-with-opencv-and-deep-learning/ 

- Holistically-Nested Edge Detection. Saining Xie. Dept. of CSE and Dept. of CogSci. University of California, San Diego. 9500 Gilman Drive, La Jolla, CA 92093

