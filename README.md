<h1> Introduction </h1>
A sample size of 10 000 synthetic patients' data was created from scratch to analyse the patients' blood pressure. 
The features that were examined are age, gender, height, weight, diastolic Blood Pressure and systolic Blood Pressure.
Goal: To examinine a collection of data points (patients' data) and grouping them into clusters according to some distance measure to know the similarity between them.

<p>Research was done to find out the average systolic and diastolic blood pressure before populating the patients' data.</p>
<p>Average Male BP : a systolic blood pressure of less than 120 mm Hg and a diastolic blood pressure of less than 80 mm Hg.</p>
<p>Average Female BP : a systolic blood pressure of less than 120 mm Hg and a diastolic blood pressure of less than 80 mm Hg</p>


<h2> K Clustering </h2>
<p>K clustering was done by building a clustering algorithm from scratch and also a provided Sklearn KMeans method.</p>
<ol>Steps taken to perform clustering:
<li> Deciding the clustering variables which are the age, gender, height, weight, diastolic BP and systolic BP.</li>
<li>Standardisation : Objective is to adjust for differences in scale. Variables with bigger values will naturally dominate the choice of clusters.
   Methods used for standardisation :  X – Minimum Value / Range of Values</li>
<li> Specify the number of clusters needed denoted as K</li>
<li>Randomly initialise the centroid for each cluster. </li>
<li>Determien which data points belong to which cluster by finding the closest centroid to each data point using mean geometric calculation.</li>
<li> Update the centroids based on the geometric mean of all the data points in the cluster.</li>
<li>Iterate step 5 and 6 until the centroids stop changing. </li>
</ol>

<h2> Insights </h2>
<p>3 clusters were created.</p>
<ol>
<li> Cluster 0 and Cluster 1 have quite similar observation where their age, systolic, and diastolic BP are quite close except that the weight of Cluster 1 patients are highet than that of Cluster 0. </li>
<li> Cluster 2 patients are younger whihc then explained the lower systolic and diastolic blood pressure supported by the lower height and weight too.</li>
</ol>

</h2> Improvements </h2>
<ul>
<li>Data transformation should be done on gender by grouping them into 0 and 1 instead of M and F, so SKlearn Clustering could be done on them too.</li>
<li> BMI can be added.</li>
<li>More features such as smoking habits, occupations, lifestyle attributes could be added to make the analysis more realistic.</li>
<ul>

</h2> Sources </h2>
<ol>
<li> https://www.heart.org/en/health-topics/high-blood-pressure/understanding-blood-pressure-readings/updated-aha-asa-high-blood-pressure-guidelines-for-men </li>
<li>https://www.heart.org/en/health-topics/high-blood-pressure/understanding-blood-pressure-readings/updated-aha-asa-high-blood-pressure-guidelines-for-women </li>
</ol>

  




