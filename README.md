# Self-Driving-Car_Finding-Lane-Lines
Implement finding lane line algorithm of self driving car using techniques such as Canny filter and Hough Transform through openCV.

# Description of the pipelines:
1) First, i converted the image to grayscale and apply Canny filter to the image to get the edges. Next, i apply a filter to the canny image to filter out the unwanted area of the image so that only the center part of the image that contain the lane lines of the road will be remained in the image. After that, i pass the image to Hough Transform method to get the 2 points of the lane lines. Since the lane lines I get are segmented due to the dashed line on road, I need to extrapolated the line 
