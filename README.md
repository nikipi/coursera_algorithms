# Python codes for Coursera Algorithms

---

[Coursera algorithms](https://www.coursera.org/learn/algorithms-divide-conquer/lecture/NtFU9/merge-sort-pseudocode)

Python 3 version

## Karatsuba Multiplication

![alt text](./pic/Selection_003.png)


![alt text](./pic/Selection_004.png)



## Merge Sort

![alt text](./pic/Selection_005.png)

## Big-O notation

Formal definition: $T(n) = O(f(n))$ if and only if there exist $c, n_0 > 0$, such that $T(n) \leq cf(n)$ for all $n \geq n_0$.


## Omega notation

Formal definition: $T(n) = \Omega(f(n))$ if and only if there exist $c, n_0 > 0$, such that $T(n) \geq cf(n)$ for all $n \geq n_0$.

## Theta notation

Formal definition: $T(n)=\theta(f(n))$ if and only if $T(n)=O(f(n))$ and $T(n)=\Omega(f(n))$. 
there exist $c_1, c_2$, such that $T(n) \geq c_1 f(n)$ and $T(n) \leq c_2 f(n)$ for all $n \geq n_0$.

## Counting inversions

Couting inversion means that 

 $i, j$ form an inversion if $a_i > a_j$, that is, if the two elements $a_i$ and $a_j$ are "out of order".

Finding "similarity" between two rankings. Given a sequence of n numbers 1..n (assume all numbers are distinct). Define a measure that tells us how far this list is from being in ascending order.  The value should be 0 if $a_1 < a_2 < ... < a_n$ and 
should be higher as the list is more "out of order".

![alt text](./pic/Selection_031.png)

![alt text](./pic/Selection_032.png)


## Strassen's Subcubic Matrix Multiplication Algorithm

![alt text](./pic/Selection_033.png)



## The master method for asymptotic analysis of divide and conquer algorithms

![alt text](./pic/Selection_034.png)

![alt text](./pic/Selection_035.png)


## QuickSort 

### implementation


![alt text](./pic/Selection_037.png)

![alt text](./pic/Selection_040.png)

### Example

![alt text](./pic/Selection_038.png)

![alt text](./pic/Selection_039.png)

### Background knowledge

Utilized linearity of Expectation and decomposition principle

Rule of thumb for checking independene of random variables:

So, for those of you without much practice with independence, here's my rule of thumb for whether or not you treat random variables as independent. If things are independent by construction, like, for example, you define it in your algorithm, so the two different things are independent. Then you can proceed with the analysis under the assumption that they're independent. If there's any doubt, if it's not obvious the two things are independent, you might want to, as a rule of thumb, assume that they're dependent until further notice. 

![alt text](./pic/Selection_052.png)

![alt text](./pic/Selection_051.png)

![alt text](./pic/Selection_045.png)

A good exercise is the birthday problem with the solution in [Introduction of Algorithms](https://books.google.de/books?id=NLngYyWFl_YC&pg=PA106&lpg=PA106&dq=birthday+problem+introduction+to+algorithms&source=bl&ots=BzSoIz0kHa&sig=ACfU3U177Hw1_m4xZFxmfM6JMoSxLSoNaA&hl=en&sa=X&ved=2ahUKEwjIr5Du4YjhAhUPy6YKHadKCtAQ6AEwBXoECAkQAQ#v=onepage&q=birthday%20problem%20introduction%20to%20algorithms&f=false)


### Asymptotic analysis and proof

![alt text](./pic/Selection_041.png)

![alt text](./pic/Selection_042.png)

![alt text](./pic/Selection_043.png)

![alt text](./pic/Selection_044.png)


![alt text](./pic/Selection_046.png)

![alt text](./pic/Selection_047.png)

![alt text](./pic/Selection_048.png)

![alt text](./pic/Selection_049.png)

## Karger Min-cut algorithm


![alt text](./pic/Selection_054.png)

![alt text](./pic/Selection_055.png)

![alt text](./pic/Selection_056.png)


## Graph Search

### BFS

![alt text](./pic/Selection_062.png)

![alt text](./pic/Selection_063.png)

### DFS

![alt text](./pic/Selection_064.png)

#### Strongly Connected Components of direct graph

![alt text](./pic/Selection_066.png)

![alt text](./pic/Selection_067.png)

![alt text](./pic/Selection_068.png)

![alt text](./pic/Selection_065.png)

## Single source shortest path

![alt text](./pic/Selection_069.png)

### Dijkstra algorithm

![alt text](./pic/Selection_070.png)

![alt text](./pic/Selection_071.png)

#### Heap data structure to increase the searching

![alt text](./pic/Selection_072.png)

![alt text](./pic/Selection_073.png)

## Heap and its in median maintenance

![alt text](./pic/Selection_074.png)

## Hash table and 2-sum problem

![alt text](./pic/Selection_075.png)


## Greedy method

### Schedule problem

![alt text](./pic/Selection_077.png)

![alt text](./pic/Selection_076.png)


### MST problem

![alt text](./pic/Selection_078.png)

![alt text](./pic/Selection_079.png)

## Clustering and UnionFind data structure

### Kruskal MST

![alt text](./pic/Selection_081.png)

### UnionFind data structure


![alt text](./pic/Selection_081.png)

### Greedy algorithm for clustering

![alt text](./pic/Selection_082.png)

![alt text](./pic/Selection_083.png)

## Huffman coding and Dynamic Programming

### Huffman coding
![alt text](./pic/Selection_085.png)

![alt text](./pic/Selection_086.png)

### Max weighted independent set problem

![alt text](./pic/Selection_087.png)

![alt text](./pic/Selection_088.png)

![alt text](./pic/Selection_089.png)

![alt text](./pic/Selection_090.png)

### Dynamic programming

![alt text](./pic/Selection_091.png)

### Knapsack 

![alt text](./pic/Selection_092.png)

![alt text](./pic/Selection_093.png)

![alt text](./pic/Selection_094.png)

![alt text](./pic/Selection_095.png)

### Optimal binary search tree



![alt text](./pic/Selection_096.png)

![alt text](./pic/Selection_097.png)

![alt text](./pic/Selection_098.png)

