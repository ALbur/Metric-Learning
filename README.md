# Metric-Learning
Author: Xing EP,Ng AY,Jordan MI, et al.Distance Metric Learning,with Application to Clustering with Side-information [C]//International Conference on Neural Information Processing Systems, 2002.
% ---------------------------------------------------------------------------
% Input 
% X: data
% S: similarity constraints (in the form of a pairwise-similarity matrix)
% D: disimilarity constraints (in the form of a pairwise-disimilarity matrix)
% A: initial distance metric matrix
% w: a weight vector originated from similar data (see paper)
% upper bound of constraint C1 (the sum of pairwise distance bound)
% maxiter: maximum iterations
%
% Output
% A: the solution of distance metric matrix
% converged: indicator of convergence
% iters: iterations passed until convergence 
% ---------------------------------------------------------------------------

X：数据
S：相似性约束（以成对相似性矩阵的形式）
D：相异性约束（以成对相异矩阵的形式）
A：初始距离度量矩阵
w：来自类似数据的权重向量（见论文）
t：约束 C1 的上限（成对距离的总和）
maxiter：最大迭代次数

iter_projection_new2(X, S, D, A, w, t, maxiter)
