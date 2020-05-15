# High dimensional instances for Knapsack Problem

The knapsack problem (KP) is a classic NP-complete problem [(Kellerer et. al 2004)](#references), which is defined by the task of taking a set of items, each with a weight and a profit, filling the knapsack so that the total profit is maximized, but not exceeding the maximum weight the knapsack can hold. KP is a very well-known problem in computer science. It occurs in many situations be they in industry, communication, finance, applied sciences or in real life.

The files in this repository correspond to binary Knapsack problem instances with big sizes, which go from 50,000 items to 1,000,000. The filename shows the number of items and knapsack capacity, e.g. `kp100K-10K-1.txt`  is an instance with 100,000 items and a knapsack capacity equal to 10,000. These big KP instances were obtained with the generator described in [(Pisinger 1999)](#refereces), choosing the uncorrelated data instances type (no correlation between the weight and the profit of an item). 

## References

(Kellerer et. al 2004) H. Kellerer, U. Pferschy, and D. Pisinger. Introduction to NP-Completeness of Knapsack Problems, pages 483–493. Springer Berlin Heidelberg, Berlin, Heidelberg, 2004.

(Pisinger 1999) D. Pisinger. Core problems in knapsack algorithms. Operations Research, 47:570–575, 1999.


