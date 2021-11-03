# Bonus Part Discussion
**Name:** Max Boholm

For the Bonus, I have done the following:
1.    Identify the likelihood for characters being in initial position of a word, i.e. the characters' *initiality*.
2.    Identify the "semantics" of every character, i.e. their embeddings. 
3.    Reduce the 200 dimension embeddings to two dimensions (an arbitrary choice, but it is easier to plot).
4.    Compute Pearsons correlation coefficient *r* between *intiality*, on the one hand, and *dimension 1* or *dimension 2*, on the other.
5.    Identify the characters with the highest dimensionality (*initiality* > 0.9); and those with the lowest (*initiality* < 0.1); and then scatterplot those in relation to dimension 1 and dimension 2.

This analysis find *no* relationship between the representation of characters in embeddings and their initiality: *r* for *initiality* and dimension 1 is 0.016; and *r* for *initiality* and dimension 2 is -0.017. That is, the variables are almost completely unrelated. 

From the scatter plot a similar conclusion can be drawn. There is no tendence of characters with *high* initiality or *low* intiality to scatter towards any value of the dimensions. Thus, the visualization confirms the previous conclusion or the variables unrelatedness.
