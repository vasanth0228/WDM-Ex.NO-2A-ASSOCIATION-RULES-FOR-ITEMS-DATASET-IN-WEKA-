# WDM-Ex.NO-2A-ASSOCIATION-RULES-FOR-ITEMS-DATASET-IN-WEKA-
### Aim:
To Find the Association Rules for Buying dataset.
#### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered in databases using different measures of interestingness. In market basket analysis association rules are used and they are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
## Creation of Buying Table:
#### Procedure:
1)	Open Start  Programs  Accessories  Notepad
2)	Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
  	G40,low,no,fair,yes
  	L20,high,yes,excellent,yes
  	G40,high,no,fair,yes
  	L20,low,yes,excellent,no
  	G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
  	L20,medium,yes,fair,yes
  	G40,high,yes,excellent,yes
```
4)	After that the file is saved with .arff file format.
5)	Minimize the arff file and then open Start  Programs  weka-3-4.
6)	Click on weka-3-4, then Weka dialog box is displayed on the screen.
7)	In that dialog box there are four modes, click on explorer.
8)	Explorer shows many options. In that click on ‘open file’ and select the arff file
9)	Click on edit button which shows buying table on weka.
 
Training Data Set  Buying Table
<img width="730" height="786" alt="image" src="https://github.com/user-attachments/assets/fe39fa3c-e5fe-459c-a376-9dd6d5d56a1b" />

### Procedure for Association Rules:
1)	Open Start  Programs  Weka-3-4  Weka-3-4
2)	Open explorer.
3)	Click on open file and select buying.arff
4)	Select Associate option on the top of the Menu bar.
5)	Select Choose button and then click on Apriori Algorithm.
6)	Click on Start button and output will be displayed on the right side of the window.
 
 <img width="1060" height="851" alt="image" src="https://github.com/user-attachments/assets/51f8ee80-b3c4-4fe8-877d-d7ccc0ed66c7" />


### Output:

 <img width="923" height="560" alt="image" src="https://github.com/user-attachments/assets/8e87b425-325c-493e-86b3-1780e423c255" />

 
<img width="942" height="570" alt="image" src="https://github.com/user-attachments/assets/d723d80d-9428-45b6-bc84-a1495c4ae13e" />
































### Result:
Thus, this program has been successfully executed.
