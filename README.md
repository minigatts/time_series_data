# Sample Data
This is a sample time series dataset for exploration.

Files Provided:

### Time-series field data : data.csv 
Contains many columns, but only the following are relevant:

Date (timestamp)
Weight
Speed
Depth
 

### model.csv: Contains 4 columns, but only the following are relevant:
Tubing Depth
Surface Weight (RIH) 
Task Instructions:

Read the data.csv file and filter out any rows where Weight is greater than 180,000 or less than -180,000 (these values are outside the reasonable range and should be discarded).   

This data is from a coiled tubing job, where we run pipe from surface (depth=0) down to the bottom of the well (max depth of dataset).    We are only interested in the data between starting to run into the hole - and reaching that maximum depth. 

You can discard any data prior to first reaching the depth of 200 ft,  or after reaching the maximum depth seen in the dataset. 

Create two scatter plots :
Weight (x-axis) vs. Depth (y-axis)
Speed (x-axis) vs. Depth (y-axis) on a separate subplot
 
Overlay the model data from model.csv (Weight vs. Depth) on the same Weight vs. Depth plot as a line.
 
Include a legend on the plot to distinguish between the data (scatter) and model (line) for Weight vs. Depth, as well as Speed vs. Depth on its subplot.
 
Ensure the plot is clear and properly labeled (axes, title, etc.).

Expected Output: Your code should produce plots similar to the example provided: one showing Weight vs. Depth (with the model overlaid) and another showing Speed vs. Depth, both with a legend. You do not have to overlay an average line for weight/speed as shown in the example, nor do you need to plot the trend estimates below the dotted red line as seen in the example. Scatter plots with the one model overlaid will be sufficient.
