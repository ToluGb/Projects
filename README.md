# Face Detection with OpenCV

# Aim
The aim of the project is to determine the number of faces present in a given image by face detection and generate an output indicating the count.

# Methodology
1. First of all, the necessary libraries to be used are imported
2. Next, the images are uploaded and stored in a 'Path' folder
3. A function is defined and the tasks carried out are discussed in the foregoing.
4. The respective image inputs which were given in pixels are stored in a list and then converted to the png format
5. Next, the images are converted to grayscale and displayed
6. An instance of the haarcascades Cascade classifier is created
7. The faces are detected from the images using the detectMultiScale function and the scale factor is adjusted with respect to the images for accurate detection
8. The count of the faces detected is displayed
9. Rectangles are drawn about the detected faces for easy identification
10. The images are displayed with the rectangles about the detected faces

# Results
From the results obtained, only the first image had an accurate count of the number of faces detected. The other images did not give an accurate count of the number of faces detected.

# An Alterative to solving the problem.
HOG: The histogram of oriented gradients (HOG) is a feature descriptor used in computer vision and image processing for the purpose of object detection. The technique counts occurrences of gradient orientation in localized portions of an image. The basic idea of HOG is dividing the image into small connected cells. The only disadvantage with HOG based face detection is that it doesn’t work on faces at odd angles, it only works with straight and front faces.


