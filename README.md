# nba_clustering

This project focuses on identifying high frequency shooting zones (HFSZ) for multiple teams. For any team, this HFSZ is the region on the basketball court (X, Y coordinates) that has high probability (compared to a threshold value) of a team making a successful shot.

For this project, we purchased two datasets from www.bigdataball.com and performed the following steps:
-	Merged the box score and the play-by-play data using advanced formulas in Excel.
-	Removed all the redundant fields.
-	Created a .csv file with numeric and nominal attributes for each team under consideration. 
-	Performed the k-prototype algorithm on the data. We ran the k-prototype algorithm using different number of clusters and evaluated each of them using the Silhouette index. 
-	Similarly, we performed EM (Expectation-Maximization) Clustering, and used the Bayesian Information Criterion (BIC) to evaluate the right number of clusters and parameters.

This research was published in the proceedings of the Institute of Industrial and Systems Engineering (IISE) Annual Conference in 2017. (https://www.xcdsystem.com/iise/2017_proceedings/prof3171.html)

A short article was also posted on the Rutgers Website: https://mbs.rutgers.edu/articles/student-spotlight-aditya-gandhi-sheds-light-successful-shot-zones-nba-teams-analytics
