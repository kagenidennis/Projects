# Projects
Repository containing portfolio of computer science projects completed by me for academic, self-learning, and fun.

# Contents
## Machine Learning
1. MNIST
2. Principal Landmarks: Took multiple photos of my favorite landmark in Retiro, Buenos Aires and used principal component analysis to project the images into a 2D representation. Reconstructed the images from their low-dimensional representation
3. Machine Learning Fashionista 1.0: Comparing the Linear Discriminant Analysis (LDA) and Principal Component Analysis (PCA) 2D projections of the ImageNet dataset that contains examples of Men's and Women's clothing
4. Machine Learning Fashionista 2.0: Revisiting the ImageNet dataset to compare the performace of support vector classifiers using multiple kernels and deep neural networks using transfer learning.
5. Gaussian Process: Estimated the temperature over the time of day and time of year for the Yosemite Village yearly weather dataset; compared the mean squared error (MSE) of my Gaussian process with a previous implementation of a linear parameter model.
6. Topic Modeling: Downloaded Peter-Pan as Plain Text; performed data-preprocessing to transform the book into a suitable format for the Latent Dirichlet Allocation (LDA) model contained in scikit.learn; trained an LDA model on the corpus and printed the first ten words of the ten most common topics

## Statistical Inference
1. Causal Inference: Replicated Figure 8 from [https://gking.harvard.edu/files/counterf.pdf](this) paper that considers the implications of adding an interaction term (logdead * untype4) to the basic model.
2. Regression and Bootstrapping

## Computational Statistics
1. Cost of Basic Goods Model: Modeled the price variation of 10 groceries from 24 neighborhoods in Berlin, California, and London based on product type, product quantity, and grocery store location under a Bayesian statistical framework; inferred the correlation between the average rental prices from 20 neighborhoods in Berlin and London to the cost of basic goods.
2. Carbon Emissions Predictive Model: A predictive Bayesian model that explains the atmospheric carbon dioxide measurements from Mauna Loa Observatory dataset and forecasts atmospheric carbon measurements for the next 40 years.

## Algorithms & Data Structures
1. Gene Mutation Sequencing: Executed a Python program to investigate genealogical mutation sequencing using Dynamic Programming and Greedy Algorithm frameworks; wrote a script to estimate the probabilities of insertions, deletions, and mutations.
2. Counting Bloom Filter

## Modeling & Simulation
1. Elevator Simulation: Group project where we designed and implemented a simulation of a building containing a single elevator and some number of passengers who want to travel from one floor in the building to another. We compared the performace for the two strategies we proposed and generated metrics to determine which was the better strategy.
2. Traffic Simulation: Implemented the single lane, variable-speed traffic model described in [https://course-resources.minerva.kgi.edu/uploaded_files/mke/YpqvNV/nagel-schreckenberg.pdf](Nagel), K.,Schreckenberg, M. (1992) as well as the 2-lane, symmetric, uni-directional, variable speed model in [https://course-resources.minerva.kgi.edu/uploaded_files/mke/00100888-7879/rickert-et-al.pdf](Rickert), M., et al. (1996). Analyzed how much more traffic can flow through a multi-lane road, compared to a single lane road, at the same traffic density. Presented my results in a report.
3. Social Dynamics Model: Implemented an extension to a social dynamics model covered in class to explore the interaction between people’s preferences or opinions and the strength of their social connections by proposing modifications to the model to make the dynamics more realistic; implemented my improvements in a simulation, and analyzed the expected (theoretical) and actual (experimental) effects of my changes on the model.

## Optimization Methods
1. Knapsack Problem: A Mixed Integer Program that uses the GLPK_MI solver in CVXPY to curate a catalogue of the most bought products and maximize the expected revenue while working within predefined weight and volume constraints.
2. Buenos Aires Tour: A tour of must-see locations in Buenos Aires. Implementd the Travelling Salesman Problem (TSP) to minimize the time required to visit each site once (and only once)

