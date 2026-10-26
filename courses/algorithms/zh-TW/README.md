# 演算法

[科目首頁](../README.md)

**[下載整科完整版講義](complete-handout.pdf)**

依下列順序學習。前兩章已整合分析與正確性、遞迴與分治；後續主題目前連到既有單元，會隨逐章修訂繼續整合，原書章號保留供查找。

前兩章提供 16:9 播放版，以及每張紙上下各一頁 4:3 的 A4 講義；講義合併相依內容，保留定義、證明與數例。後續單元暫沿用原版面，隨逐章修訂更新。練習與詳解各自獨立，建議先作答再對照。

[一、演算法分析與正確性](#analysis) · [二、遞迴、遞迴式與分治](#recurrence) · [三、排序、選擇與隨機分析](#sorting) · [四、資料結構與攤銷分析](#structures) · [五、動態規劃](#dp) · [六、貪心方法](#greedy) · [七、圖的走訪與連通](#traversal) · [八、最小生成樹與最短路徑](#paths) · [九、網路流](#flow) · [十、計算幾何](#geometry) · [十一、計算複雜度與近似](#complexity) · [十二、字串比對](#strings) · [十三、矩陣運算與 FFT](#matrixfft) · [十四、數論演算法](#number) · [十五、線性規劃](#lp) · [十六、平行演算法](#parallel) · [查用附錄](#appendices)

<a id="analysis"></a>

## 一、演算法分析與正確性

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [演算法分析與正確性](chapters/ch01-analysis-correctness/README.md) | [播放](chapters/ch01-analysis-correctness/slides-teaching.pdf) · [講義](chapters/ch01-analysis-correctness/slides-handout.pdf) | [練習](chapters/ch01-analysis-correctness/exercises.pdf) · [詳解](chapters/ch01-analysis-correctness/solutions.pdf) |

<a id="recurrence"></a>

## 二、遞迴、遞迴式與分治

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [遞迴、遞迴式與分治](chapters/ch02-recursion-divide-conquer/README.md) | [播放](chapters/ch02-recursion-divide-conquer/slides-teaching.pdf) · [講義](chapters/ch02-recursion-divide-conquer/slides-handout.pdf) | [練習](chapters/ch02-recursion-divide-conquer/exercises.pdf) · [詳解](chapters/ch02-recursion-divide-conquer/solutions.pdf) |

<a id="sorting"></a>

## 三、排序、選擇與隨機分析

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [05 機率分析與隨機演算法](chapters/ch05-probabilistic-analysis/README.md) | [播放](chapters/ch05-probabilistic-analysis/slides-teaching.pdf) · [講義](chapters/ch05-probabilistic-analysis/slides-handout.pdf) | [練習](chapters/ch05-probabilistic-analysis/exercises.pdf) · [詳解](chapters/ch05-probabilistic-analysis/solutions.pdf) |
| [06 堆積排序](chapters/ch06-heapsort/README.md) | [播放](chapters/ch06-heapsort/slides-teaching.pdf) · [講義](chapters/ch06-heapsort/slides-handout.pdf) | [練習](chapters/ch06-heapsort/exercises.pdf) · [詳解](chapters/ch06-heapsort/solutions.pdf) |
| [07 快速排序](chapters/ch07-quicksort/README.md) | [播放](chapters/ch07-quicksort/slides-teaching.pdf) · [講義](chapters/ch07-quicksort/slides-handout.pdf) | [練習](chapters/ch07-quicksort/exercises.pdf) · [詳解](chapters/ch07-quicksort/solutions.pdf) |
| [08 線性時間排序](chapters/ch08-sorting-in-linear-time/README.md) | [播放](chapters/ch08-sorting-in-linear-time/slides-teaching.pdf) · [講義](chapters/ch08-sorting-in-linear-time/slides-handout.pdf) | [練習](chapters/ch08-sorting-in-linear-time/exercises.pdf) · [詳解](chapters/ch08-sorting-in-linear-time/solutions.pdf) |
| [09 中位數與次序統計量](chapters/ch09-medians-order-statistics/README.md) | [播放](chapters/ch09-medians-order-statistics/slides-teaching.pdf) · [講義](chapters/ch09-medians-order-statistics/slides-handout.pdf) | [練習](chapters/ch09-medians-order-statistics/exercises.pdf) · [詳解](chapters/ch09-medians-order-statistics/solutions.pdf) |

<a id="structures"></a>

## 四、資料結構與攤銷分析

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [10 基本資料結構](chapters/ch10-elementary-data-structures/README.md) | [播放](chapters/ch10-elementary-data-structures/slides-teaching.pdf) · [講義](chapters/ch10-elementary-data-structures/slides-handout.pdf) | [練習](chapters/ch10-elementary-data-structures/exercises.pdf) · [詳解](chapters/ch10-elementary-data-structures/solutions.pdf) |
| [11 雜湊表](chapters/ch11-hash-tables/README.md) | [播放](chapters/ch11-hash-tables/slides-teaching.pdf) · [講義](chapters/ch11-hash-tables/slides-handout.pdf) | [練習](chapters/ch11-hash-tables/exercises.pdf) · [詳解](chapters/ch11-hash-tables/solutions.pdf) |
| [12 二元搜尋樹](chapters/ch12-binary-search-trees/README.md) | [播放](chapters/ch12-binary-search-trees/slides-teaching.pdf) · [講義](chapters/ch12-binary-search-trees/slides-handout.pdf) | [練習](chapters/ch12-binary-search-trees/exercises.pdf) · [詳解](chapters/ch12-binary-search-trees/solutions.pdf) |
| [13 紅黑樹](chapters/ch13-red-black-trees/README.md) | [播放](chapters/ch13-red-black-trees/slides-teaching.pdf) · [講義](chapters/ch13-red-black-trees/slides-handout.pdf) | [練習](chapters/ch13-red-black-trees/exercises.pdf) · [詳解](chapters/ch13-red-black-trees/solutions.pdf) |
| [14 擴充資料結構](chapters/ch14-augmenting-data-structures/README.md) | [播放](chapters/ch14-augmenting-data-structures/slides-teaching.pdf) · [講義](chapters/ch14-augmenting-data-structures/slides-handout.pdf) | [練習](chapters/ch14-augmenting-data-structures/exercises.pdf) · [詳解](chapters/ch14-augmenting-data-structures/solutions.pdf) |
| [17 攤銷分析](chapters/ch17-amortized-analysis/README.md) | [播放](chapters/ch17-amortized-analysis/slides-teaching.pdf) · [講義](chapters/ch17-amortized-analysis/slides-handout.pdf) | [練習](chapters/ch17-amortized-analysis/exercises.pdf) · [詳解](chapters/ch17-amortized-analysis/solutions.pdf) |
| [18 B 樹](chapters/ch18-b-trees/README.md) | [播放](chapters/ch18-b-trees/slides-teaching.pdf) · [講義](chapters/ch18-b-trees/slides-handout.pdf) | [練習](chapters/ch18-b-trees/exercises.pdf) · [詳解](chapters/ch18-b-trees/solutions.pdf) |
| [19 費氏堆積](chapters/ch19-fibonacci-heaps/README.md) | [播放](chapters/ch19-fibonacci-heaps/slides-teaching.pdf) · [講義](chapters/ch19-fibonacci-heaps/slides-handout.pdf) | [練習](chapters/ch19-fibonacci-heaps/exercises.pdf) · [詳解](chapters/ch19-fibonacci-heaps/solutions.pdf) |
| [20 van Emde Boas 樹](chapters/ch20-van-emde-boas-trees/README.md) | [播放](chapters/ch20-van-emde-boas-trees/slides-teaching.pdf) · [講義](chapters/ch20-van-emde-boas-trees/slides-handout.pdf) | [練習](chapters/ch20-van-emde-boas-trees/exercises.pdf) · [詳解](chapters/ch20-van-emde-boas-trees/solutions.pdf) |

<a id="dp"></a>

## 五、動態規劃

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [15 動態規劃](chapters/ch15-dynamic-programming/README.md) | [播放](chapters/ch15-dynamic-programming/slides-teaching.pdf) · [講義](chapters/ch15-dynamic-programming/slides-handout.pdf) | [練習](chapters/ch15-dynamic-programming/exercises.pdf) · [詳解](chapters/ch15-dynamic-programming/solutions.pdf) |

<a id="greedy"></a>

## 六、貪心方法

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [16 貪婪演算法](chapters/ch16-greedy-algorithms/README.md) | [播放](chapters/ch16-greedy-algorithms/slides-teaching.pdf) · [講義](chapters/ch16-greedy-algorithms/slides-handout.pdf) | [練習](chapters/ch16-greedy-algorithms/exercises.pdf) · [詳解](chapters/ch16-greedy-algorithms/solutions.pdf) |

<a id="traversal"></a>

## 七、圖的走訪與連通

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [22 基礎圖演算法](chapters/ch22-elementary-graph-algorithms/README.md) | [播放](chapters/ch22-elementary-graph-algorithms/slides-teaching.pdf) · [講義](chapters/ch22-elementary-graph-algorithms/slides-handout.pdf) | [練習](chapters/ch22-elementary-graph-algorithms/exercises.pdf) · [詳解](chapters/ch22-elementary-graph-algorithms/solutions.pdf) |

<a id="paths"></a>

## 八、最小生成樹與最短路徑

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [21 不相交集合](chapters/ch21-disjoint-sets/README.md) | [播放](chapters/ch21-disjoint-sets/slides-teaching.pdf) · [講義](chapters/ch21-disjoint-sets/slides-handout.pdf) | [練習](chapters/ch21-disjoint-sets/exercises.pdf) · [詳解](chapters/ch21-disjoint-sets/solutions.pdf) |
| [23 最小生成樹](chapters/ch23-minimum-spanning-trees/README.md) | [播放](chapters/ch23-minimum-spanning-trees/slides-teaching.pdf) · [講義](chapters/ch23-minimum-spanning-trees/slides-handout.pdf) | [練習](chapters/ch23-minimum-spanning-trees/exercises.pdf) · [詳解](chapters/ch23-minimum-spanning-trees/solutions.pdf) |
| [24 單源最短路徑](chapters/ch24-single-source-shortest-paths/README.md) | [播放](chapters/ch24-single-source-shortest-paths/slides-teaching.pdf) · [講義](chapters/ch24-single-source-shortest-paths/slides-handout.pdf) | [練習](chapters/ch24-single-source-shortest-paths/exercises.pdf) · [詳解](chapters/ch24-single-source-shortest-paths/solutions.pdf) |
| [25 全點對最短路徑](chapters/ch25-all-pairs-shortest-paths/README.md) | [播放](chapters/ch25-all-pairs-shortest-paths/slides-teaching.pdf) · [講義](chapters/ch25-all-pairs-shortest-paths/slides-handout.pdf) | [練習](chapters/ch25-all-pairs-shortest-paths/exercises.pdf) · [詳解](chapters/ch25-all-pairs-shortest-paths/solutions.pdf) |

<a id="flow"></a>

## 九、網路流

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [26 最大流](chapters/ch26-maximum-flow/README.md) | [播放](chapters/ch26-maximum-flow/slides-teaching.pdf) · [講義](chapters/ch26-maximum-flow/slides-handout.pdf) | [練習](chapters/ch26-maximum-flow/exercises.pdf) · [詳解](chapters/ch26-maximum-flow/solutions.pdf) |

<a id="geometry"></a>

## 十、計算幾何

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [33 計算幾何](chapters/ch33-computational-geometry/README.md) | [播放](chapters/ch33-computational-geometry/slides-teaching.pdf) · [講義](chapters/ch33-computational-geometry/slides-handout.pdf) | [練習](chapters/ch33-computational-geometry/exercises.pdf) · [詳解](chapters/ch33-computational-geometry/solutions.pdf) |

<a id="complexity"></a>

## 十一、計算複雜度與近似

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [34 NP 完備性](chapters/ch34-np-completeness/README.md) | [播放](chapters/ch34-np-completeness/slides-teaching.pdf) · [講義](chapters/ch34-np-completeness/slides-handout.pdf) | [練習](chapters/ch34-np-completeness/exercises.pdf) · [詳解](chapters/ch34-np-completeness/solutions.pdf) |
| [35 近似演算法](chapters/ch35-approximation-algorithms/README.md) | [播放](chapters/ch35-approximation-algorithms/slides-teaching.pdf) · [講義](chapters/ch35-approximation-algorithms/slides-handout.pdf) | [練習](chapters/ch35-approximation-algorithms/exercises.pdf) · [詳解](chapters/ch35-approximation-algorithms/solutions.pdf) |

<a id="strings"></a>

## 十二、字串比對

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [32 字串匹配](chapters/ch32-string-matching/README.md) | [播放](chapters/ch32-string-matching/slides-teaching.pdf) · [講義](chapters/ch32-string-matching/slides-handout.pdf) | [練習](chapters/ch32-string-matching/exercises.pdf) · [詳解](chapters/ch32-string-matching/solutions.pdf) |

<a id="matrixfft"></a>

## 十三、矩陣運算與 FFT

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [28 矩陣運算](chapters/ch28-matrix-operations/README.md) | [播放](chapters/ch28-matrix-operations/slides-teaching.pdf) · [講義](chapters/ch28-matrix-operations/slides-handout.pdf) | [練習](chapters/ch28-matrix-operations/exercises.pdf) · [詳解](chapters/ch28-matrix-operations/solutions.pdf) |
| [30 多項式與快速傅立葉轉換](chapters/ch30-polynomials-and-fft/README.md) | [播放](chapters/ch30-polynomials-and-fft/slides-teaching.pdf) · [講義](chapters/ch30-polynomials-and-fft/slides-handout.pdf) | [練習](chapters/ch30-polynomials-and-fft/exercises.pdf) · [詳解](chapters/ch30-polynomials-and-fft/solutions.pdf) |

<a id="number"></a>

## 十四、數論演算法

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [31 數論演算法](chapters/ch31-number-theoretic-algorithms/README.md) | [播放](chapters/ch31-number-theoretic-algorithms/slides-teaching.pdf) · [講義](chapters/ch31-number-theoretic-algorithms/slides-handout.pdf) | [練習](chapters/ch31-number-theoretic-algorithms/exercises.pdf) · [詳解](chapters/ch31-number-theoretic-algorithms/solutions.pdf) |

<a id="lp"></a>

## 十五、線性規劃

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [29 線性規劃](chapters/ch29-linear-programming/README.md) | [播放](chapters/ch29-linear-programming/slides-teaching.pdf) · [講義](chapters/ch29-linear-programming/slides-handout.pdf) | [練習](chapters/ch29-linear-programming/exercises.pdf) · [詳解](chapters/ch29-linear-programming/solutions.pdf) |

<a id="parallel"></a>

## 十六、平行演算法

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [27 多執行緒演算法](chapters/ch27-multithreaded-algorithms/README.md) | [播放](chapters/ch27-multithreaded-algorithms/slides-teaching.pdf) · [講義](chapters/ch27-multithreaded-algorithms/slides-handout.pdf) | [練習](chapters/ch27-multithreaded-algorithms/exercises.pdf) · [詳解](chapters/ch27-multithreaded-algorithms/solutions.pdf) |

<a id="appendices"></a>

## 查用附錄

| 主題入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [A 求和](chapters/chA-summations/README.md) | [播放](chapters/chA-summations/slides-teaching.pdf) · [講義](chapters/chA-summations/slides-handout.pdf) | [練習](chapters/chA-summations/exercises.pdf) · [詳解](chapters/chA-summations/solutions.pdf) |
| [B 集合、關係、函數、圖與樹](chapters/chB-sets-relations-functions-graphs-trees/README.md) | [播放](chapters/chB-sets-relations-functions-graphs-trees/slides-teaching.pdf) · [講義](chapters/chB-sets-relations-functions-graphs-trees/slides-handout.pdf) | [練習](chapters/chB-sets-relations-functions-graphs-trees/exercises.pdf) · [詳解](chapters/chB-sets-relations-functions-graphs-trees/solutions.pdf) |
| [C 計數與機率](chapters/chC-counting-and-probability/README.md) | [播放](chapters/chC-counting-and-probability/slides-teaching.pdf) · [講義](chapters/chC-counting-and-probability/slides-handout.pdf) | [練習](chapters/chC-counting-and-probability/exercises.pdf) · [詳解](chapters/chC-counting-and-probability/solutions.pdf) |
| [D 矩陣](chapters/chD-matrices/README.md) | [播放](chapters/chD-matrices/slides-teaching.pdf) · [講義](chapters/chD-matrices/slides-handout.pdf) | [練習](chapters/chD-matrices/exercises.pdf) · [詳解](chapters/chD-matrices/solutions.pdf) |
