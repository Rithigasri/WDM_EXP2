# EXPERIMENT 02: GENERATING ASSOCIATION RULES FOR EMPLOYEE DATASET USING APRIORI ALGORITHM
## DATE: 17.02.2024
## AIM: 
To generate associate rules for the employee dataset using Apriori Algorithm.
## DESCRIPTION:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
## PROCEDURE:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

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
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
## OUTPUT:
### BUYING DATASET:
![output2a1](https://github.com/Rithigasri/WDM_EXP2/assets/93427256/8fafd08e-150f-4c3f-b14f-f09af8bd792e)
### BANKING DATASET:
![output2b1](https://github.com/Rithigasri/WDM_EXP2/assets/93427256/b0ef0ebc-dc02-40a5-99d9-d554d842fc60)
### EMPLOYEE DATASET:
![output2c1](https://github.com/Rithigasri/WDM_EXP2/assets/93427256/650c8f2a-e35e-441f-8ecd-cbc3f6908344)


## PROCEDURE FOR ASSOCIATION RULES:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

## OUTPUT:
### BUYING DATASET:
![output2a2](https://github.com/Rithigasri/WDM_EXP2/assets/93427256/5174ea4e-e0cc-4dba-91ff-dfd63c3da8a9)
### BANKING DATASET:
![output2b2](https://github.com/Rithigasri/WDM_EXP2/assets/93427256/ace02a58-1891-4c33-9249-0d6bdc1f8b07)
### EMPLOYEE DATASET:
![output2c2](https://github.com/Rithigasri/WDM_EXP2/assets/93427256/7a24c6d3-0e27-4b50-9fed-54ece8c5ee1e)

## RESULT: 
Thus, generation of association rules using apriori algorithm is executed succesfully.
