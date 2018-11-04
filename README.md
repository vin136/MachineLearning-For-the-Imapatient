# MachineLearning-For-the-Impatient
Collection of recipes and some not so well appreciatedd best practices for the impatient..data scientist..


## On Missing Data:
Got missing data just do any one of the following:
1.Remove MISSING rows(sensibly for less than 5% of total data)
2.Impute with some statistic(mean,median etc)
3.Collect more data
Almost all of them give biased estimates.







Some thoughts on missingness:(I didn't choose the naming..)
Based on the nature of missingness .. people divided three basic regimes:
1.MCAR(Missing Completely At Random): Consider we have a data monster who randomly knocks down some of the observations.
2.MAR(Missing At Random):Instead now he looks at something that exists in the world like he knocks down some sales data on every friday to account for heavy traffic.Randomness but on a deterministic process.
3.MNAR(Missing Not At Random):Your thermometer fails every time at high temperature.You have a perfectly deterministic process.



`
