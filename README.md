# network-growth-models


[[This project is still under progress.]]

This folder contains simulations of network models, with focus on preferential attachment

These simulations show that different models produce networks with different characteristics. The goal here is to understand the dynamics of network growth and to look (if possible) for unexpected results.

Initially, a small growth simulation with a graph will be useful to initially visualize the model.  
Finally, a large sample of network will be constructed so to verify that the previously obtained results can be considered as reliable. The two-sample Kolmogorov-Smirnov test is used to determine whether the actual distribution of degrees is a power-law distribution (i.e. what it is expected to be according to the Alber-Barabasi model). Under the null hypothesis of the K-S test the two distributions are identical, so if the null hypothesis is rejected the degree distribution of the network will not have a power-law distribution.




Bibliography:

Albert, R., Jeong, H., & Barabasi, A. (2011). Error and attack tolerance of complex networks. The Structure and Dynamics of Networks. 

Albert, R., & Barabasi, A. (2002). Statistical mechanics of complex networks. Reviews Of Modern Physics, 74. 

Barabasi, A. (1999) Emergence of Scaling in Random Networks. Science, 286(5439), 509-512. 
