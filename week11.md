## Cluster Analysis
- is an unsupervised learning -> develop predictive model based on both input and output data
- K-Means
- DB-Scan

### Clustering
- in general a grouping of objects -> obj in a group (cluster) are similar and different (unrelated to) the obj in other groups
![](https://media.discordapp.net/attachments/1014398974649708624/1087629055026790420/image.png)

### Types of Clustering
#### Well-Seperated

#### Center-Based

#### Density-Based

### K-Means
- **"k"** groups (number of clusters)
- the objective is to **minimize the sum of distances** of the points to their respective **centriod**
![](https://media.discordapp.net/attachments/1014398974649708624/1087629702493114378/image.png)
- aka. "Lloyd's algorithm"
	- select K points as the initial centroids
	- repeat
	- form K clusters by assigning all points to the closet centriod
	- recompute the centriod of each cluster
	- until the centriods don't change
![](https://media.discordapp.net/attachments/1014398974649708624/1087630174415237120/image.png?width=1124&height=685)

#### Finding "K" -> Elbow Method
![](https://media.discordapp.net/attachments/1014398974649708624/1087633936076771408/image.png?width=598&height=685)
- k = 3 is at "elbow point"

#### Limitations
- sizes
![](https://media.discordapp.net/attachments/1014398974649708624/1087635327193186325/image.png)
- density
![](https://media.discordapp.net/attachments/1014398974649708624/1087635470114099280/image.png)
- non-globular shapes
![](https://media.discordapp.net/attachments/1014398974649708624/1087635622111490058/image.png)

### DBSCAN
- **DBSCAN** is a **Density-Based Clustering**
- partition points into dense regions seperated by not-so-dnese regions
- characterization of points (กำหนดแค่ MinPts, Eps -> then you'll get core points, border points) 
	- **core points** -> if it has more than a specified number of points (MinPts) within Eps (epsilon)
	- **border point** -> has fewer than MinPts within Eps, but is in the neighborhood of a core point
	- **noise point**
![](https://media.discordapp.net/attachments/1014398974649708624/1087637726574161950/image.png)
- probably gonna be on exams since he emphasize on this so much
![](https://media.discordapp.net/attachments/1014398974649708624/1087638328851046460/image.png?width=1235&height=685)
