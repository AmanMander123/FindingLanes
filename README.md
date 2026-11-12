# **Finding Lane Lines on the Road** 
***
In this project, we use the following tools to identify lane lines on the road:  
* Color selection  
* Region of interest selection  
* Grayscaling  
* Gaussian smoothing  
* Canny Edge Detection  
* Hough transform for line detection

The [notebook](FindingLanes.ipynb) builds the pipeline on individual images and then applies it frame by frame. The [raw line detections](raw-lines-example.mp4) show the intermediate segments. The final pipeline extrapolates those segments to draw one boundary on each side of the lane. See the results on the [white lane marking clip](white.mp4) and [yellow lane marking clip](yellow.mp4).
