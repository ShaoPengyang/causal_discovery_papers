# causal_discovery_papers
Continuous optimization-score based methods
### Questions
- 我发现杨帅和况老师的文章都直接为正则化项，没有进一步讨论拉格朗日对偶形式，为什么？
- 一步优化和迭代式优化的区别在于？

|Paper|year|Introduction|code|
|--|--|--|--|
|Notears|NIPS ||offical codes [here](https://github.com/xunzheng/notears)|
|DAG-GNN|ICML 2019||offical codes [here](https://github.com/fishmoon1234/DAG-GNN) others [here](https://github.com/ronikobrosly/DAG_from_GNN)|
|Gradient-Based Neural DAG Learning|ICLR 2020|We propose a novel score-based approach to learning a directed acyclic graph (DAG) from observational data. We adapt a recently proposed continuous constrained optimization formulation to allow for nonlinear relationships between variables using neural networks. This extension allows to model complex interactions while avoiding the combinatorial nature of the problem. In addition to comparing our method to existing continuous optimization methods, we provide missing empirical comparisons to nonlinear greedy search methods. On both synthetic and real-world data sets, this new method outperforms current continuous methods on most tasks while being competitive with existing greedy search methods on important metrics for causal inference.|[here](https://github.com/kurowasan/GraN-DAG)|
|DAGs with No Fears: A closer look at continuous optimization for learning Bayesian networks|NIPS 2020|This paper re-examines a continuous optimization framework dubbed NOTEARS for learning Bayesian networks. We first generalize existing algebraic characterizations of acyclicity to a class of matrix polynomials. Next, focusing on a one-parameter-per-edge setting, it is shown that the Karush-Kuhn-Tucker (KKT) optimality conditions for the NOTEARS formulation cannot be satisfied except in a trivial case, which explains a behavior of the associated algorithm. We then derive the KKT conditions for an equivalent reformulation, show that they are indeed necessary, and relate them to explicit constraints that certain edges be absent from the graph. If the score function is convex, these KKT conditions are also sufficient for local minimality despite the non-convexity of the constraint. Informed by the KKT conditions, a local search post-processing algorithm is proposed and shown to substantially and universally improve the structural Hamming distance of all tested algorithms, typically by a factor of 2 or more. Some combinations with local search are both more accurate and more efficient than the original NOTEARS.||
|CausalVAE: Disentangled Representation Learning via Neural Structural Causal Models|CVPR 2021|||
|Dags with no curl: An efficient dag structure learning approach|ICML 2021|||
|Weakly Supervised Disentangled Generative Causal Representation Learning|JMLR 2022|||
|Masked gradient-based causal structure learning|SDM 2022|||
|Personalized Latent Structure Learning for Recommendation|TPAMI 2023|First, introduce a base DAG learning model. \\ Level 1 challenge: personalized DAG. Someone not follow majority, and some hidden variables. Level 2 challenge: sparse and noisy nature of interaction data. PlanRec: latent structure personalization and balancing personalization and shared knowledge for each individual over the base latent structure learning model||

|Paper|year|Introduction|
|--|--|--|
|DAG-GAN: Causal Structure Learning with Generative Adversarial Nets|||
|Large-Scale Differentiable Causal Discovery of Factor Graphs|||
|Disentangling shared and group-specific variations in single-cell transcriptomics data with multiGroupVI|PMLR 2022||
|On the Convergence of Continuous Constrained Optimization for Structure Learning|PMLR 2022||
