# 資訊工程六科自學講義

**Computer Science Self-Study Notes — 繁體中文與英文教材**

六科分開整理，面向大學高年級與研究所程度的自學：定義與適用條件、一般證明、可追蹤數例、操作圖解，以及獨立練習與完整詳解。作者：Lin Cing。

Each course has Traditional Chinese and English editions, worked examples, proofs, diagrams, exercises, and solutions. Choose a course below for its chapter index, or download a full course handout.

| 科目與分章目錄 / Course | 繁體中文完整版 | English full course |
|---|---|---|
| [演算法 / Algorithms](courses/algorithms/README.md) | [中文整本](courses/algorithms/zh-TW/complete-handout.pdf) | [English full handout](courses/algorithms/en/complete-handout.pdf) |
| [離散數學 / Discrete and Combinatorial Mathematics](courses/discrete_mathematics/README.md) | [中文整本](courses/discrete_mathematics/zh-TW/complete-handout.pdf) | [English full handout](courses/discrete_mathematics/en/complete-handout.pdf) |
| [線性代數 / Linear Algebra](courses/linear_algebra/README.md) | [中文整本](courses/linear_algebra/zh-TW/complete-handout.pdf) | [English full handout](courses/linear_algebra/en/complete-handout.pdf) |
| [計算機組織 / Computer Organization](courses/computer_organization/README.md) | [中文整本](courses/computer_organization/zh-TW/complete-handout.pdf) | [English full handout](courses/computer_organization/en/complete-handout.pdf) |
| [作業系統 / Operating Systems](courses/operating_systems/README.md) | [中文整本](courses/operating_systems/zh-TW/complete-handout.pdf) | [English full handout](courses/operating_systems/en/complete-handout.pdf) |
| [資料結構 / Data Structures](courses/data_structures/README.md) | [中文整本](courses/data_structures/zh-TW/complete-handout.pdf) | [English full handout](courses/data_structures/en/complete-handout.pdf) |

## 教材格式 / Formats

- **完整版講義**：每科每語系各一本 A4 上下兩張講義，包含正文、附錄、可點選目錄、章節書籤及全書頁碼；首頁標明參考用書、作者與版次。
- **教用播放版**：每章一份 16:9 PDF，一張一頁。
- **分章講義版**：每章一份 A4 直式 PDF，上下兩張。
- **練習與詳解**：每章各自獨立兩份 PDF，可先作答再核對推導。

Full handouts combine each course's chapter and appendix handouts. Teaching slides, chapter handouts, exercises, and solutions remain available separately. Every PDF page carries Lin Cing and this repository URL.

## 目錄結構 / Structure

```text
courses/<subject>/
├── README.md
├── zh-TW/
│   ├── README.md
│   ├── complete-handout.pdf
│   ├── chapters/chNN-topic/  → 播放、講義、練習、詳解四份 PDF
│   └── appendices/          → 適用科目的附錄
└── en/                     → 相同結構
```

各科、語系與章節有固定路徑；正文和附錄在目錄中分列。ALG、CO 的字母附錄沿用章節目錄中的既有路徑，但在導覽中單獨列為附錄。

## 參考用書 / Reference textbooks

| 科目 | 書名與版次 | 作者 |
|---|---|---|
| 演算法 | Introduction to Algorithms, 3rd Edition | Cormen, Leiserson, Rivest, Stein |
| 離散數學 | Discrete and Combinatorial Mathematics, 5th Edition | Ralph P. Grimaldi |
| 線性代數 | Introduction to Linear Algebra, 5th Edition | Gilbert Strang |
| 計算機組織 | Computer Organization and Design, Revised Fourth Edition | Patterson, Hennessy |
| 作業系統 | Operating System Concepts, 9th Edition | Silberschatz, Galvin, Gagne |
| 資料結構 | Fundamentals of Data Structures in C++, 2nd Edition | Horowitz, Sahni, Mehta |

本教材為原創教學整理，參考書原檔、掃描件與製作資料不隨倉庫散布。資料結構依十一章主題清單組織，未取得第二版全文供逐節核對。計組所提供參考 PDF 不含光碟附錄 C、D、E；其餘來源範圍詳見各科首頁。

These are independently authored educational notes. The referenced books are not distributed. Data Structures follows a supplied eleven-chapter topic outline; the second-edition text was unavailable for section-by-section verification. See each course's reference notes for scope details.

## 授權 / License

原創內容採 [CC BY 4.0](LICENSE)，使用或改作時請署名 Lin Cing 並連回本倉庫。Original material is licensed under CC BY 4.0; retain attribution and a link to this repository.
