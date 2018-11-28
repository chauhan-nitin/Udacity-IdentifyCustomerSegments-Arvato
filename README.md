# Data Scientist Nanodegree
## Unsupervised Learning

* ```Challenge:``` Udacity Data Scientist Nanodegree project for unsupervised learning module titled as 'Identify Customer Segments' brings Bertelsmann partners AZ Direct and Arvato Financial Solutions whose two datasets one with demographic information about the people of Germany, and one with that same information for customers of a mail-order sales company are provided for this challenge. The objective is to look at relationships between demographics features, organize the population into clusters, and see how prevalent customers are in each of the segments obtained. Prior to applying the machine learning methods, we also require to assess and clean the data in order to convert the data into a usable form.

* ```Solution:``` Preprocessed the data which includes identifying missing or unknown values encoded in the data and checking if certain features (columns) that should be removed from the analysis because of missing data. Feature transformation which includes using dimensionality reduction techniques to identify relationships between variables in the dataset, resulting in the creation of a new set of variables that account for those correlations. Lastly clustered, using the k-means method to cluster the demographic data into groups.

* ```Result:``` Using seaborn package created a visual comparison representation of customer data vs demographic data and concluded which segments/clusters of customers can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns.

### Software and Libraries
This project uses the following software and Python libraries: <br>
NumPy, pandas, Sklearn / scikit-learn, Matplotlib (for data visualization), Seaborn (for data visualization)

### Code File
Open file jupyter notebook Identify_Customer_Segment.ipynb
