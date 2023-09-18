# JavaScript Algorithms and Data Structures

**Original Repository:** [trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms)

![version](https://img.shields.io/badge/version-1.0.0-yellowgreen)
![licence](https://img.shields.io/badge/license-MIT-brightgree)
![open pr](https://img.shields.io/github/issues-pr-raw/betelgeuseAS/js-algorithms-data.svg)
![open issues](https://img.shields.io/github/issues-raw/betelgeuseAS/js-algorithms-data.svg)
![repo size](https://img.shields.io/github/repo-size/betelgeuseAS/js-algorithms-data.svg)
![author](https://img.shields.io/badge/author-Andrew%20Samchuk-orange)

This repository contains JavaScript based examples of many
popular algorithms and data structures.

Each algorithm and data structure has its own separate README
with related explanations and links for further reading (including ones
to YouTube videos).

_Read this in other languages:_
[_Українська_](README.uk-UA.md)

*☝ Note that this project is meant to be used for learning and researching purposes
only, and it is **not** meant to be used for production.*

## Data Structures

A data structure is a particular way of organizing and storing data in a computer so that it can
be accessed and modified efficiently. More precisely, a data structure is a collection of data
values, the relationships among them, and the functions or operations that can be applied to
the data.

* [Linked List](data-structures/linked-list)
* [Doubly Linked List](data-structures/doubly-linked-list)
* [Queue](data-structures/queue)
* [Stack](data-structures/stack)
* [Hash Table](data-structures/hash-table)
* [Heap](data-structures/heap) - max and min heap versions
* [Priority Queue](data-structures/priority-queue)
* [Trie](data-structures/trie)
* [Tree](data-structures/tree)
  * [Binary Search Tree](data-structures/tree/binary-search-tree)
  * [AVL Tree](data-structures/tree/avl-tree)
  * [Red-Black Tree](data-structures/tree/red-black-tree)
  * [Segment Tree](data-structures/tree/segment-tree) - with min/max/sum range queries examples
  * [Fenwick Tree](data-structures/tree/fenwick-tree) (Binary Indexed Tree)
* [Graph](data-structures/graph) (both directed and undirected)
* [Disjoint Set](data-structures/disjoint-set) - a union–find data structure or merge–find set
* [Bloom Filter](data-structures/bloom-filter)
* [LRU Cache](data-structures/lru-cache/) - Least Recently Used (LRU) cache

## Algorithms

An algorithm is an unambiguous specification of how to solve a class of problems. It is
a set of rules that precisely define a sequence of operations.

* **Math**
  * [Bit Manipulation](algorithms/math/bits) - set/get/update/clear bits, multiplication/division by two, make negative etc.
  * [Binary Floating Point](algorithms/math/binary-floating-point) - binary representation of the floating-point numbers.
  * [Factorial](algorithms/math/factorial)
  * [Fibonacci Number](algorithms/math/fibonacci) - classic and closed-form versions
  * [Prime Factors](algorithms/math/prime-factors) - finding prime factors and counting them using Hardy-Ramanujan's theorem
  * [Primality Test](algorithms/math/primality-test) (trial division method)
  * [Euclidean Algorithm](algorithms/math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  * [Least Common Multiple](algorithms/math/least-common-multiple) (LCM)
  * [Sieve of Eratosthenes](algorithms/math/sieve-of-eratosthenes) - finding all prime numbers up to any given limit
  * [Is Power of Two](algorithms/math/is-power-of-two) - check if the number is power of two (naive and bitwise algorithms)
  * [Pascal's Triangle](algorithms/math/pascal-triangle)
  * [Complex Number](algorithms/math/complex-number) - complex numbers and basic operations with them
  * [Radian & Degree](algorithms/math/radian) - radians to degree and backwards conversion
  * [Fast Powering](algorithms/math/fast-powering)
  * [Horner's method](algorithms/math/horner-method) - polynomial evaluation
  * [Matrices](algorithms/math/matrix) - matrices and basic matrix operations (multiplication, transposition, etc.)
  * [Euclidean Distance](algorithms/math/euclidean-distance) - distance between two points/vectors/matrices
  * [Integer Partition](algorithms/math/integer-partition)
  * [Square Root](algorithms/math/square-root) - Newton's method
  * [Liu Hui π Algorithm](algorithms/math/liu-hui) - approximate π calculations based on N-gons
  * [Discrete Fourier Transform](algorithms/math/fourier-transform) - decompose a function of time (a signal) into the frequencies that make it up
* **Sets**
  * [Cartesian Product](algorithms/sets/cartesian-product) - product of multiple sets
  * [Fisher–Yates Shuffle](algorithms/sets/fisher-yates) - random permutation of a finite sequence
  * [Power Set](algorithms/sets/power-set) - all subsets of a set (bitwise, backtracking, and cascading solutions)
  * [Permutations](algorithms/sets/permutations) (with and without repetitions)
  * [Combinations](algorithms/sets/combinations) (with and without repetitions)
  * [Longest Common Subsequence](algorithms/sets/longest-common-subsequence) (LCS)
  * [Longest Increasing Subsequence](algorithms/sets/longest-increasing-subsequence)
  * [Shortest Common Supersequence](algorithms/sets/shortest-common-supersequence) (SCS)
  * [Knapsack Problem](algorithms/sets/knapsack-problem) - "0/1" and "Unbound" ones
  * [Maximum Subarray](algorithms/sets/maximum-subarray) - "Brute Force" and "Dynamic Programming" (Kadane's) versions
  * [Combination Sum](algorithms/sets/combination-sum) - find all combinations that form specific sum
* **Strings**
  * [Hamming Distance](algorithms/string/hamming-distance) - number of positions at which the symbols are different
  * [Palindrome](algorithms/string/palindrome) - check if the string is the same in reverse
  * [Levenshtein Distance](algorithms/string/levenshtein-distance) - minimum edit distance between two sequences
  * [Knuth–Morris–Pratt Algorithm](algorithms/string/knuth-morris-pratt) (KMP Algorithm) - substring search (pattern matching)
  * [Z Algorithm](algorithms/string/z-algorithm) - substring search (pattern matching)
  * [Rabin Karp Algorithm](algorithms/string/rabin-karp) - substring search
  * [Longest Common Substring](algorithms/string/longest-common-substring)
  * [Regular Expression Matching](algorithms/string/regular-expression-matching)
* **Searches**
  * [Linear Search](algorithms/search/linear-search)
  * [Jump Search](algorithms/search/jump-search) (or Block Search) - search in sorted array
  * [Binary Search](algorithms/search/binary-search) - search in sorted array
  * [Interpolation Search](algorithms/search/interpolation-search) - search in uniformly distributed sorted array
* **Sorting**
  * [Bubble Sort](algorithms/sorting/bubble-sort)
  * [Selection Sort](algorithms/sorting/selection-sort)
  * [Insertion Sort](algorithms/sorting/insertion-sort)
  * [Heap Sort](algorithms/sorting/heap-sort)
  * [Merge Sort](algorithms/sorting/merge-sort)
  * [Quicksort](algorithms/sorting/quick-sort) - in-place and non-in-place implementations
  * [Shellsort](algorithms/sorting/shell-sort)
  * [Counting Sort](algorithms/sorting/counting-sort)
  * [Radix Sort](algorithms/sorting/radix-sort)
  * [Bucket Sort](algorithms/sorting/bucket-sort)
* **Linked Lists**
  * [Straight Traversal](algorithms/linked-list/traversal)
  * [Reverse Traversal](algorithms/linked-list/reverse-traversal)
* **Trees**
  * [Depth-First Search](algorithms/tree/depth-first-search) (DFS)
  * [Breadth-First Search](algorithms/tree/breadth-first-search) (BFS)
* **Graphs**
  * [Depth-First Search](algorithms/graph/depth-first-search) (DFS)
  * [Breadth-First Search](algorithms/graph/breadth-first-search) (BFS)
  * [Kruskal’s Algorithm](algorithms/graph/kruskal) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * [Dijkstra Algorithm](algorithms/graph/dijkstra) - finding the shortest paths to all graph vertices from single vertex
  * [Bellman-Ford Algorithm](algorithms/graph/bellman-ford) - finding the shortest paths to all graph vertices from single vertex
  * [Floyd-Warshall Algorithm](algorithms/graph/floyd-warshall) - find the shortest paths between all pairs of vertices
  * [Detect Cycle](algorithms/graph/detect-cycle) - for both directed and undirected graphs (DFS and Disjoint Set based versions)
  * [Prim’s Algorithm](algorithms/graph/prim) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * [Topological Sorting](algorithms/graph/topological-sorting) - DFS method
  * [Articulation Points](algorithms/graph/articulation-points) - Tarjan's algorithm (DFS based)
  * [Bridges](algorithms/graph/bridges) - DFS based algorithm
  * [Eulerian Path and Eulerian Circuit](algorithms/graph/eulerian-path) - Fleury's algorithm - Visit every edge exactly once
  * [Hamiltonian Cycle](algorithms/graph/hamiltonian-cycle) - Visit every vertex exactly once
  * [Strongly Connected Components](algorithms/graph/strongly-connected-components) - Kosaraju's algorithm
  * [Travelling Salesman Problem](algorithms/graph/travelling-salesman) - shortest possible route that visits each city and returns to the origin city
* **Cryptography**
  * [Polynomial Hash](algorithms/cryptography/polynomial-hash) - rolling hash function based on polynomial
  * [Rail Fence Cipher](algorithms/cryptography/rail-fence-cipher) - a transposition cipher algorithm for encoding messages
  * [Caesar Cipher](algorithms/cryptography/caesar-cipher) - simple substitution cipher
  * [Hill Cipher](algorithms/cryptography/hill-cipher) - substitution cipher based on linear algebra
* **Machine Learning**
  * [NanoNeuron](https://github.com/trekhleb/nano-neuron) - 7 simple JS functions that illustrate how machines can actually learn (forward/backward propagation)
  * [k-NN](algorithms/ml/knn) - k-nearest neighbors classification algorithm
  * [k-Means](algorithms/ml/k-means) - k-Means clustering algorithm
* **Image Processing**
  * [Seam Carving](algorithms/image-processing/seam-carving) - content-aware image resizing algorithm
* **Statistics**
  * [Weighted Random](algorithms/statistics/weighted-random) - select the random item from the list based on items' weights
* **Evolutionary algorithms**
  * [Genetic algorithm](https://github.com/trekhleb/self-parking-car-evolution) - example of how the genetic algorithm may be applied for training the self-parking cars
* **Uncategorized**
  * [Tower of Hanoi](algorithms/uncategorized/hanoi-tower)
  * [Square Matrix Rotation](algorithms/uncategorized/square-matrix-rotation) - in-place algorithm
  * [Jump Game](algorithms/uncategorized/jump-game) - backtracking, dynamic programming (top-down + bottom-up) and greedy examples
  * [Unique Paths](algorithms/uncategorized/unique-paths) - backtracking, dynamic programming and Pascal's Triangle based examples
  * [Rain Terraces](algorithms/uncategorized/rain-terraces) - trapping rain water problem (dynamic programming and brute force versions)
  * [Recursive Staircase](algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top (4 solutions)
  * [Best Time To Buy Sell Stocks](algorithms/uncategorized/best-time-to-buy-sell-stocks) - divide and conquer and one-pass examples
  * [N-Queens Problem](algorithms/uncategorized/n-queens)
  * [Knight's Tour](algorithms/uncategorized/knight-tour)

### Algorithms by Paradigm

An algorithmic paradigm is a generic method or approach which underlies the design of a class
of algorithms. It is an abstraction higher than the notion of an algorithm, just as an
algorithm is an abstraction higher than a computer program.

* **Brute Force** - look at all the possibilities and selects the best solution
  * [Linear Search](algorithms/search/linear-search)
  * [Rain Terraces](algorithms/uncategorized/rain-terraces) - trapping rain water problem
  * [Recursive Staircase](algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top
  * [Maximum Subarray](algorithms/sets/maximum-subarray)
  * [Travelling Salesman Problem](algorithms/graph/travelling-salesman) - shortest possible route that visits each city and returns to the origin city
  * [Discrete Fourier Transform](algorithms/math/fourier-transform) - decompose a function of time (a signal) into the frequencies that make it up
* **Greedy** - choose the best option at the current time, without any consideration for the future
  * [Jump Game](algorithms/uncategorized/jump-game)
  * [Unbound Knapsack Problem](algorithms/sets/knapsack-problem)
  * [Dijkstra Algorithm](algorithms/graph/dijkstra) - finding the shortest path to all graph vertices
  * [Prim’s Algorithm](algorithms/graph/prim) - finding Minimum Spanning Tree (MST) for weighted undirected graph
  * [Kruskal’s Algorithm](algorithms/graph/kruskal) - finding Minimum Spanning Tree (MST) for weighted undirected graph
* **Divide and Conquer** - divide the problem into smaller parts and then solve those parts
  * [Binary Search](algorithms/search/binary-search)
  * [Tower of Hanoi](algorithms/uncategorized/hanoi-tower)
  * [Pascal's Triangle](algorithms/math/pascal-triangle)
  * [Euclidean Algorithm](algorithms/math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  * [Merge Sort](algorithms/sorting/merge-sort)
  * [Quicksort](algorithms/sorting/quick-sort)
  * [Tree Depth-First Search](algorithms/tree/depth-first-search) (DFS)
  * [Graph Depth-First Search](algorithms/graph/depth-first-search) (DFS)
  * [Matrices](algorithms/math/matrix) - generating and traversing the matrices of different shapes
  * [Jump Game](algorithms/uncategorized/jump-game)
  * [Fast Powering](algorithms/math/fast-powering)
  * [Best Time To Buy Sell Stocks](algorithms/uncategorized/best-time-to-buy-sell-stocks) - divide and conquer and one-pass examples
  * [Permutations](algorithms/sets/permutations) (with and without repetitions)
  * [Combinations](algorithms/sets/combinations) (with and without repetitions)
  * [Maximum Subarray](algorithms/sets/maximum-subarray)
* **Dynamic Programming** - build up a solution using previously found sub-solutions
  * [Fibonacci Number](algorithms/math/fibonacci)
  * [Jump Game](algorithms/uncategorized/jump-game)
  * [Unique Paths](algorithms/uncategorized/unique-paths)
  * [Rain Terraces](algorithms/uncategorized/rain-terraces) - trapping rain water problem
  * [Recursive Staircase](algorithms/uncategorized/recursive-staircase) - count the number of ways to reach to the top
  * [Seam Carving](algorithms/image-processing/seam-carving) - content-aware image resizing algorithm
  * [Levenshtein Distance](algorithms/string/levenshtein-distance) - minimum edit distance between two sequences
  * [Longest Common Subsequence](algorithms/sets/longest-common-subsequence) (LCS)
  * [Longest Common Substring](algorithms/string/longest-common-substring)
  * [Longest Increasing Subsequence](algorithms/sets/longest-increasing-subsequence)
  * [Shortest Common Supersequence](algorithms/sets/shortest-common-supersequence)
  * [0/1 Knapsack Problem](algorithms/sets/knapsack-problem)
  * [Integer Partition](algorithms/math/integer-partition)
  * [Maximum Subarray](algorithms/sets/maximum-subarray)
  * [Bellman-Ford Algorithm](algorithms/graph/bellman-ford) - finding the shortest path to all graph vertices
  * [Floyd-Warshall Algorithm](algorithms/graph/floyd-warshall) - find the shortest paths between all pairs of vertices
  * [Regular Expression Matching](algorithms/string/regular-expression-matching)
* **Backtracking** - similarly to brute force, try to generate all possible solutions, but each time you generate next solution you test
if it satisfies all conditions, and only then continue generating subsequent solutions. Otherwise, backtrack, and go on a
different path of finding a solution. Normally the DFS traversal of state-space is being used.
  * [Jump Game](algorithms/uncategorized/jump-game)
  * [Unique Paths](algorithms/uncategorized/unique-paths)
  * [Power Set](algorithms/sets/power-set) - all subsets of a set
  * [Hamiltonian Cycle](algorithms/graph/hamiltonian-cycle) - Visit every vertex exactly once
  * [N-Queens Problem](algorithms/uncategorized/n-queens)
  * [Knight's Tour](algorithms/uncategorized/knight-tour)
  * [Combination Sum](algorithms/sets/combination-sum) - find all combinations that form specific sum
* **Branch & Bound** - remember the lowest-cost solution found at each stage of the backtracking
search, and use the cost of the lowest-cost solution found so far as a lower bound on the cost of
a least-cost solution to the problem, in order to discard partial solutions with costs larger than the
lowest-cost solution found so far. Normally BFS traversal in combination with DFS traversal of state-space
tree is being used.

## Useful Information

### References

- [▶ Data Structures and Algorithms on YouTube](https://www.youtube.com/playlist?list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

### Big O Notation

*Big O notation* is used to classify algorithms according to how their running time or space requirements grow as the input size grows.
On the chart below you may find most common orders of growth of algorithms specified in Big O notation.

![Big O graphs](./assets/big-o-graph.png)

Source: [Big O Cheat Sheet](http://bigocheatsheet.com/).

Below is the list of some of the most used Big O notations and their performance comparisons against different sizes of the input data.

| Big O Notation | Type        | Computations for 10 elements | Computations for 100 elements | Computations for 1000 elements  |
| -------------- | ----------- | ---------------------------- | ----------------------------- | ------------------------------- |
| **O(1)**       | Constant    | 1                            | 1                             | 1                               |
| **O(log N)**   | Logarithmic | 3                            | 6                             | 9                               |
| **O(N)**       | Linear      | 10                           | 100                           | 1000                            |
| **O(N log N)** | n log(n)    | 30                           | 600                           | 9000                            |
| **O(N^2)**     | Quadratic   | 100                          | 10000                         | 1000000                         |
| **O(2^N)**     | Exponential | 1024                         | 1.26e+29                      | 1.07e+301                       |
| **O(N!)**      | Factorial   | 3628800                      | 9.3e+157                      | 4.02e+2567                      |

### Data Structure Operations Complexity

| Data Structure          | Access    | Search    | Insertion | Deletion  | Comments  |
| ----------------------- | :-------: | :-------: | :-------: | :-------: | :-------- |
| **Array**               | 1         | n         | n         | n         |           |
| **Stack**               | n         | n         | 1         | 1         |           |
| **Queue**               | n         | n         | 1         | 1         |           |
| **Linked List**         | n         | n         | 1         | n         |           |
| **Hash Table**          | -         | n         | n         | n         | In case of perfect hash function costs would be O(1) |
| **Binary Search Tree**  | n         | n         | n         | n         | In case of balanced tree costs would be O(log(n)) |
| **B-Tree**              | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Red-Black Tree**      | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **AVL Tree**            | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Bloom Filter**        | -         | 1         | 1         | -         | False positives are possible while searching |

### Array Sorting Algorithms Complexity

| Name                  | Best            | Average             | Worst               | Memory    | Stable    | Comments  |
| --------------------- | :-------------: | :-----------------: | :-----------------: | :-------: | :-------: | :-------- |
| **Bubble sort**       | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |
| **Insertion sort**    | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |
| **Selection sort**    | n<sup>2</sup>   | n<sup>2</sup>       | n<sup>2</sup>       | 1         | No        |           |
| **Heap sort**         | n&nbsp;log(n)   | n&nbsp;log(n)       | n&nbsp;log(n)       | 1         | No        |           |
| **Merge sort**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n&nbsp;log(n)       | n         | Yes       |           |
| **Quick sort**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n<sup>2</sup>       | log(n)    | No        | Quicksort is usually done in-place with O(log(n)) stack space |
| **Shell sort**        | n&nbsp;log(n)   | depends on gap sequence   | n&nbsp;(log(n))<sup>2</sup>  | 1         | No         |           |
| **Counting sort**     | n + r           | n + r               | n + r               | n + r     | Yes       | r - biggest number in array |
| **Radix sort**        | n * k           | n * k               | n * k               | n + k     | Yes       | k - length of longest key |

## Support

> You may support this project via ❤️️ [Buy me a coffee](https://www.buymeacoffee.com/betelgeuseo) or ❤️️ [Become a Patron](https://www.paypal.com/donate/?hosted_button_id=327N24D6QDLVC).

## Author

[MeDev](https://betelgeuseas.github.io/me-dev/)
