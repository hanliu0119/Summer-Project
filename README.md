# Summer-Project
merge Interactive Visual Analytics tools with Data Science tools, prepare for MS thesis
Platform Requirements and Packages
1. Python 3 
2. Jupyter Notebook
3. Python packages: ipywidgets, matplotlib, numpy, pandas, sklearn, random


Code Design
1. Initialization of sliders
2. MDS function 
* Convert high-d data to 2D data
3. Interactive Plot with Sliders
* Allow users to drag the sliders to change the weights
* Then the scatter plot will be changed simultaneously
4. Draggable Plot with Updated Weights
* The input weights in this section is the updated version from the 3th step
* Allow the users to drag any points on the plot to any place
5. Retrieve the Old and New Coordinates
* Retrieve the coordinates of points before and after being dragged by users
6. Inverse lowD to highD
* Proposal：produce a new weight by moving to a random direction with a specific step 
* Stress: calculate the stress between old low-d data and new low-d data calculated by high-d data
* invMDs: produce a weight list from the inverse process of MDS, which creates a new high dimensional data.
