# tennis_data_visualization
Visualizing Australian open data:

[Link](https://srinuvallabhaneni.github.io/tennis_data_visualization/)

Introduction:

In my analysis of this dataset I tried to prove that if a player does not loose points in Australian open games, he would be statistically in a better position to win the game. I try to prove this seemingly subjective assumption by representing this using a derived feature called dynamic play score which considers First point won, second point won, return points and Ace points. The score is calculated as follows:

	Dynamic play Score= First points won+ Second points won+ return points+ ace points
	Notes: 	1) All the features used above are the key attributes, calculated using PCA for better data classification.
		2) Uses linear addition for better representation of the pie chart.

Data Analysis and Story:

To get meaningful insights from the data provided, I segregated the data into winner data and looser data and the separately checked for missing values. I then supplemented the missing values with the average value of the feature. Then both the winners and looser data is appended vertically. So now we normalize the data to a standard scale and then subjected to Principle Component Analysis (PCA) which resulted in obtaining key attributes for data classification. These key attributes were used to formulate the Dynamic Score. The data was then ordered based on the Dynamic score to get the top 10 players of Australian opens dataset.

Then using this dataset, a bar chart is plotted to represent the top 10 players against their dynamic score over all the matches. Additionally, a pie chart is created beside the bar chart which represents the distribution of the dynamic score (scores of the key attributes obtained using PCA).

Some additional statistics of the Australian open series are represented on the page to represent some information about the series.
