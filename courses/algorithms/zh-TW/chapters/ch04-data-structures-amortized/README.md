# 資料結構與攤銷分析

先從堆疊、佇列與操作序列成本出發，再學雜湊、二元搜尋樹、紅黑樹的插入與刪除，以及次序統計與區間樹。最後討論 B-tree 的頁存取模型、Fibonacci heap 與整數 universe 下的 vEB 搜尋。

[教用播放版 · 16:9](slides-teaching.pdf) · [A4 講義 · 上下兩頁 4:3](slides-handout.pdf)

[72 題獨立練習](exercises.pdf) · [完整詳解](solutions.pdf)

記錄身分、handle、共用 NIL、區間端點、B-tree 的 order 與最小度數，以及節點數 n 和 universe 大小 u，都有各自明確的定義。期望、攤銷與最壞界分開推導；與資料結構科目採用不同表示法的地方，正文提供對照。

延伸閱讀：[不相交集合：進階分析](../ch21-disjoint-sets/README.md)，包含路徑壓縮與反 Ackermann 攤銷界的證明。

[章節目錄](../../README.md) · [科目首頁](../../../README.md)

參考用書：Cormen, Leiserson, Rivest, Stein, *Introduction to Algorithms*, 3rd Edition, Chapters 10–14 and 17–20.

補充參考：MIT 6.046J（2004）L09；MIT 6.046J（2005）L08、L09、L11、L13；Lin Cing 個人手寫資料結構筆記。實際採用的主題列於章末參考頁。
