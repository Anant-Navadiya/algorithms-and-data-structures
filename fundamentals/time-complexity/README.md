# Time Complexity

The time complexity is the computational complexity that describes the amount of computer time it takes to run an
algorithm. Time complexity is commonly estimated by counting the number of elementary operations performed by the
algorithm, supposing that each elementary operation takes a fixed amount of time to perform.

Since an algorithm's running time may vary among different inputs of the same size, one commonly considers the
worst-case time complexity, which is the maximum amount of time required for inputs of a given size.

## Common Time Complexities
| Name                                     | Time Complexity          |
|------------------------------------------|--------------------------|
| Constant Time                            | O(1)                     |
| Inverse Ackermann Time                   | O(α(n))                  |
| Iterated Logarithmic Time                | O(log* n)                |
| Log-Logarithmic Time                     | O(log log n)             |
| Logarithmic Time                         | O(log n)                 |
| Polylogarithmic Time                     | poly(log n)              |
| Fractional Power                         | O(n^c), where 0 < c < 1  |
| Linear Time                              | O(n)                     |
| n Log-Star n Time                        | O(n log* n)              |
| Linearithmic Time                        | O(n log n)               |
| Quasilinear Time                         | n poly(log n)            |
| Quadratic Time                           | O(n²)                    |
| Cubic Time                               | O(n³)                    |
| Polynomial Time                          | 2^O(log n) = poly(n)     |
| Quasi-Polynomial Time                    | 2^poly(log n)            |
| Sub-Exponential Time (First Definition)  | O(2^(n^ε)) for all ε > 0 |
| Sub-Exponential Time (Second Definition) | 2^o(n)                   |
| Exponential Time (with Linear Exponent)  | 2^O(n)                   |
| Factorial Time                           | O(n)! = 2^O(n log n)     |
| Exponential Time                         | 2^poly(n)                |
| Double Exponential Time                  | 2^(2^poly(n))            |

## Common Data Structure Operations

| Data Structure     | Average Access | Average Search | Average Insertion | Average Deletion | Worst Access | Worst Search | Worst Insertion | Worst Deletion |
|--------------------|----------------|----------------|-------------------|------------------|--------------|--------------|-----------------|----------------|
| Array              | Θ(1)           | Θ(n)           | Θ(n)              | Θ(n)             | O(1)         | O(n)         | O(n)            | O(n)           |
| Stack              | Θ(n)           | Θ(n)           | Θ(1)              | Θ(1)             | O(n)         | O(n)         | O(1)            | O(1)           |
| Queue              | Θ(n)           | Θ(n)           | Θ(1)              | Θ(1)             | O(n)         | O(n)         | O(1)            | O(1)           |
| Singly-Linked List | Θ(n)           | Θ(n)           | Θ(1)              | Θ(1)             | O(n)         | O(n)         | O(1)            | O(1)           |
| Doubly-Linked List | Θ(n)           | Θ(n)           | Θ(1)              | Θ(1)             | O(n)         | O(n)         | O(1)            | O(1)           |
| Skip List          | Θ(log(n))      | Θ(log(n))      | Θ(log(n))         | Θ(log(n))        | O(n)         | O(n)         | O(n)            | O(n)           |
| Hash Table         | N/A            | Θ(1)           | Θ(1)              | Θ(1)             | N/A          | O(n)         | O(n)            | O(n)           |
| Binary Search Tree | Θ(log(n))      | Θ(log(n))      | Θ(log(n))         | Θ(log(n))        | O(n)         | O(n)         | O(n)            | O(n)           |
| Cartesian Tree     | N/A            | Θ(log(n))      | Θ(log(n))         | Θ(log(n))        | N/A          | O(n)         | O(n)            | O(n)           |
| B-Tree             | Θ(log(n))      | Θ(log(n))      | Θ(log(n))         | Θ(log(n))        | O(log(n))    | O(log(n))    | O(log(n))       | O(log(n))      |
| Red-Black Tree     | Θ(log(n))      | Θ(log(n))      | Θ(log(n))         | Θ(log(n))        | O(log(n))    | O(log(n))    | O(log(n))       | O(log(n))      |
| Splay Tree         | N/A            | Θ(log(n))      | Θ(log(n))         | Θ(log(n))        | N/A          | O(log(n))    | O(log(n))       | O(log(n))      |
| AVL Tree           | Θ(log(n))      | Θ(log(n))      | Θ(log(n))         | Θ(log(n))        | O(log(n))    | O(log(n))    | O(log(n))       | O(log(n))      |

## Array Sorting Algorithms

| Algorithm      | Best Time   | Average Time  | Worst Time    |
|----------------|-------------|---------------|---------------|
| Quicksort      | Ω(n log(n)) | Θ(n log(n))   | O(n²)         |
| Mergesort      | Ω(n log(n)) | Θ(n log(n))   | O(n log(n))   |
| Timsort        | Ω(n)        | Θ(n log(n))   | O(n log(n))   |
| Heapsort       | Ω(n log(n)) | Θ(n log(n))   | O(n log(n))   |
| Bubble Sort    | Ω(n)        | Θ(n²)         | O(n²)         |
| Insertion Sort | Ω(n)        | Θ(n²)         | O(n²)         |
| Selection Sort | Ω(n²)       | Θ(n²)         | O(n²)         |
| Tree Sort      | Ω(n log(n)) | Θ(n log(n))   | O(n²)         |
| Shell Sort     | Ω(n log(n)) | Θ(n(log(n))²) | O(n(log(n))²) |
| Bucket Sort    | Ω(n+k)      | Θ(n+k)        | O(n²)         |
| Radix Sort     | Ω(nk)       | Θ(nk)         | O(nk)         |
| Counting Sort  | Ω(n+k)      | Θ(n+k)        | O(n+k)        |
| Cubesort       | Ω(n)        | Θ(n log(n))   | O(n log(n))   |

## References

* https://en.wikipedia.org/wiki/Time_complexity
* https://www.bigocheatsheet.com/