# algorithms.php

[![Build Status](https://travis-ci.org/su-xiaolin/algorithms.php.svg)](https://travis-ci.org/su-xiaolin/algorithms.php)
[![Code Climate](https://codeclimate.com/github/su-xiaolin/algorithms.php/badges/gpa.svg)](https://codeclimate.com/github/su-xiaolin/algorithms.php)
[![Issue Count](https://codeclimate.com/github/su-xiaolin/algorithms.php/badges/issue_count.svg)](https://codeclimate.com/github/su-xiaolin/algorithms.php)
[![Latest Stable Version](https://poser.pugx.org/suxiaolin/algorithms/version)](https://packagist.org/packages/suxiaolin/algorithms)
[![Latest Unstable Version](https://poser.pugx.org/suxiaolin/algorithms/v/unstable)](//packagist.org/packages/suxiaolin/algorithms)
[![Total Downloads](https://poser.pugx.org/suxiaolin/algorithms/downloads)](https://packagist.org/packages/suxiaolin/algorithms)
[![License](https://poser.pugx.org/suxiaolin/algorithms/license)](https://packagist.org/packages/suxiaolin/algorithms)

![](http://www.quickmeme.com/img/8d/8d30a19413145512ad5a05c46ec0da545df5ed79e113fcf076dc03c7514eb631.jpg)


## Atwood's Law applied to CS101.

Classic algorithms and data structures implemented in JavaScript, you know... FOR SCIENCE.

### Installing
```
npm install --save algorithms
```

### Contents

#### Data Structures

```javascript
require('algorithms/data_structures');
// or
require('algorithms').DataStructures;
```

* BST
* DisjointSetForest
* FenwickTree
* Graph
* HashTable
* Heap
 * MaxHeap
 * MinHeap
* LinkedList
* PriorityQueue
* Queue
* Set (HashSet)
* Stack

#### Graph algorithms

```javascript
require('algorithms/graph');
// or
require('algorithms').Graph;
```

* breadthFirstSearch
* depthFirstSearch
* eulerPath
* topologicalSort

##### Shortest path
* bellmanFord
* bfsShortestPath
* dijkstra
* floydWarshall
* SPFA (Shortest Path Faster Algorithm)

##### Minimum spanning tree
* prim
* kruskal

#### Math algorithms

```javascript
require('algorithms/math');
// or
require('algorithms').Math;
```
* collatzConjecture
* extendedEuclidean
* fastPower
* fibonacci
* fisherYates
* gcd (Greatest common divisor)
* greatestDifference
* lcm (Least common multiple)
* newtonSqrt
* nextPermutation
* powerSet
* reservoirSampling
* shannonEntropy

#### Search algorithms

```javascript
require('algorithms/search');
// or
require('algorithms').Search;
```

* bfs (breadth-first search for binary trees)
* binarySearch
* dfs (depth-first search for binary trees)
 * inOrder (default)
 * postOrder
 * preOrder

#### Sorting algorithms

```javascript
require('algorithms/sorting');
// or
require('algorithms').Sorting;
```

* bubbleSort
* countingSort
* heapSort
* insertionSort
* quicksort
* radixSort
* selectionSort
* shellSort
* shortBubbleSort

#### String algorithms

```javascript
require('algorithms/string');
// or
require('algorithms').String;
```

* hamming
* huffman
 * decode
 * encode
* knuthMorrisPratt
* levenshtein
* longestCommonSubsequence
* longestCommonSubstring
* rabinKarp
