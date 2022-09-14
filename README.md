
# Background 
There are four variables used to describe the three species of Iris in the dataset. Sepal Width, Sepal Length, Petal Length, and Petal Width are the features used to distinguish the species ( <em>Iris setosa, Iris, viginica,</em> and <em> Iris versicolor</em>) 
<p align="center"> <img src="https://miro.medium.com/max/700/0*Uw37vrrKzeEWahdB"/> </p>

# Objective
This project's purpose is to demonstrate ability to perform a preliminary investigations of the Iris data in order to discover trends, anomalies, check assumptions with the help of statistical insight and graphic representations. 

***Quick Questions:***
- What statistical insight can I gain from this dataset (ex. mean, median, standard deviation, count, min, max)?
- What can I learn about the data frame (number of variables, number of rows/columns)?
- How are the species differentiated by their variables?

# Dataset Background
Downloaded the [Iris dataset](https://www.kaggle.com/datasets/himanshunakrani/iris-dataset) from Kaggle that contains information about petal and sepal dimensions for three species of Iris. 

# Analysis
![count and proportion by species](https://user-images.githubusercontent.com/99365065/190040728-920113b7-5431-4d9e-b88b-73787a186f44.png)


![describe_by](https://user-images.githubusercontent.com/99365065/190040731-42b33557-73ca-4424-b925-e273d9b603a8.png)


![summarise_petalleng](https://user-images.githubusercontent.com/99365065/190040802-8e87eebd-65bf-4926-8240-3e697d3bf589.png)


![summarise_petalwidth](https://user-images.githubusercontent.com/99365065/190040804-1d1adb26-e08a-484b-b12b-b83c6bf998b1.png)


![summarise_sepalleng](https://user-images.githubusercontent.com/99365065/190040805-df8a390f-73ad-4131-8897-9d319fc877a4.png)


![summarise_sepalwidth](https://user-images.githubusercontent.com/99365065/190040806-f218170b-f7aa-4ddf-8919-e4291979cbe1.png)


![summary](https://user-images.githubusercontent.com/99365065/190040807-f614383d-761a-4a4d-abba-43b911c3d3b9.png)


![skim_without_charts](https://user-images.githubusercontent.com/99365065/190040810-3811b371-67e1-43e3-a67c-65eda8943dec.png)


# Visualization
Figure 1 ![Comparing Petal_leng vs Petal_width by Iris](https://user-images.githubusercontent.com/99365065/190041176-77778fd1-5bb6-4d61-be9b-7024576f1485.png)

Figure 2 ![Sepal_leng vs Sepal width by species](https://user-images.githubusercontent.com/99365065/190041185-b95e3cbb-2106-419d-b272-497f9de26ecf.png)

Figure 3 ![Sepal Dimensions by Species_FACET](https://user-images.githubusercontent.com/99365065/190041198-3d5dd4ab-b317-457a-8eb5-f33823088da7.png)

Figure 4 ![Petal Dimensions by Species_FACET](https://user-images.githubusercontent.com/99365065/190041226-3fb8348d-4641-40c9-b4a1-279b1e0da2ce.png)

Figure 5 ![Sepal_leng vs Sepal width by species](https://user-images.githubusercontent.com/99365065/190041239-261a1027-500c-49f3-b353-2d51c0952da7.png)

Figure 6 ![Count size by species](https://user-images.githubusercontent.com/99365065/190043249-06d69c63-f371-42bf-a7fe-71a6cd2f756d.png)


# Observations
- There was a total of 5 columns (sepal_length, sepal_width, petal_length, petal_width, species), 150 rows of unique data values
- For the mean dimensions, <em>Iris virginica</em> had the greatest average for all four features, followed by <em>Iris versicolor</em>, and lastly <em>Iris setosa</em>
- In the data frame there are equal frequencies (50) and proportions (0.33) of each species
- Figure 1 reflects a significant difference in size amongst the species. <em>Iris versicolor</em> and <em>Iris virginica</em> had larger petal dimensions than <em>Iris setosa</em>
- In Figure 2, <em>Iris setosa</em> had a larger sepal width than the other two species and a lower sepal length. <em>Iris virginica</em> and <em>Iris versicolor</em> had very similar sepal dimensions with <em>Iris virginica's</em> dimensions being slightly larger in size 
