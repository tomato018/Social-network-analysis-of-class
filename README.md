# Social-network-analysis-of-class


Social network anlaysis has found utility is institutional, classroom and analyses of networked data in socially-based educational games. However, the utility of the method largely rests on being able to ascribe meaning to the **structure of the network**. Without meaningful interpretation of structure, there is no added value to a networked model. A successful networked graph model can simply reflect student characterstics. Understanding measures of centrality and network structure in SNA are therefore an important, though difficult, aspect of the method. As with all SNA work, the vocabulary can be daunting though the ideas are relatively intuitive.

In this project, I generated and analyzed three social networks based on three different measures:
1. Who does a student get on with in the class?  
2. Who is a student's best friends in the class?  
3. Who would a student prefer to work with? 

To complete the analysis, I used centrality, closeness measures and clusters within the network.

The data was used via [the Index of Complex Networks](https://icon.colorado.edu/#!/). 

## Packages Required
```
install.packages("igraph")
```

## Datasets

I used three datasets: get.on.with.csv, best.friends.csv, work.with.csv. Each dataset has variables including layerID, from, to, and gender.from.

## Procedure

1. Upload three csv files as data frames.
2. Prepare to create EDGE and VERTEX in data wrangling steps.
3. Show disciplinary action count for students who are connected.
4. Create a visualization graph for each dataset.
5. Measure centrality, betweeness, and clustering for each graph. 

Graph visualization:
* [Get on with](https://github.com/tomato018/Social-network-analysis-of-class/blob/master/get_on_with.png)
* [best friends](https://github.com/tomato018/Social-network-analysis-of-class/blob/master/best_friends.png)
* [Prefer to work with](https://github.com/tomato018/social-network-analysis/blob/master/prefer%20to%20work%20with.pdf)

## Author

[Meijuan Zeng](https://github.com/tomato018), MS Student in Learning Analytics at Columbia University
