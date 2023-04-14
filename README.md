<h1> Introduction </h1>
A sample size of 10 000 synthetic patients' data was created from scratch to analyse the patients' blood pressure. 
The features that were examined are age, gender, height, weight, diastolic Blood Pressure and systolic Blood Pressure.
Goal: To examinine a collection of data points (patients' data) and grouping them into clusters according to some distance measure to know the similarity between them.


Research was done to find out the average systolic and diastolic blood pressure before populating the patients' data.
Source: https://www.ahajournals.org/doi/10.1161/01.hyp.37.5.1199

<h2> K Clustering </h2>
K clustering was done by building a clustering algorithm from scratch and also a provided Sklearn KMeans method.
Steps taken to perform clustering:
1) Deciding the clustering variables which are the age, gender, height, weight, diastolic BP and systolic BP.
2) Standardisation : Objective is to adjust for differences in scale. Variables with bigger values will naturally dominate the choice of clusters.
   Methods used for standardisation :  X – Minimum Value / Range of Values
3) 
  




