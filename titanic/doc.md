# [Titanic](https://www.kaggle.com/c/titanic/data)



## Data Dictionary

| Variable | Definition	  | Key                       |
|----------|--------------|---------------------------|
| survival | Survival 	  | 0 = No, 1 = Yes           |
| pclass   | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
| sex      | Sex 	        |
| Age      | Age in years |	
| sibsp    | # of siblings / spouses aboard the Titanic |
| parch    | # of parents / children aboard the Titanic |
| ticket   | Ticket number 	|
| fare     | Passenger fare 	|
| cabin    | Cabin number 	   |
| embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton |

## Variable Notes

**pclass**: A proxy for socio-economic status (SES)

* **1st** = Upper
* **2nd** = Middle
* **3rd** = Lower

**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of `xx.5`

**sibsp**: The dataset defines family relations in this way...

* **Sibling** = brother, sister, stepbrother, stepsister
* **Spouse** = husband, wife (mistresses and fiancés were ignored)

**parch**: The dataset defines family relations in this way...

* **Parent** = mother, father
* **Child** = daughter, son, stepdaughter, stepson
    > _Some children travelled only with a nanny, therefore parch=0 for them._

## Manual changes:

**sex**: o sexo do passageiro:

* **0** - male
* **1** - female

**embarked**: o local do embarque:

* **0** - nulo
* **1** - C = Cherbourg
* **2** - Q = Queenstown
* **3** - S = Southampton

## Info print

| #  | Column       |Non-Null Count| Dtype  | Type         |
|----|--------------|--------------|--------|--------------|
| 0  | passengerid  |891 non-null  | int64  | Qualitative  |
| 1  | pclass       |891 non-null  | int64  | Qualitative  |
| 2  | name         |891 non-null  | object | Qualitative  |
| 3  | sex          |891 non-null  | int64  | Qualitative  |
| 4  | age          |714 non-null  | float64| Quantitative |
| 5  | sibsp        |891 non-null  | int64  | Quantitative |
| 6  | parch        |891 non-null  | int64  | Quantitative |
| 7  | ticket       |891 non-null  | object | Qualitative  |
| 8  | fare         |891 non-null  | float64| Quantitative |
| 9  | cabin        |204 non-null  | object | Qualitative  |
| 10 | embarked     |891 non-null  | int64  | Qualitative  |
| 11 | survived     |891 non-null  | int64  | Qualitative  |