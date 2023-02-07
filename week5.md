## Introduction to Machine Learning

### AI Techniques
- Rule-Driven
- **Data-Driven**
	- Supervised (มี output)
		- Regression (ตัวเลขต่อเนื่อง)
			- Linear Regression
			- Polynomial Regression
		- Classification (ทำนายกลุ่ม)
			- Logistic Regression
			- Naive Bayes
			- Decision Tree
			- K-NN
			- Neural Network
	- Unsupervised (ไม่มี output)
		- K-Mean
		- DBSCAN

### Model
- input x -> output y
- **Function Mapping**
![](https://media.discordapp.net/attachments/1014398974649708624/1072400183515697202/image.png?width=1440&height=685)

### Supervised Learning
![](https://media.discordapp.net/attachments/1014398974649708624/1072401283794870373/image.png?width=1440&height=579)

### Unsupervised Learning
![](https://media.discordapp.net/attachments/1014398974649708624/1072401435125350420/image.png?width=1440&height=537)

### Evaluation

#### Model Performance
- Regression
	- **RMSE**
	- MAPE
	- MAE
- **Classification !!!**
	- **Accuracy**
	- Precision
	- Recall
	- F1

#### Root Mean Square Error (RMSE)
![](https://media.discordapp.net/attachments/1014398974649708624/1072402178188255242/image.png?width=1440&height=587)

#### Other Regression Measurement Methods
![](https://media.discordapp.net/attachments/1014398974649708624/1072402621316477008/image.png?width=865&height=685)

### Classification Evaluation

#### Confusion Matrix !!!(ออกสอบ สำคัญ)
![](https://media.discordapp.net/attachments/1014398974649708624/1072403317910687754/image.png)

#### Accuracy
![](https://media.discordapp.net/attachments/1014398974649708624/1072403452669476874/image.png?width=1440&height=574)

#### Other Classification Measurement Methods
![](https://media.discordapp.net/attachments/1014398974649708624/1072403620051550208/image.png?width=1440&height=634)

### Train-Test Split
![](https://media.discordapp.net/attachments/1014398974649708624/1072407869279977493/image.png?width=1440&height=613)
- not vary enough

### K-Fold Cross-Validation
![](https://media.discordapp.net/attachments/1014398974649708624/1072408296629207100/image.png?width=1291&height=685)
- K is either 3,4,5,10
- disadvantage: computationall expensive

### Scikit Learn
- simple and efficient tools for predictive data analysis
- open source

#### Major Steps for Train-Test Split
1. to split train-test
	- `train_test_split(X,y)` -> X_train, y_train, X_test, y_test
2. to create a model
	- `{technique}.fit(X_train, y_train)`
3. to predict
	- `{model}.predict(X_test)` -> y_pred
4. to evaluate
	- `{evaluation}(y_test, y_pred)` -> value

#### To Deploy
- we dont select one or another data_set (from train,test) model in K-fold
	- its just a techniques that ensures the performance of the model
- we use all of the data to deploy and use in real-world

### Regression
![](https://media.discordapp.net/attachments/1014398974649708624/1072414297189253200/image.png?width=1440&height=668)
#### Feature Selection
![](https://media.discordapp.net/attachments/1014398974649708624/1072415289897144360/image.png?width=1440&height=587)
- select the features that have the correlation close to 1 or -1

### Classification
#### Decision Tree
