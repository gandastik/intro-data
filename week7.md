
## Classification

### Decisition Tree: Construction (no exam)
![](https://media.discordapp.net/attachments/1014398974649708624/1077472369989386310/image.png?width=1303&height=685)

## Recommender System
- user profile
	- gender
	- age
	- where you live etc.
- collaborative system
	- behavior
- product features
	- category
	- description
- knowledge base

### Evaluation
- MAE
- Top-K Precision
	- pickup K items from the recommended list
	- count how many actual items that users interact
	- Top-K = N / K
- Area Under ROC Curve (AUC)
![](https://media.discordapp.net/attachments/1014398974649708624/1077480246523215922/image.png)
![](https://media.discordapp.net/attachments/1014398974649708624/1077480411485180004/image.png)
![](https://media.discordapp.net/attachments/1014398974649708624/1077480617232568341/image.png?width=1213&height=685)
![](https://media.discordapp.net/attachments/1014398974649708624/1077480664330412032/image.png?width=1235&height=685)

#### Decide to evaluate?
- firstly
	- use Top-K Precision
	- check the accuracy of top recommended items
	- close to the real situation when the number of recommend items are limited
- secondly
	- use AUC
	- check the overall performance of an alogrithm

### Collaborative Recommendation (ออกสอบ final)
- **user**-based collaborative filtering
![](https://media.discordapp.net/attachments/1014398974649708624/1077481978590400624/image.png)

![](https://media.discordapp.net/attachments/1014398974649708624/1077484223113482310/image.png?width=1134&height=685)

![](https://media.discordapp.net/attachments/1014398974649708624/1077484288909508698/image.png?width=1169&height=685)

![](https://media.discordapp.net/attachments/1014398974649708624/1077494739118592021/image.png?width=523&height=684)
