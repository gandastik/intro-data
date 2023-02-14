## Classification
- Decision Tree
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors
- Artificial Neural Network

### Decision Tree
![](https://media.discordapp.net/attachments/1014398974649708624/1074934365517262848/image.png?width=1440&height=595)

### Logistic Regression
![](https://media.discordapp.net/attachments/1014398974649708624/1074956484124876860/image.png?width=1440&height=627)

### Naive Bayes
![](https://media.discordapp.net/attachments/1014398974649708624/1074956549786710096/image.png?width=1380&height=685)

### K-Nearest Neighbors
![](https://media.discordapp.net/attachments/1014398974649708624/1074958415010476103/image.png?width=1419&height=685)

![](https://media.discordapp.net/attachments/1014398974649708624/1074958454759899217/image.png?width=1322&height=685)

### Artificial Neural Network
![](https://media.discordapp.net/attachments/1014398974649708624/1074959401045213265/image.png?width=1432&height=685)

#### Feed Forward
#### Backpropagation
#### Weight Updated
#### Chain Rule with Partial Derivatives


## Classification Evalution
> the highlight of all lectures
- TP | TN | FP | FN
- Accuracy
	- ไม่ใช้คำกลางๆที่ใช้วัด "ความแม่นยำ" ของ model -> "performance"
- Precision | Recall | F1
- TPR | FPR | ROC | AUC
- Confusion Matrix for Multi-Class

#### Step
- Test set
- Classifier Did (สิ่งที่ทำนายออกมา)
- Correct Classification

### Evaluation Methods
![](https://media.discordapp.net/attachments/1014398974649708624/1074936748620136538/image.png?width=1440&height=615)

### TP | TN | FP | FN
- positive - we predict the **disease is present**
- negative - we predict the **disease is NOT present**

- **"ถ้าจะตรวจอะไร ให้เคสนั้นเป็น positive ไว้"**

- TP - True Positive "ทายถูก ว่า เป็น"
- TN - True Negative "ทายถูก ว่า ไม่เป็น"
- FP - False Positive "ทายไม่ถูก ว่า เป็น"
- FN - False Negative "ทายไม่ถูก ว่า ไม่เป็น"

![](https://media.discordapp.net/attachments/1014398974649708624/1074938127308836906/image.png)

### Accuracy
- ![](https://media.discordapp.net/attachments/1014398974649708624/1074944696272572466/image.png)
- im-balanced class
	- ทำให้ accuracy ไม่ค่อย make sense
	- need another technique

### Precision | Recall | F1
- ![](https://media.discordapp.net/attachments/1014398974649708624/1074946541497896990/image.png?width=1440&height=491)

- ![](https://media.discordapp.net/attachments/1014398974649708624/1074947224519311391/image.png?width=1276&height=685)

- F1 (F-Measure)
![](https://media.discordapp.net/attachments/1014398974649708624/1074948414820851763/image.png?width=1440&height=668)

#### Multi-Class
- ![](https://media.discordapp.net/attachments/1014398974649708624/1074949687251050549/image.png?width=1440&height=664)

### TPR | FPR | ROC | AUC

#### TP Rate & FP Rate
![](https://media.discordapp.net/attachments/1014398974649708624/1074950127535538176/image.png?width=1440&height=685)

![](https://media.discordapp.net/attachments/1014398974649708624/1074950967587508254/image.png?width=1333&height=685)

#### ROC Curve
![](https://media.discordapp.net/attachments/1014398974649708624/1074952038468816947/image.png?width=927&height=685)

#### AUC: Area Under the ROC Curve
![](https://media.discordapp.net/attachments/1014398974649708624/1074952255213674576/image.png?width=1440&height=631)

### Confusion Matrix for Multi-Class
![](https://media.discordapp.net/attachments/1014398974649708624/1074952655442563092/image.png)

![](https://media.discordapp.net/attachments/1014398974649708624/1074952712493477938/image.png?width=1440&height=568)

### Summary Evaluation Methods
![](https://media.discordapp.net/attachments/1014398974649708624/1074953006052818954/image.png?width=1440&height=643)


### Exam
- 3 hours 
- เนื้อหาข้อสอบถึงอาทิตย์นี้เท่านั้น
- open book + calculator allowed (ติดรูท, เศษส่วนได้)