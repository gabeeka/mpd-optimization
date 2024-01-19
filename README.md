# Product Modularization Problem Optimization

## Product Modularization Using Cuckoo Search Algorithm (Hayam G. Wahdan, Sally S. Kassem, and Hisham M.E. Abdelsalam)

### Reprezentation

#### Design Structure Matrix
The product is represented in the form of a Design Structure Matrix (DSM) that contains a list of all
product components and the corresponding information exhange and dependency patterns.
The DSM will work as a system analysis tool that provides a compact and clear representation of a
complex system.

Once a DSM is constructed, it can be analyzed for identifying
modules, a process referred to as clustering. The goal of DSM clustering is to find a
clustering arrangement where modules minimally interact with each other, while
components within a module maximally interact with each other.

#### Objective/Cost Function

IntraClusterCost

ExtrClusterCost

Total coordination Cost ¼ ExtraClusterCostþ IntraClusterCost

#### Solution Reprezentation

|1|2|2|2|3|3|1| - vector

Size of the vector (7) - where the DSM contains 7 elements (7 rows).
Elements 1, 7    belong to cluster 1
Elements 2, 3, 4 belong to cluster 2
Elements 5, 6    belong to cluster 3

This solution representation enforces an element to be part of a single cluster.

#### Solution Evaluation



#### Alg
 SA
 GA
 GS - CS
 kurzust megnezni, 9-est is, egesz reprezentacio