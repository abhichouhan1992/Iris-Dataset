# Iris Dataset Flower Prediction Project
Prediction of variety of flower over iris dataset using K-NN algorithm. 
# Introduction
The Iris dataset consists of 150 samples of iris flowers from three different species: Setosa, Versicolor, and Virginica.  Each sample includes four features: sepal length, sepal width, petal length, and petal width.
# Problem Domain
We have Csv file of Iris dataset and now we see There are 4 features in dataset ,which is in numerical form and 1 label which is in categorical (string) form so we use Supervised machine learning for better prediction our model. our model doesn't take string format so we convert string format to numerical format.
# Solution Domain
For this Iris dataset we used K Nearsest Neighbors because (K-NN) algorithm is a versatile and widely used machine learning algorithm that is primarily used for  its simplicity and ease of implementation. It does not require any assumptions about the underlying data distribution. It can also handle both numerical and categorical data, making it a flexible choice for various types of datasets in classification and regression tasks. It is a non-parametric method that makes predictions based on the similarity of data points in a given dataset. K-NN is less sensitive to outliers compared to other algorithm.
# Technology Used
 We used Jupyter Notebook for Iris dataset algorithm and also used diffent types of library from python such as numpy, pandas , matplotlib, seaborn and Scikit-Learn.
 # Mathematical Formula
The K-NN algorithm works by finding the K nearest neighbors to a given data point based on a distance metric, such as Euclidean distance.The class or value of the data point is then determined by the majority vote or average of the K neighbors. This approach allows the algorithm to adapt to different patterns and make predictions based on the local structure of the data.
distance(x, X_i) = [{sqrt{sum_{j=1}^{d} (x_j - X_{i_j})^2} ]   
# Conclusion
For this project, I mainly worked through the Python documentation manuals of the Pandas, Matplotlib and Seaborn modules as well as the Python 3 documentation. There are many resources freely available for learning how to use Python and applying it to analysing datasets such as the Iris dataset. The pandas library is quite intuitive and in a valuable tool in investigating and analysing multi-class multi-variates datasets 
such as the Iris dataset.I looked at the statistical properties of the Iris data set in this project.Visualising the data gives a better understanding of the data and what can be done with it. The Iris data set is referenced quite a bit in machine learning and many resources on the internet use it to demonstrate their product or to teach machine learning methods.We used Scikit-Learn library to implement better prediction of model.
