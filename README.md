## Topsis-Pulkit-102003619
**T**echnique for **O**rder **P**reference by **S**imilarity to **I**deal
**S**olution (TOPSIS) originated in the 1980s as a multi-criteria decision
making method. It is based on the fundamental premise that the best solution has the shortest distance from the positive-ideal solution, and the longest distance from the negative-ideal one. Alternatives are ranked with the use of an overall index calculated based on the distances from the ideal solutions.

## Installation
```pip install Topsis-Pulkit-102003619```

# OR alternatively use 
```python -m pip install Topsis-Pulkit-102003619```

## How to use it?

Topsis-Pulkit-102003619 can be used as 

## In Terminal
*Provide the file containing data in CSV Format, Provide corresponding weights and Impacts*
```topsis data.csv "1,0.5,1,0.5" "+,-,+,-" Output.csv```

<br>

## Sample dataset

The decision matrix (`a`) should be constructed with each row representing a Model alternative, and each column representing a criterion like Fund Name , P1 ,P2 , P3 , P4 , P5.

Model | Correlation | R<sup>2</sup> | RMSE | Accuracy
------------ | ------------- | ------------ | ------------- | ------------
M1|	0.8	|0.64	|3.5	|37.5	|10.61
M2|	0.86	|0.74	|3.4	|42.2	|11.8
M3|	0.69	|0.48	|5.7	|70	|19.22
M4|	0.65	|0.42	|5.7	|65.5	|18.07
M5|	0.9	|0.81	|6.6	|39.1	|11.85
M6|	0.76	|0.58	|4	|53.5	|14.71
M7|	0.69	|0.48	|6.2	|51.3	|14.67
M8|	0.65	|0.42	|6	|50.2	|14.32



<br>

## Output

```
Row_NO	Performance_score	Rank
1	    0.436737	         7
2	    0.389937	         8
3	    0.565650             4
4	    0.590487	         3
5	    0.522924	         5
6	    0.451344	         6
7	    0.637889	         1
8	    0.635536	         2

```
<br>
The rankings are displayed in the form of a table using a package 'tabulate', with the 1st rank offering us the best decision, and last rank offering the worst decision making, according to TOPSIS method.

## License

© 2023 Pulkit

This repository is licensed under the MIT license. See LICENSE for details.