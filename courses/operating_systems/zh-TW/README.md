# 作業系統

20 個章節／附錄單元，分章提供教材、練習與詳解。

[科目首頁](../README.md)

**[下載整科完整版講義](complete-handout.pdf)**（含目錄、章節書籤及全書頁碼）

播放版適合螢幕閱讀；講義版將同一內容上下排成 A4。練習與詳解各自獨立，建議先作答再開詳解。

先用第 1、2 章建立核心、系統呼叫與權限邊界，再讀行程、執行緒、同步、排程和死結，追蹤程式何時能繼續。記憶體與儲存兩組主題處理位址、缺頁、I/O 和持久性；保護與安全則檢查誰能做哪些操作。虛擬化和分散式系統延伸執行環境。第 18、19 章的 Linux／Windows 案例可回頭對照各機制，第 20 章補設計脈絡。原書章號與版本界線保留，方便查找。

**主題入口：** [一、核心、介面與系統結構](#foundations) · [二、行程、同步與排程](#execution) · [三、位址轉換與虛擬記憶體](#memory) · [四、儲存、檔案與 I/O](#storage-io) · [五、保護與安全](#protection-security) · [六、虛擬化與分散式系統](#virtual-distributed) · [七、系統案例與設計脈絡](#system-cases)

<a id="foundations"></a>

## 一、核心、介面與系統結構

| 章節入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [第 1 章　導論](chapters/ch01-introduction/README.md) | [播放](chapters/ch01-introduction/slides-teaching.pdf) · [講義](chapters/ch01-introduction/slides-handout.pdf) | [練習](chapters/ch01-introduction/exercises.pdf) · [詳解](chapters/ch01-introduction/solutions.pdf) |
| [第 2 章　作業系統結構](chapters/ch02-os-structures/README.md) | [播放](chapters/ch02-os-structures/slides-teaching.pdf) · [講義](chapters/ch02-os-structures/slides-handout.pdf) | [練習](chapters/ch02-os-structures/exercises.pdf) · [詳解](chapters/ch02-os-structures/solutions.pdf) |

<a id="execution"></a>

## 二、行程、同步與排程

| 章節入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [第 3 章　程序](chapters/ch03-processes/README.md) | [播放](chapters/ch03-processes/slides-teaching.pdf) · [講義](chapters/ch03-processes/slides-handout.pdf) | [練習](chapters/ch03-processes/exercises.pdf) · [詳解](chapters/ch03-processes/solutions.pdf) |
| [第 4 章　執行緒](chapters/ch04-threads/README.md) | [播放](chapters/ch04-threads/slides-teaching.pdf) · [講義](chapters/ch04-threads/slides-handout.pdf) | [練習](chapters/ch04-threads/exercises.pdf) · [詳解](chapters/ch04-threads/solutions.pdf) |
| [第 5 章　程序同步](chapters/ch05-process-synchronization/README.md) | [播放](chapters/ch05-process-synchronization/slides-teaching.pdf) · [講義](chapters/ch05-process-synchronization/slides-handout.pdf) | [練習](chapters/ch05-process-synchronization/exercises.pdf) · [詳解](chapters/ch05-process-synchronization/solutions.pdf) |
| [第 6 章　CPU 排程](chapters/ch06-cpu-scheduling/README.md) | [播放](chapters/ch06-cpu-scheduling/slides-teaching.pdf) · [講義](chapters/ch06-cpu-scheduling/slides-handout.pdf) | [練習](chapters/ch06-cpu-scheduling/exercises.pdf) · [詳解](chapters/ch06-cpu-scheduling/solutions.pdf) |
| [第 7 章　死結](chapters/ch07-deadlocks/README.md) | [播放](chapters/ch07-deadlocks/slides-teaching.pdf) · [講義](chapters/ch07-deadlocks/slides-handout.pdf) | [練習](chapters/ch07-deadlocks/exercises.pdf) · [詳解](chapters/ch07-deadlocks/solutions.pdf) |

<a id="memory"></a>

## 三、位址轉換與虛擬記憶體

| 章節入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [第 8 章　主記憶體](chapters/ch08-main-memory/README.md) | [播放](chapters/ch08-main-memory/slides-teaching.pdf) · [講義](chapters/ch08-main-memory/slides-handout.pdf) | [練習](chapters/ch08-main-memory/exercises.pdf) · [詳解](chapters/ch08-main-memory/solutions.pdf) |
| [第 9 章　虛擬記憶體](chapters/ch09-virtual-memory/README.md) | [播放](chapters/ch09-virtual-memory/slides-teaching.pdf) · [講義](chapters/ch09-virtual-memory/slides-handout.pdf) | [練習](chapters/ch09-virtual-memory/exercises.pdf) · [詳解](chapters/ch09-virtual-memory/solutions.pdf) |

<a id="storage-io"></a>

## 四、儲存、檔案與 I/O

| 章節入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [第 10 章　大量儲存結構](chapters/ch10-mass-storage/README.md) | [播放](chapters/ch10-mass-storage/slides-teaching.pdf) · [講義](chapters/ch10-mass-storage/slides-handout.pdf) | [練習](chapters/ch10-mass-storage/exercises.pdf) · [詳解](chapters/ch10-mass-storage/solutions.pdf) |
| [第 11 章　檔案系統介面](chapters/ch11-file-system-interface/README.md) | [播放](chapters/ch11-file-system-interface/slides-teaching.pdf) · [講義](chapters/ch11-file-system-interface/slides-handout.pdf) | [練習](chapters/ch11-file-system-interface/exercises.pdf) · [詳解](chapters/ch11-file-system-interface/solutions.pdf) |
| [第 12 章　檔案系統實作](chapters/ch12-file-system-implementation/README.md) | [播放](chapters/ch12-file-system-implementation/slides-teaching.pdf) · [講義](chapters/ch12-file-system-implementation/slides-handout.pdf) | [練習](chapters/ch12-file-system-implementation/exercises.pdf) · [詳解](chapters/ch12-file-system-implementation/solutions.pdf) |
| [第 13 章　I/O 系統](chapters/ch13-io-systems/README.md) | [播放](chapters/ch13-io-systems/slides-teaching.pdf) · [講義](chapters/ch13-io-systems/slides-handout.pdf) | [練習](chapters/ch13-io-systems/exercises.pdf) · [詳解](chapters/ch13-io-systems/solutions.pdf) |

<a id="protection-security"></a>

## 五、保護與安全

| 章節入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [第 14 章　保護](chapters/ch14-protection/README.md) | [播放](chapters/ch14-protection/slides-teaching.pdf) · [講義](chapters/ch14-protection/slides-handout.pdf) | [練習](chapters/ch14-protection/exercises.pdf) · [詳解](chapters/ch14-protection/solutions.pdf) |
| [第 15 章　安全](chapters/ch15-security/README.md) | [播放](chapters/ch15-security/slides-teaching.pdf) · [講義](chapters/ch15-security/slides-handout.pdf) | [練習](chapters/ch15-security/exercises.pdf) · [詳解](chapters/ch15-security/solutions.pdf) |

<a id="virtual-distributed"></a>

## 六、虛擬化與分散式系統

| 章節入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [第 16 章　虛擬機器](chapters/ch16-virtual-machines/README.md) | [播放](chapters/ch16-virtual-machines/slides-teaching.pdf) · [講義](chapters/ch16-virtual-machines/slides-handout.pdf) | [練習](chapters/ch16-virtual-machines/exercises.pdf) · [詳解](chapters/ch16-virtual-machines/solutions.pdf) |
| [第 17 章　分散式系統](chapters/ch17-distributed-systems/README.md) | [播放](chapters/ch17-distributed-systems/slides-teaching.pdf) · [講義](chapters/ch17-distributed-systems/slides-handout.pdf) | [練習](chapters/ch17-distributed-systems/exercises.pdf) · [詳解](chapters/ch17-distributed-systems/solutions.pdf) |

<a id="system-cases"></a>

## 七、系統案例與設計脈絡

| 章節入口 | 投影片 PDF | 題解 PDF |
|---|---|---|
| [第 18 章　Linux 系統](chapters/ch18-linux-system/README.md) | [播放](chapters/ch18-linux-system/slides-teaching.pdf) · [講義](chapters/ch18-linux-system/slides-handout.pdf) | [練習](chapters/ch18-linux-system/exercises.pdf) · [詳解](chapters/ch18-linux-system/solutions.pdf) |
| [第 19 章　Windows 7](chapters/ch19-windows-7/README.md) | [播放](chapters/ch19-windows-7/slides-teaching.pdf) · [講義](chapters/ch19-windows-7/slides-handout.pdf) | [練習](chapters/ch19-windows-7/exercises.pdf) · [詳解](chapters/ch19-windows-7/solutions.pdf) |
| [第 20 章　具影響力的作業系統](chapters/ch20-influential-systems/README.md) | [播放](chapters/ch20-influential-systems/slides-teaching.pdf) · [講義](chapters/ch20-influential-systems/slides-handout.pdf) | [練習](chapters/ch20-influential-systems/exercises.pdf) · [詳解](chapters/ch20-influential-systems/solutions.pdf) |

