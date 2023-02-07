# Determining the most influential nodes using the TOPSIS method

## Summary:

Identifying influential nodes is among important questions, applications such as accelerating fact spreading and controlling rumors and diseases, numerous methods have been proposed to identify influential nodes in complex networks, measuring the centrality of nodes in process-based propagation.

In this project, a new method is developed to evaluate the importance of nodes in complex networks based on the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) approach. TOPSIS is first applied to identify the influential nodes of the complex network. This open-themed network. Different ways of looking at several different centralities measure several attributes of complex networks in TOPSIS applications.

TOPSIS is used to aggregate multiple attributes to obtain their scores, importance of each node's node. However, you are not limited to one centrality measure. Consider different centrality measures, since each centrality measure has its own centrality measure disadvantages and limitations. Then use the susceptible index (SI) model to evaluate performance.

Finally, we propose using the K-Means algorithm to find clusters.
The emphasis is on the top K influential nodes detected by the TOPSIS method.


##  The TOPSIS method ??
The Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) is a method used to rank alternatives in decision-making. It is based on the concept of "ideal solution" and "anti-ideal solution". The steps for applying TOPSIS to identify the top influential nodes are as follows:

1. Define the criteria: Identify the relevant attributes or criteria for the decision problem.

2. Normalize the data: Convert all data into a scale of 0 to 1 for each attribute.

3. Determine the weight of each attribute: Assign a weight to each attribute based on its relative importance.

4. Calculate the similarity index: Calculate the similarity of each alternative to the ideal solution and anti-ideal solution.

5. Rank the alternatives: Order the alternatives based on their similarity index, with the highest being the most preferred.

6. Identify the top influential nodes: The top influential nodes can be determined as the alternatives with the highest similarity index or the ones closest to the ideal solution.

Note: The TOPSIS method assumes that all criteria have the same importance. If this is not the case, the criteria should be weighted appropriately.

## The SI model ?

The SI model, in the context of epidemiology and infectious disease dynamics, refers to the Susceptible-Infected model. It's a basic mathematical model used to describe the spread of an infectious disease in a population. The model considers individuals to be either susceptible (not yet infected), infected (able to spread the disease), or recovered/removed (no longer able to spread the disease). The model tracks the flow of individuals from the susceptible to the infected category, and from the infected to the recovered/removed category, over time. The SI model helps researchers to understand the dynamics of disease spread and inform public health interventions.
