# virtualPaintbyOpenCV
OpenCV is used to create a simple paint application that uses a webcam of PC. Orange, red, green, and blue colorful pens can be used to draw after the project is run. Also, image processing by using OpenCV is explained by stacking images. 

## Image Processing
OpenCV provides to convert images to different versions like Blur, Canny, or Gray. A function is used to stack these versions in a window. Also, by using getCountors method the angles of shapes counted and it decides which shape it is. The related information is written something close to the center point of shapes. 

## ColorPicker
It is used to detect HSV values of colours by using webcam of PC. After the related colour values found,it is used for the virtual paint. By changing the values of trackbar anyone
can found a HSV value of a color. 

## Virtual Paint
It mostly has same functions with the other files. It recognizes the colors of pens from the webcam and draws that colour by movement. To make this project proper, you may find
the color of an object by using ColorPicker and then use that object to draw something by using webcam.
