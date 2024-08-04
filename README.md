# Data-Visualization-On-Heart-Disease-Dataset
The key to effective data visualization is to choose the right type of plot for the data you are working with, and to use clear and informative labels and titles to help communicate your insights to others.

 

We are going to divide the project into 6 parts:

    Heart Disease EDA - Age (DistPlot)
    Heart Disease EDA - Categorical Columns (Pie Charts)
    Heart Disease EDA - ViolinPlot
    Heart Disease EDA - Correlation (HeatMap)
    Heart Disease EDA - Corrlation (PairPlot)
    Heart Disease EDA - Correlation - (JointPlot)

### Heart Disease EDA - Age (DistPlot)
In seaborn, a distplot is a function that plots a histogram, kernel density estimate (KDE) plot, and/or rug plot on a single figure. It is used to visualize the distribution of a single continuous variable.
So after doing the visualization we can infer that minimum age is around 30 and maximum age is around 80. Maximum of the data falls within the range of 40 to 70.

### Heart Disease EDA - Categorical Columns (Pie Charts)
A pie chart is a circular statistical graphic, which is divided into slices to illustrate numerical proportion. In a pie chart, the arc length of each slice is proportional to the quantity it represents. Pie charts are generally used to show the distribution of a categorical variable.
With the help of pie chart we can see that 79% of the people who are having heart disease are males and 21% are females in our dataset.

### Heart Disease EDA - ViolinPlot
In seaborn, a violinplot is a graphical representation of a continuous distribution, showing the probability density of the data at different values. It is a combination of a box plot and a kernel density plot, with a rotated kernel density plot on each side.
So from this we can see there are more males who are having the chances of having a heart disease compared to females.

### Heart Disease EDA - Correlation (HeatMap)
A correlation heatmap is a graphical representation of the correlation matrix of a dataset, which shows the correlation coefficients between the different variables in the dataset. The values in the matrix are represented as colors, with darker colors indicating a stronger positive or negative correlation.
The values in the matrix are the Pearson correlation coefficients between the different variables, with 1 indicating a strong positive correlation, -1 indicating a strong negative correlation, and 0 indicating no correlation. The colors in the heatmap represent the strength of the correlation, with darker colors indicating a stronger correlation.

### Heart Disease EDA - Corrlation (PairPlot)
A correlation pairplot is a graphical representation of the pairwise relationships between variables in a dataset. It is a matrix of scatter plots, where each scatter plot shows the relationship between two variables. The diagonal of the matrix is a histogram or kernel density plot showing the distribution of one of the variables.

### Heart Disease EDA - Correlation - (JointPlot)
A correlation jointplot is a graphical representation of the joint distribution of two variables, along with their individual distributions. In seaborn, you can create a jointplot using the jointplot function.
 
