# SCCAB(iclustering)
This method finds linear biclusters by exploiting SCCA.

# TODOs
## Features
- Fused Lasso on **D**
- Complete set of plotting functions
- Allow functors for different types of maximization

## Exploratory
- Figure out good regularization for feature vectors (not just 1:3)
- Investigate how to scale differently for **D**

## Major refactoring
- Start using `fscca` instead of `scca`
- Formal class instead of just passing
- Post processes more formal
- ~~Move to `roxygen`~~
- ~~Turn into a real R package~~

## Minor
- `data.frame` to `matrix` objects in matrix computations
- camelCase to snake_case
- remove '.' in functions
