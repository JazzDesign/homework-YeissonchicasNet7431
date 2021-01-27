# Net7431 NA Class 2020
## Homework developed by Yeisson Chicas

Network science and Graph Learning Homework 2020.

You will find the Python Notebook with this information:



### Question 2: Social Network Analysis with the Facebook100 Dataset
The smallest network (Caltech) has 762 nodes in the largest connected component (LCC), and the largest has more than 40000 nodes in the LCC.
Lets use three networks from the FB100: Caltech (with 762 nodes in the LCC), MIT (which has 6402 nodes in the LCC), and Johns Hopkins (which has 5157 nodes in the LCC).

(a) For these three networks plot the degree distribution for each of the three net- works that you downloaded. What are you able to conclude from these degree distributions?

(b) Compute the global clustering coefficient and mean local clustering coefficient for each of the two networks. Also compute the edge density of each network. Should either of these networks be construed as sparse?

(c) For each network, also draw a scatter plot of the degree versus local clustering coefficient. Based on these calculations as well as your previous ones, are you able to draw any conclusions about any similarities or differences between the tree networks? What other observations can you make?

### Question 3: Social Network Analysis with the Facebook100 Dataset
(a) Using the FB100 networks, investigate the assortativity patterns for three vertex attributes: (i) student/faculty status, (ii) major, (iii) vertex degree, and (iiii) dorm. Treat these networks as simple graphs in your analysis.

### Question 4: Find missing labels with the label propagation algorithms

(b) Implement in python the label propagation algorithm, please consider pytorch1 and networkx2 for the development of your algorithm.

(c) Choose a network from The Facebook100 dataset and randomly select 10%, 20% and 30% of of the node attributes of the network to be remove. Use the label propagation algorithm you implemented to recover the missing attributes. perform this operation for each of the following attributes : the ”dorm”, ”major”, ”gender”.

(d) For each cases of the following percentage of missing attributes: 10%, 20% and 30% and for each of the following attributes: the ”dorm”, ”major”, ”gender” show the mean absolute error and accuracy [5] of the label propagation algorithm as in the example provided in Table 1 for the Duke university Facebook network.

(e) Conclude on the accuracy of the label propagation algorithm for the different labels, could you explain why there is such difference in accuracy between each labels ?



[Notebook Link Google Colabs](https://colab.research.google.com/drive/1wGo_iApd2ipglidL93-ZwyfgHkCNCFKv?usp=sharing)
