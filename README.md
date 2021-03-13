# Offside-Detection-on-Footbal-Ground-Using-Python-and-Computer-Vision-Libraries
Offside Detection on Footbal Ground Using Python and Computer Vision Libraries

Input and Output Image of this code are uploaded as well. Kindly Check them to get clear idea of the code.
To get more information of each function and various data/image processing and transformations applied in the code. Kindly go through Word document which is also uploaded.


Major Steps of the ALGORITHM:
1.	Find at least four corresponding/matching points for the Image and Field.
2.	Find the Homography by using cv.findHomography function.
3.	Select Any two points (They can be defender and attacker players) in the Image.
4.	Find the Mapping of above two selected points to the Field.
5.	Now find the Points, in the Field, which represent the LINE.
6.	Then Map those 4 Field points, which represent the Two Lines, to the Image plane.
7.	After getting the Line points. Draw the Lines on Image Plane.
8.	Find the Distance b/w those two Parallel Lines which are on the Image Plane.
