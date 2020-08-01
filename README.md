# Image_Scanner_with_Python

Initially we need to resize the images so OpenCV can handle it and then the following functions are applied

-> Guassian Blur to smoothen image.
-> Canny Edges to detect the edges.
-> Find contours and boundary of the page
-> Map the end points of contours to 800 * 800 window
-> Apply perspective trasform to get scanned or bird eye view of the image.
