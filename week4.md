	week3: google collab basics pandas and numpy

## Basic Statistics

### Scale of Data

![](https://media.discordapp.net/attachments/1014398974649708624/1069865659695108096/image.png)

- **Ratio data**: true zero exists eg. money, distance, weight 
- **Interval data**: no true zero eg. temperature 0 C != 0 F, Date
- **Ordinal data**: ordered categories (rankings, order, or scaling)
- **Nominal data**: categories (no ordering or direction)

![](https://media.discordapp.net/attachments/1014398974649708624/1069866819273363487/image.png?width=1258&height=685)

### Central Tendency
- **Arithmatic Mean**
- **Harmonic Mean**
- **Mode**: ฐานนิยม
- **Median**: มัธยฐาน

### Measure of Dispersion
- **Range**: Max - Min
- **Variance**: 
![](https://media.discordapp.net/attachments/1014398974649708624/1069867910585131048/image.png)
- **Standard Deviation**: square root of variance

### Distribution
- **Normal distribution**
- **Standardize** -> range -3 -2 -1 0 1 2 3
![](https://media.discordapp.net/attachments/1014398974649708624/1069868532143226931/image.png)

### Correlation
- **Positive Correlation**
- **Negative Correlation**
![](https://media.discordapp.net/attachments/1014398974649708624/1069869012542050345/image.png?width=1280&height=685)
- **Pearson Correlation**
![](https://media.discordapp.net/attachments/1014398974649708624/1069869623257870366/image.png)


## Data Processing
- Data is dirty because
	- incomplete data comes from
		- n/a data value when collected
	- noisy data comes from the process of data
		- collection, entry, transmission
	- inconsistent data comes from
		- different data sources
		- functional dependency violation

### Data Cleaning
#### Missing Data
- equipment malfunction
- data no entered due to misunderstanding
- **missing data may need to be infered**
- deal with missing data
	- deleting/ignoring rows with missing values
		- simplest solution: not use the records with missing values
	- filling in the values
		- create a new category that will represent 'unknown'
		- mode, mean to fille
- **noisy data**
	- random error or variance in a measure variable
	- use interquartile to remove noisy data: IQR = Q3 - Q1

- **Imputation**
	- filling miassing values
	- numerical imputation 
- handling outliers
	- **drop** or **cap**

### Bining
- make the model more robust and prevent overfitting
- eg. 0-30 -> low, 31 - 70 -> mid, 71 - 100 -> high

### One-Hot encoding
- flag columns and assigns to 0 or 1

### Scaling
- **Normalization** (min-max): Xnorm = (X - Xmin)/(Xmax - Xmin)
- **Standardization** (z-score): reduces the effect of the outliers in the feature

## Data Exploration
### Data Table
![](https://media.discordapp.net/attachments/1014398974649708624/1069879823427702834/image.png)

### Histogram
![](https://media.discordapp.net/attachments/1014398974649708624/1069879940205518868/image.png)

#### Box plot
![](https://media.discordapp.net/attachments/1014398974649708624/1069879982446362684/image.png)

#### Scatter Plot
#### Heatmap

### Tools
- Matplotlib
- pandas plot
- seaborn