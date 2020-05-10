
## Lane Finding Pipeline

My solution has two main parts:
- First 5 steps for preparing image for lane line detection process.
- Second 7 steps for processing the prepared image to find lines and draw the detected lane lines on the main image.

![My solution pipeline](./media/CarND-LaneLines-P1.svg)

## Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

in the first 5 steps of my processor prepare the image which will be used for lane line detection. This image contains only the 

After the 


### 2. Identify potential shortcomings with your current pipeline

One potential shortcoming would be if the road doesn't have lane lines.


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to draw the curves not with the straight lines but with curve lines
