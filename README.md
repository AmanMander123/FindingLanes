# **Finding Lane Lines on the Road** 
***
In this project, we use the following tools to identify lane lines on the road:  
* Color selection  
* Region of interest selection  
* Grayscaling  
* Gaussian smoothing  
* Canny Edge Detection  
* Hough Tranform line detection  

We develop a pipeline on a series of individual images, and later apply the result to a video stream (really just a series of images). Check out the video clip "raw-lines-example.mp4" (also contained in this repository) to see what the output should look like after using the helper functions below. 

Once the result looks roughly like "raw-lines-example.mp4", we get creative and extrapolate the line segments we've detected to map out the full extent of the lane lines.  We can see an example of the result we're going for in the video "P1_example.mp4".  Ultimately, we would like to draw just one line for the left side of the lane, and one for the right.
