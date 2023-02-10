# Entropy_calculation_in-Decision_Tree
Decision trees are a nonparametric supervised learning set of rules for type and regression duties. It has a hierarchical tree shape together with a root node, branches, internal nodes, and leaf nodes.
[DECISION TREE.docx](https://github.com/Gagan-Patel/Entropy_calculation_in-Decision_Tree/files/10710558/DECISION.TREE.docx)
![Screenshot (22)](https://user-images.githubusercontent.com/122751229/218181269-aeccb469-20e8-4633-a0e7-893b23bc5f69.png)

For getting accurate data at the end we havce to split the nodes of decision tree.Node splitting is the process of dividing a node into multiple sub-nodes to create relatively pure nodes

We can do this with the hepl of Entropy and informatoipon gain.

Entropy is the opposite of knowledge, A high knowledge of data leads to low entropy. which measures the impurity of the sample values.
Formula for entropy
Entropy=-M/(Total )log2(M/(Total )) −N/(Total )log2(N/(Total ))

knowledge, A high knowledge of data leads to low entropy. which measures the impurity of the sample values

For example:
What is the entropy for a bucket with a ratio of four red balls to ten blue balls? 
Total number of balls =14
Red balls =4
Blue balls 10
Solution:
-4/14 log2(4/14)- 10/14 log2(10/14)= 0.863
[entropy.xlsx](https://github.com/Gagan-Patel/Entropy_calculation_in-Decision_Tree/files/10710882/entropy.xlsx)

python code for entropy is:

import numpy as np
-(((4/14) * np.log2(4/14) + (10/14) * np.log2(10/14)))
=0.863120568566631

