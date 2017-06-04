# **Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of multiple steps, Applying a color mask, Performing edge detection,

 Selecting regions to search for lines, Using Hough transform to search for line segments, extrapolating the lane from line segments  

Code suggested during the classroom is used in the notebook

### 2. Identify potential shortcomings with your current pipeline


Few potential shortcoming would be my current pipeline is highly sensitive to color  and has hard coded regions which need to be automated

### 3. Suggest possible improvements to your pipeline

Use better tuned parameters for Hough transform and edge detection and remove parts where values are hard coded by automating their calculation
