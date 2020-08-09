# KNN-algorithm-for-unknown-dataset
This is a classification problem, where I have worked on a data-set where the names of the labels are unknown(names are replaced with some random value). I have used K-nearest neighbor algorithm to predict the values for the target data. 


Now let me explain the process,


First of all I have implemented a dataset where the labels are hidden(or replaced with some random value),
<br>


<img src="Images/initialDataset.PNG">
<br><br>

Then I have scaled the data using "fit" and "transform" methods and remove the "TARGET CLASS" from the dataset.


<br>
<img src="Images/AfterScaling.PNG">
<br><br>

Then for experimental purposes I have taken K=1 and made the predictions,

<br>
<br>
<img src="Images/K=1.PNG">
<br>
And here is the prediction result that I got from the classification matrix,
<br>
<br>
<img src="Images/K=1_Classification_Matrix.PNG">
<br>

Then I have used <b>"Elbow Method"</b> to find the best <b>"K"</b> value.

<br>
After applying the Elbow method I got this graph,
<br>
<br>
<img src="Images/ElbowMethodDiagram.PNG">
<br>
From the above diagram you can see that error rate is min for values like 12 or 17.7 . I am choosing 12 to impliment the algo.
<br>
<br>
<img src="Images/K=12.PNG">
<br>
<br>
And I got this classification matrix,
<br>
<br>
<img src="Images/K=12_Classification_matrix.PNG">
<br>
<br>
As you can see the prediction values are much better than the previous one.
<br>
<br>
Thank you for visiting and please let me know if you have any queries. 
