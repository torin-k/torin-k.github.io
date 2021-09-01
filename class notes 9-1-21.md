# 80-516 Class Notes 9/1/21

*Last class: definition of causality, necessity for causal view*

**Artificial intelligence** - imitating human behavior or computational rationality?
Three current problems:

 - Prediction - probability of `e1` given `e2` happens naturally
 - Intervention - probability of `e1` given we force `e2` to be true
 - Counterfactual - probability of `e1` if `e2` had been true, even though we know `e2` to not be true

Investigating causal structure:
- If `X` causes `Y`, then `P(Y | do X=X1) = P(Y | X=X1)`
- If `Y` causes `X`, then `P(Y | do X=X1) = P(Y)` (as `Y` is not modified by `X`)


**Machine learning**:

 - Learning without being specifically programmed
 - Use data to improve knowledge via automated mechanisms

Three components of ML:

 1. Data - what information do we have, and is it useful?
 2. Task - what do we aim to produce (discriminative, generative)
 3. Algorithm - what mechanism do we actually use to leverage data to solve our task?

Three categories of ML:
 1. Supervised - given a set of labeled training data
	 - want to predict unseen examples well (avoid over/under-fitting)
	 - Nearest-neighbor, decision tree, regression, NN
 2. Unsupervised (GMM, K-means, PCA)
 3. Reinforcement - taught by the environment, learns via exploration and costs/rewards
	- We want to find how current state and action influence next state, that is learn the function `f(S_current, A) = S_future` so we can choose the optimal action `A` to get to goal `S_future`.

*In most problems where deep learning is the best solution, we aim to find a `Y` given `X` where `Y` is the cause of `X` (i.e. medical diagnosis).*


Benefits of causal thinking:

 - Dependence vs. causality - smoking causes yellow fingers and lung cancer, but avoiding yellow fingers won't reduce cancer!
 - Simpson's Paradox - if we don't account for certain variables, we see weird results! This is due to effects on sample size. If we look only at recovery rate, treatment A might seem worse than treatment B. But if it turns out that sicker people tend to get treatment A, it could be that treatment A 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NTYzMjM2NTIsLTU3NzM2ODM3MSwtMT
cxOTI1OTU4LC02OTI1MDAwMDEsLTY2NDYxOTE2Ml19
-->