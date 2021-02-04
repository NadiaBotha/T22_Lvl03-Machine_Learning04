# T22_Lvl03-Machine_Learning04
task02_kmean.py is able to read data from three external csv files, called data1953.cvs, data2008.csv and dataBoth.csv. The data represents the birth rates and life expectancies for a list of different countries in the years 1953 and 2008. The dataBoth.csv file has the data for both years in it.

After reading the data it groups the data point into clusters by using the k-means method. It provides a visual presentation of the clusters on a scatter plot for each iteration. 

## Functions
The user can select how many clusters to form and for how many iterations the k-means should be executed.

For each iteration, the convergence will be displayed, which is the total distance of all the points in the cluster to the cluster centroid. This distance should decrease with each iteration in order to show convergence.

For the final iteration, clusters details are also diaplyed. This includes, the number of data point in a given cluster, the mean birth rate of the cluster and the mean life expectancy of the cluster.

## Use
This program is useful to anyone who needs to categorize countries in clusters according to their birth rates and life expectancies. For example, this can be used by organizations such as United Nations or Doctors without borders in order to determine where the most support is needed. 

## Contributors
Contributors include Nadia Botha and HyperionDev. 

Please send an email to nadiamarais@live.co.za regarding any issues. Include a brief description and screenshot of the issue in the email, with K-Means as the email subject. 

## Installing and running the program
Install Python 3.7 or a later version by clicking [here](https://www.python.org/downloads/).

Download the files (task02_kmean.py, data1953.cvs, data2008.csv and dataBoth.csv) from the Github repository and save them in the same folder. Open Python IDE, IDLE, from the start menu. In IDLE, select file, open, and open the task02_kmean.py file. 

Select Run from the top ribbon, Run the Module, and follow the instructions displayed.
