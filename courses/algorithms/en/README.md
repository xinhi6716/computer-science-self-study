# Algorithms

39 chapter/appendix units with separate teaching material, exercises, and worked solutions.

[Course home](../README.md)

**[Download the full course handout](complete-handout.pdf)** (linked contents, chapter bookmarks, and book page numbers)

Teaching slides are for screen reading. Handouts place the same slides vertically on A4. Exercises and solutions are separate; attempt the exercises before opening the solutions.

Follow analysis → design → theory, with sorting and data structures in a separate toolbox. Chapter numbers retain the textbook numbering. Skip familiar toolbox material; FFT sits with divide-and-conquer, and disjoint sets precede MSTs.

**Themes:** [1. Analysis: growth, probability, and amortized costs](#analysis) · [2. Toolbox: sorting and data structures](#tools) · [3. Recurrence and divide-and-conquer](#recurrence) · [4. Design: dynamic programming and greedy algorithms](#design) · [5. Graphs: traversal, connectivity, shortest paths, and flow](#graphs) · [6. Computational geometry](#geometry) · [7. Further methods: parallelism, matrices, optimization, and strings](#extensions) · [8. Theory: intractability and approximation](#theory) · [Reference appendices: sums, sets, probability, and matrices](#appendices)

<a id="analysis"></a>

## 1. Analysis: growth, probability, and amortized costs

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [01 · The role of algorithms in computing](chapters/ch01-role-of-algorithms/README.md) | [Teaching](chapters/ch01-role-of-algorithms/slides-teaching.pdf) · [Handout](chapters/ch01-role-of-algorithms/slides-handout.pdf) | [Exercises](chapters/ch01-role-of-algorithms/exercises.pdf) · [Solutions](chapters/ch01-role-of-algorithms/solutions.pdf) |
| [02 · Getting started](chapters/ch02-getting-started/README.md) | [Teaching](chapters/ch02-getting-started/slides-teaching.pdf) · [Handout](chapters/ch02-getting-started/slides-handout.pdf) | [Exercises](chapters/ch02-getting-started/exercises.pdf) · [Solutions](chapters/ch02-getting-started/solutions.pdf) |
| [03 · Growth of functions](chapters/ch03-growth-of-functions/README.md) | [Teaching](chapters/ch03-growth-of-functions/slides-teaching.pdf) · [Handout](chapters/ch03-growth-of-functions/slides-handout.pdf) | [Exercises](chapters/ch03-growth-of-functions/exercises.pdf) · [Solutions](chapters/ch03-growth-of-functions/solutions.pdf) |
| [05 · Probabilistic analysis and randomized algorithms](chapters/ch05-probabilistic-analysis/README.md) | [Teaching](chapters/ch05-probabilistic-analysis/slides-teaching.pdf) · [Handout](chapters/ch05-probabilistic-analysis/slides-handout.pdf) | [Exercises](chapters/ch05-probabilistic-analysis/exercises.pdf) · [Solutions](chapters/ch05-probabilistic-analysis/solutions.pdf) |
| [17 · Amortized analysis](chapters/ch17-amortized-analysis/README.md) | [Teaching](chapters/ch17-amortized-analysis/slides-teaching.pdf) · [Handout](chapters/ch17-amortized-analysis/slides-handout.pdf) | [Exercises](chapters/ch17-amortized-analysis/exercises.pdf) · [Solutions](chapters/ch17-amortized-analysis/solutions.pdf) |

<a id="tools"></a>

## 2. Toolbox: sorting and data structures

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [06 · Heapsort](chapters/ch06-heapsort/README.md) | [Teaching](chapters/ch06-heapsort/slides-teaching.pdf) · [Handout](chapters/ch06-heapsort/slides-handout.pdf) | [Exercises](chapters/ch06-heapsort/exercises.pdf) · [Solutions](chapters/ch06-heapsort/solutions.pdf) |
| [08 · Sorting in linear time](chapters/ch08-sorting-in-linear-time/README.md) | [Teaching](chapters/ch08-sorting-in-linear-time/slides-teaching.pdf) · [Handout](chapters/ch08-sorting-in-linear-time/slides-handout.pdf) | [Exercises](chapters/ch08-sorting-in-linear-time/exercises.pdf) · [Solutions](chapters/ch08-sorting-in-linear-time/solutions.pdf) |
| [10 · Elementary data structures](chapters/ch10-elementary-data-structures/README.md) | [Teaching](chapters/ch10-elementary-data-structures/slides-teaching.pdf) · [Handout](chapters/ch10-elementary-data-structures/slides-handout.pdf) | [Exercises](chapters/ch10-elementary-data-structures/exercises.pdf) · [Solutions](chapters/ch10-elementary-data-structures/solutions.pdf) |
| [11 · Hash tables](chapters/ch11-hash-tables/README.md) | [Teaching](chapters/ch11-hash-tables/slides-teaching.pdf) · [Handout](chapters/ch11-hash-tables/slides-handout.pdf) | [Exercises](chapters/ch11-hash-tables/exercises.pdf) · [Solutions](chapters/ch11-hash-tables/solutions.pdf) |
| [12 · Binary search trees](chapters/ch12-binary-search-trees/README.md) | [Teaching](chapters/ch12-binary-search-trees/slides-teaching.pdf) · [Handout](chapters/ch12-binary-search-trees/slides-handout.pdf) | [Exercises](chapters/ch12-binary-search-trees/exercises.pdf) · [Solutions](chapters/ch12-binary-search-trees/solutions.pdf) |
| [13 · Red-black trees](chapters/ch13-red-black-trees/README.md) | [Teaching](chapters/ch13-red-black-trees/slides-teaching.pdf) · [Handout](chapters/ch13-red-black-trees/slides-handout.pdf) | [Exercises](chapters/ch13-red-black-trees/exercises.pdf) · [Solutions](chapters/ch13-red-black-trees/solutions.pdf) |
| [14 · Augmenting data structures](chapters/ch14-augmenting-data-structures/README.md) | [Teaching](chapters/ch14-augmenting-data-structures/slides-teaching.pdf) · [Handout](chapters/ch14-augmenting-data-structures/slides-handout.pdf) | [Exercises](chapters/ch14-augmenting-data-structures/exercises.pdf) · [Solutions](chapters/ch14-augmenting-data-structures/solutions.pdf) |
| [18 · B-trees](chapters/ch18-b-trees/README.md) | [Teaching](chapters/ch18-b-trees/slides-teaching.pdf) · [Handout](chapters/ch18-b-trees/slides-handout.pdf) | [Exercises](chapters/ch18-b-trees/exercises.pdf) · [Solutions](chapters/ch18-b-trees/solutions.pdf) |
| [19 · Fibonacci heaps](chapters/ch19-fibonacci-heaps/README.md) | [Teaching](chapters/ch19-fibonacci-heaps/slides-teaching.pdf) · [Handout](chapters/ch19-fibonacci-heaps/slides-handout.pdf) | [Exercises](chapters/ch19-fibonacci-heaps/exercises.pdf) · [Solutions](chapters/ch19-fibonacci-heaps/solutions.pdf) |
| [20 · van Emde Boas trees](chapters/ch20-van-emde-boas-trees/README.md) | [Teaching](chapters/ch20-van-emde-boas-trees/slides-teaching.pdf) · [Handout](chapters/ch20-van-emde-boas-trees/slides-handout.pdf) | [Exercises](chapters/ch20-van-emde-boas-trees/exercises.pdf) · [Solutions](chapters/ch20-van-emde-boas-trees/solutions.pdf) |

<a id="recurrence"></a>

## 3. Recurrence and divide-and-conquer

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [04 · Divide and conquer](chapters/ch04-divide-and-conquer/README.md) | [Teaching](chapters/ch04-divide-and-conquer/slides-teaching.pdf) · [Handout](chapters/ch04-divide-and-conquer/slides-handout.pdf) | [Exercises](chapters/ch04-divide-and-conquer/exercises.pdf) · [Solutions](chapters/ch04-divide-and-conquer/solutions.pdf) |
| [07 · Quicksort](chapters/ch07-quicksort/README.md) | [Teaching](chapters/ch07-quicksort/slides-teaching.pdf) · [Handout](chapters/ch07-quicksort/slides-handout.pdf) | [Exercises](chapters/ch07-quicksort/exercises.pdf) · [Solutions](chapters/ch07-quicksort/solutions.pdf) |
| [09 · Medians and order statistics](chapters/ch09-medians-order-statistics/README.md) | [Teaching](chapters/ch09-medians-order-statistics/slides-teaching.pdf) · [Handout](chapters/ch09-medians-order-statistics/slides-handout.pdf) | [Exercises](chapters/ch09-medians-order-statistics/exercises.pdf) · [Solutions](chapters/ch09-medians-order-statistics/solutions.pdf) |
| [30 · Polynomials and FFT](chapters/ch30-polynomials-and-fft/README.md) | [Teaching](chapters/ch30-polynomials-and-fft/slides-teaching.pdf) · [Handout](chapters/ch30-polynomials-and-fft/slides-handout.pdf) | [Exercises](chapters/ch30-polynomials-and-fft/exercises.pdf) · [Solutions](chapters/ch30-polynomials-and-fft/solutions.pdf) |

<a id="design"></a>

## 4. Design: dynamic programming and greedy algorithms

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [15 · Dynamic programming](chapters/ch15-dynamic-programming/README.md) | [Teaching](chapters/ch15-dynamic-programming/slides-teaching.pdf) · [Handout](chapters/ch15-dynamic-programming/slides-handout.pdf) | [Exercises](chapters/ch15-dynamic-programming/exercises.pdf) · [Solutions](chapters/ch15-dynamic-programming/solutions.pdf) |
| [16 · Greedy algorithms](chapters/ch16-greedy-algorithms/README.md) | [Teaching](chapters/ch16-greedy-algorithms/slides-teaching.pdf) · [Handout](chapters/ch16-greedy-algorithms/slides-handout.pdf) | [Exercises](chapters/ch16-greedy-algorithms/exercises.pdf) · [Solutions](chapters/ch16-greedy-algorithms/solutions.pdf) |

<a id="graphs"></a>

## 5. Graphs: traversal, connectivity, shortest paths, and flow

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [22 · Elementary graph algorithms](chapters/ch22-elementary-graph-algorithms/README.md) | [Teaching](chapters/ch22-elementary-graph-algorithms/slides-teaching.pdf) · [Handout](chapters/ch22-elementary-graph-algorithms/slides-handout.pdf) | [Exercises](chapters/ch22-elementary-graph-algorithms/exercises.pdf) · [Solutions](chapters/ch22-elementary-graph-algorithms/solutions.pdf) |
| [21 · Disjoint sets](chapters/ch21-disjoint-sets/README.md) | [Teaching](chapters/ch21-disjoint-sets/slides-teaching.pdf) · [Handout](chapters/ch21-disjoint-sets/slides-handout.pdf) | [Exercises](chapters/ch21-disjoint-sets/exercises.pdf) · [Solutions](chapters/ch21-disjoint-sets/solutions.pdf) |
| [23 · Minimum spanning trees](chapters/ch23-minimum-spanning-trees/README.md) | [Teaching](chapters/ch23-minimum-spanning-trees/slides-teaching.pdf) · [Handout](chapters/ch23-minimum-spanning-trees/slides-handout.pdf) | [Exercises](chapters/ch23-minimum-spanning-trees/exercises.pdf) · [Solutions](chapters/ch23-minimum-spanning-trees/solutions.pdf) |
| [24 · Single-source shortest paths](chapters/ch24-single-source-shortest-paths/README.md) | [Teaching](chapters/ch24-single-source-shortest-paths/slides-teaching.pdf) · [Handout](chapters/ch24-single-source-shortest-paths/slides-handout.pdf) | [Exercises](chapters/ch24-single-source-shortest-paths/exercises.pdf) · [Solutions](chapters/ch24-single-source-shortest-paths/solutions.pdf) |
| [25 · All-pairs shortest paths](chapters/ch25-all-pairs-shortest-paths/README.md) | [Teaching](chapters/ch25-all-pairs-shortest-paths/slides-teaching.pdf) · [Handout](chapters/ch25-all-pairs-shortest-paths/slides-handout.pdf) | [Exercises](chapters/ch25-all-pairs-shortest-paths/exercises.pdf) · [Solutions](chapters/ch25-all-pairs-shortest-paths/solutions.pdf) |
| [26 · Maximum flow](chapters/ch26-maximum-flow/README.md) | [Teaching](chapters/ch26-maximum-flow/slides-teaching.pdf) · [Handout](chapters/ch26-maximum-flow/slides-handout.pdf) | [Exercises](chapters/ch26-maximum-flow/exercises.pdf) · [Solutions](chapters/ch26-maximum-flow/solutions.pdf) |

<a id="geometry"></a>

## 6. Computational geometry

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [33 · Computational geometry](chapters/ch33-computational-geometry/README.md) | [Teaching](chapters/ch33-computational-geometry/slides-teaching.pdf) · [Handout](chapters/ch33-computational-geometry/slides-handout.pdf) | [Exercises](chapters/ch33-computational-geometry/exercises.pdf) · [Solutions](chapters/ch33-computational-geometry/solutions.pdf) |

<a id="extensions"></a>

## 7. Further methods: parallelism, matrices, optimization, and strings

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [27 · Multithreaded algorithms](chapters/ch27-multithreaded-algorithms/README.md) | [Teaching](chapters/ch27-multithreaded-algorithms/slides-teaching.pdf) · [Handout](chapters/ch27-multithreaded-algorithms/slides-handout.pdf) | [Exercises](chapters/ch27-multithreaded-algorithms/exercises.pdf) · [Solutions](chapters/ch27-multithreaded-algorithms/solutions.pdf) |
| [28 · Matrix operations](chapters/ch28-matrix-operations/README.md) | [Teaching](chapters/ch28-matrix-operations/slides-teaching.pdf) · [Handout](chapters/ch28-matrix-operations/slides-handout.pdf) | [Exercises](chapters/ch28-matrix-operations/exercises.pdf) · [Solutions](chapters/ch28-matrix-operations/solutions.pdf) |
| [29 · Linear programming](chapters/ch29-linear-programming/README.md) | [Teaching](chapters/ch29-linear-programming/slides-teaching.pdf) · [Handout](chapters/ch29-linear-programming/slides-handout.pdf) | [Exercises](chapters/ch29-linear-programming/exercises.pdf) · [Solutions](chapters/ch29-linear-programming/solutions.pdf) |
| [31 · Number-theoretic algorithms](chapters/ch31-number-theoretic-algorithms/README.md) | [Teaching](chapters/ch31-number-theoretic-algorithms/slides-teaching.pdf) · [Handout](chapters/ch31-number-theoretic-algorithms/slides-handout.pdf) | [Exercises](chapters/ch31-number-theoretic-algorithms/exercises.pdf) · [Solutions](chapters/ch31-number-theoretic-algorithms/solutions.pdf) |
| [32 · String matching](chapters/ch32-string-matching/README.md) | [Teaching](chapters/ch32-string-matching/slides-teaching.pdf) · [Handout](chapters/ch32-string-matching/slides-handout.pdf) | [Exercises](chapters/ch32-string-matching/exercises.pdf) · [Solutions](chapters/ch32-string-matching/solutions.pdf) |

<a id="theory"></a>

## 8. Theory: intractability and approximation

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [34 · NP-completeness](chapters/ch34-np-completeness/README.md) | [Teaching](chapters/ch34-np-completeness/slides-teaching.pdf) · [Handout](chapters/ch34-np-completeness/slides-handout.pdf) | [Exercises](chapters/ch34-np-completeness/exercises.pdf) · [Solutions](chapters/ch34-np-completeness/solutions.pdf) |
| [35 · Approximation algorithms](chapters/ch35-approximation-algorithms/README.md) | [Teaching](chapters/ch35-approximation-algorithms/slides-teaching.pdf) · [Handout](chapters/ch35-approximation-algorithms/slides-handout.pdf) | [Exercises](chapters/ch35-approximation-algorithms/exercises.pdf) · [Solutions](chapters/ch35-approximation-algorithms/solutions.pdf) |

<a id="appendices"></a>

## Reference appendices: sums, sets, probability, and matrices

| Chapter | Slide PDFs | Practice PDFs |
|---|---|---|
| [A · Summations](chapters/chA-summations/README.md) | [Teaching](chapters/chA-summations/slides-teaching.pdf) · [Handout](chapters/chA-summations/slides-handout.pdf) | [Exercises](chapters/chA-summations/exercises.pdf) · [Solutions](chapters/chA-summations/solutions.pdf) |
| [B · Sets, relations, functions, graphs, and trees](chapters/chB-sets-relations-functions-graphs-trees/README.md) | [Teaching](chapters/chB-sets-relations-functions-graphs-trees/slides-teaching.pdf) · [Handout](chapters/chB-sets-relations-functions-graphs-trees/slides-handout.pdf) | [Exercises](chapters/chB-sets-relations-functions-graphs-trees/exercises.pdf) · [Solutions](chapters/chB-sets-relations-functions-graphs-trees/solutions.pdf) |
| [C · Counting and probability](chapters/chC-counting-and-probability/README.md) | [Teaching](chapters/chC-counting-and-probability/slides-teaching.pdf) · [Handout](chapters/chC-counting-and-probability/slides-handout.pdf) | [Exercises](chapters/chC-counting-and-probability/exercises.pdf) · [Solutions](chapters/chC-counting-and-probability/solutions.pdf) |
| [D · Matrices](chapters/chD-matrices/README.md) | [Teaching](chapters/chD-matrices/slides-teaching.pdf) · [Handout](chapters/chD-matrices/slides-handout.pdf) | [Exercises](chapters/chD-matrices/exercises.pdf) · [Solutions](chapters/chD-matrices/solutions.pdf) |

