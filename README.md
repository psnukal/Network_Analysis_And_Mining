# Network_Analysis_And_Mining

1.Implementation (6 marks) :

a. Make a list of characters in the novel. You need to decide whom to include. For
example, for Mahabharata, there is no point in including a character
representing a random soldier (;-

b. Extract a social graph of the manually identified characters in the text ( as shown
in the hands-on session). To do this, you need to use a co-occurrence algorithm
as discussed and shown in the demo in class. Also, plot the graph using networkx
(it may be a very dense graph and that is okay).

c. Calculate the four types of centrality of main protagonists i.e. degree,
betweenness, closeness, PageRank . (Ref : Unit 1 – centrality analysis)

d. Calculate the global clustering coefficient of your graph and local clustering
coefficient of the main protagonist nodes. (Ref : Unit 2 – Measures of cohesion)

e. Detect communities using the following methods: (Ref : Unit 2 – Measures of
cohesion)<br>
i. K - clique (percolation method)<br>
ii. Louvain community detection<br>
iii. Girvann Newman<br>

f. Find the degree distribution, average shortest path, and size of the largest
component. Also create equivalent generative models to compare against the
social graph that you extracted (Ref: unit 3 - Generative models)<br>
i. G(n,p) and G(n,m) generated graph<br>
ii. Preferential attachment<br>
iii. Small-world model<br>


<br>
<br>
<br>
<br>
2. Analysis (4 marks)
Theme of the analysis: What you know of the story and is it matching with what you got
from your network analysis? Have you got any insight to offer ?

a. Who are the protagonists as per your analysis? If the 4 centralities are not
having high correlation, how do you interpret them?

b. What do the clustering coefficients, discovered communities, extracted ego
network of protagonists and average shortest path tell you about the dynamics
in the story? How is clustering coefficient related to transitivity of nodes?

c. Compare all the generated graphs (from (f)) to the actual graph. Is there a
difference, and if yes, what can it be attributed to? Also, analyze the differences
between the 3 generated graph’s attributes.

d. Feel free to do any appropriate visualization using Gephi only to substantiate
your analysis














