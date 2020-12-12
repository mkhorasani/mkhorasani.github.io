## Quality of Life vs. Purchasing Power Visualization
### CS 498 Data Visualization Final Project

![Quality of life visualization](https://github.com/mkhorasani/mkhorasani.github.io/blob/master/Quality%20of%20life%20visualization.PNG?raw=true)

To view this visualization please refer to the following [link.](https://mkhorasani.github.io/)

### Messaging:
This visualization attempts to narrate and depict the relationship between the quality of life and purchasing power for various countries and regions in the world. Specifically, this visualization may help the user in selecting a country for living by determining how much quality of life, purchasing power and cost of living they will have. It is worthy to note that these three quantities are all unitless indices.

### Narrative Structure:
The structure used for this visualization is of the 'interactive slide show' form with three scenes exhibiting the same scatterplot but with different annotations. This narrative visualization allows the user to 'drill-down' and explore with navigation buttons to access each slide. This visualization has a sequential order where each scene provides additional information in the form of annotations that build on top of what was mentioned in the previous scene in the slide show.  

### Visual Structure:
The visual structure utilized for this visualization is a scatterplot that establishes the relationship between the quality of life and purchasing power. The scatterplot is equipped with a visual tooltip for each and every point that provides additional information on demand to the user such as country name and cost of living. Furthermore, the scatterplot has average lines on both the x and y axis that give the user a visual reference to the status of each country with respect to the global average. The legend provides another narrative visual aid by segregating continents based on color. 

The annotations in each slide direct the user's attention to the information provided by each visual aid in the scatterplot. Furthermore, each annotation provides a logical transition from the previous slide by stating new information that builds on top of what was shown in the previous scene.

### Scenes:

#### Scene 1: 
This scene narrates the relationship between quality of life and purchasing power between many of the countries in the world.

#### Scene 2:
This scene narrates the positioning of each country with respect to the world average in quality of life and purchasing power. In addition, this scene also narrates how continents are roughly clustered together and how the user can use the legend to differentiate between them. 

#### Scene 3:
This scene narrates the cost of living index of each country by asking the user to move their mouse over each point to reveal the provided tooltip. In addition, it explains the visual aid of how each point is sized in proportion to each country's cost of living index. 

### Annotations:
The annotations are utilized to direct the user's attention to the relationship in the data and to other visual aids such as the tooltip, legend and data point sizes that provide additional information. The annotations all use a consistent font and font size. The annotations are all situated within the scatterplot visualization in order to attract the user's attention to them as they provide crucial information. The first annotation draws the user's attention to the relationship between the quality of life and purchasing power. The second annotation directs the user's attention to the average lines and legend. The third and final annotation asks the user to use their mouse to reveal the tooltips that provide additional information for each data point.

### Parameters:
In this visualization several parameters are used to narrate additional visual information. Firstly, the parameter 'continent' is used as a color-coded quantity that allows the user to visualize the approximate clustering of countries within the same continent in the scatterplot. Another parameter used is the cost of living index which is exhibited as the radius of the data point on the scatterplot, i.e. as the cost of living increases so does the radius of the point. 

The current state of the visualization is controlled by the parameter country name and cost of living index which are revealed as tooltips on the scatterplot. When the user moves their mouse over each datapoint, the state is changed, and a corresponding tooltip is revealed with a transition. When the user moves their mouse off the point the state changes once again as the tooltip is removed with a transition that reduces its opacity to 0.

### Triggers:
In this visualization two sets of triggers are used. Namely the navigation buttons that allow the user to access various slides and the mouseover triggers that reveal the tooltips for each data point. Affordances are represented with colors for the navigation buttons, i.e. when the button for a certain slide is selected the brightness of the button's text increased and when it is deselected its brightness is reduced to communicate to the user the state of the visualization. In addition, the annotations communicate to the user on how to use the triggers for the tooltips. 

### References:

1. https://www.numbeo.com/quality-of-life/

2. https://github.com/vlandham/stepper_example/blob/gh-pages/final_d3/index.html
