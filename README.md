                                        # CryptoClustering-Module 19 Challenge
This challenge was meant to help us apply what we have learned in class about unsupervised machine learning which is used to make predictions and find trends using unlabeled data. In this particular challenge, I have tried to do market prices change analysis of crypto currencies across times. To do this, I have imported the necessary libraries, loaded the csv data, read the data into DF, visualize the data in a graph, transform the data, make line and scatter graphs and PCA analysis. See details below.


* Import functions and reading 

![image](https://user-images.githubusercontent.com/117956888/235785543-04adcb34-aa73-4c4a-beac-f6e954869973.png)

* Visualizing what is in the data:

![image](https://user-images.githubusercontent.com/117956888/235785748-0586127e-3e5f-4b76-8946-2be127bb2a9e.png)

* Preparing and normalizing the data using StandadardScaler

![image](https://user-images.githubusercontent.com/117956888/235786048-aa07982c-852c-4712-b979-be07fc4897fc.png)

* Finding best value for k using orginal data and inertia

![image](https://user-images.githubusercontent.com/117956888/235786461-c0042e2c-235f-4eb8-a1ec-bd864cf6422b.png)

* Identifying the optimal value for k using the elbow method in a line graph (sharp decrease in inertia)

![image](https://user-images.githubusercontent.com/117956888/235786780-a7993fbc-4f68-4476-af73-1eb689cd88cc.png)

* Scatter plot using the best K value identifed from the line graph

![image](https://user-images.githubusercontent.com/117956888/235787135-14f63f05-8a71-42a2-b3aa-11ff4cff759d.png)

* Model for PCA analysis and identfying varaince coponent

![image](https://user-images.githubusercontent.com/117956888/235787349-1f6d681c-cc6a-4459-b71b-2991b71e8fde.png)

* PCA DataFrame

![image](https://user-images.githubusercontent.com/117956888/235787628-85f5a269-fc83-4309-9b9a-0524ef4d52e5.png)

* Line graph using PCA data for elbow method of identifyig best # of classes

![image](https://user-images.githubusercontent.com/117956888/235787944-50971bfa-df55-40d4-bfbf-569c5649661e.png)

* Scatter plot using PCA data

![image](https://user-images.githubusercontent.com/117956888/235788084-b0a6b167-a5c3-4551-b14b-8083ad59fe0d.png)

Conclusion: based on the composite line charts, the optimal value of k is 4. However, in the scatter plot, we have seen a better separation of clusters in the PCA analysis (please refer to composite graphs in jupyter notebook).




















