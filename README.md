# Visualizing-High-Dimensional-Data-with-t-SNE
This project involved implementing key components of the t-distributed Stochastic Neighbor Embedding (t-SNE) algorithm to explore non-linear dimensionality reduction. The data consisted of two Gaussian clusters in 2D space.

The task began with constructing the conditional similarity matrix 
𝑝
𝑗
∣
𝑖
p 
j∣i
​
 , followed by the symmetric joint probability matrix 
𝑝
𝑖
𝑗
p 
ij
​
 , which reflects pairwise affinities in the high-dimensional space. Visualization experiments were conducted using different values of the variance parameter 
𝜎
2
σ 
2
 , illustrating how neighborhood size affects local versus global structure.

The low-dimensional similarity matrix 
𝑞
𝑖
𝑗
q 
ij
​
  was then computed using a Student t-distribution kernel, and comparisons between 
𝑝
𝑖
𝑗
p 
ij
​
  and 
𝑞
𝑖
𝑗
q 
ij
​
  were made using KL-divergence. Multiple projections were evaluated by measuring how well they preserved local structure, and the effects of varying hyperparameters like 
𝜎
2
σ 
2
  on divergence and clustering fidelity were analyzed.

This hands-on exploration provided intuition for how t-SNE balances local and global relationships and how parameter tuning affects the resulting embeddings.
