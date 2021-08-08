# Data-Visualization
- In this mini-project, we will focus on analyzing different aspects and statistics of the sport Soccer and visualizing historical data in such a way that it will help study different patterns and strategies various clubs/teams use and also study the strengths and weakeness of individual players.

## Libraries Required
- [json](https://docs.python.org/3/library/json.html)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [squarify](https://github.com/laserson/squarify)
- [functools](https://docs.python.org/3/library/functools.html)

## Dataset
- We have used a special and powerful opensource data-set by StatsBomb. It provides highly detailed information of several games event by event with record of evry time-stamp. [Click here to explore the data set](https://github.com/Sidhved/open-data)

## Visuals
- Firstly, we prepare a canvas to plot our data in the shape of a football field as shown below.<br>
![Pitch]('Images_Data\Pitch.png')<br>
- Now we will plot Passes in form of vector and also analyze the density of pass origin using a kdeplot.<br>
![PassMap](https://github.com/Sidhved/Data-Visualization/blob/main/Images_Data/Passes1.png) ![kdePlot]('Images_Data\Passes2.png')<br>
![Combined]('Images_Data\Passes3.png')<br>
- Now let's target a particular team (here, FCB) and observe the patterns in the shots attempted using the vectors.<br>
![Shots](Images_Data\Shots1.png)<br>
- We can easily conclude from the above image that maximum shots on target were originated within the 6-yard box. Let us understand this more clearly using the color coordinated scatter plot shown below. The red dots represents the origin place of the shots that were able to meet the back net whereas the blue ones were either deflected, saved by the keeper, or simply off-target.<br>
![ShotsScatter](Images_Data\Shots2.png)<br>
- For the final part, we will firstly create a new dataframe to fit different skills of each individual player as a seperate attribute and compare it with standard deviation to get player rating. The normalized data of each individual player is the plotted on a spider-plot that display's the player's strength and weakness. Thus we can derive areas of excellence and areas for potential improvement.<br>
![PlayerProfile](Images_Data\Profile.png)

## Important Links
- [x] [Python NoteBook](Data\DV.ipynb)
- [x] [Colab Link](https://colab.research.google.com/github/Sidhved/Data-Visualization/blob/main/Data_Visualization_Presentation.ipynb)
- [x] [Dataset](https://github.com/Sidhved/open-data)