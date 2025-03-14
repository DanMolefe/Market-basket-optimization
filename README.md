**Purpose:** I have been provided with a dataset of 7,501 transactions from a popular commodity shop. My goal is to identify the most suitable product 

pairs for the 'Buy 1 Get 1' offer, as determined by the shop owner. To achieve this, I have applied the Apriori algorithm to identify the most 

appropriate item pairs based on transaction patterns

**Algorithm:** To solve the above problem, I used the Apriori algorithm, which is widely used for frequent itemset mining and association rule learning. 

Here, **support**, **confidence**, and **lift** are key metrics that help assess the strength and relevance of the associations (rules) discovered in the data. 

A brief description of each metric is given below.

* $\color{green}{\text{Support}}$ tells you how frequent the items are in the dataset. 

* $\color{green}{\text{Confidence}}$ tells you how often items on the right-hand side (Y) are bought when the items on the left-hand side (X) are bought.

* $\color{green}{\text{Lift}}$ tells you how much more likely X and Y are to be bought together compared to if they were independent.

* Return to main page (https://github.com/DanMolefe)
