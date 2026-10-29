# RRAM 材料與濺鍍：從零開始的八週自學課程

繁體中文教材，適合有程式設計基礎、尚未修過電學與材料課程的學習者。主線是電阻式記憶體（RRAM / ReRAM）、濺鍍薄膜、電性量測與材料證據判讀。

## 從這裡開始

1. 先讀 [前 14 天課表](first14days-plan.pdf)，依序學第 1–4 章。
2. 用 [每日練習](daily-exercises.pdf) 檢查理解，完成後再看 [獨立詳解](daily-solutions.pdf)。
3. 依 [實驗室入門指南](lab-onboarding.pdf) 與帶領者確認 SOP、設備訓練與樣品。前兩週的參考負載操作屬受監督儀器訓練，第 3 週以受監督的標準 RRAM 基線實驗為目標。
4. 後六週照 [完整 56 天課表與學科權重](study-plan.pdf)，並行補足物理、材料分析、可靠度與論文閱讀。

課表中的 O01、R01 等代碼可在 [伴讀對照](reading-map.pdf) 找到完整課程、出版品名稱與選讀範圍。可點擊的官方 OCW 課程連結另行提供。

實驗記錄可從 [空白文字模板](templates/README.md) 開始，包含 Run record、整理表格欄位和資料夾結構。

每個學習日的核心為 6 小時，每週 6 天，八週共 288 小時。實驗已包含在總時數內；第 7 天留作休息或自願回顧。學科權重是時間分配建議，不是招生配分。八週目標是研究入門與面試準備，不代表精通整個材料領域。

## 八個單元

| 章 | 主題 | 使用時機 |
|---|---|---|
| [01](chapters/ch01-electricity/README.md) | 電荷、電壓、電流、電路與 I–V | 第 1–3 天 |
| [02](chapters/ch02-materials-rram/README.md) | 原子、缺陷、薄膜與 RRAM 基本語言 | 第 4–6 天 |
| [03](chapters/ch03-sputtering/README.md) | 真空、電漿、濺鍍與薄膜製程 | 第 8–10 天 |
| [04](chapters/ch04-measurement-readiness/README.md) | 量測、紀錄、限流與入場準備 | 第 11–13 天 |
| [05](chapters/ch05-solid-state/README.md) | 量子、固態、能帶與半導體接面 | 第 3–4 週選讀與深化 |
| [06](chapters/ch06-materials-physics/README.md) | 熱力學、傳輸、相圖與材料分析 | 第 3–5 週 |
| [07](chapters/ch07-rram-evidence/README.md) | 傳導與切換證據、可靠度、實驗設計 | 第 6–7 週 |
| [08](chapters/ch08-landscape-interview/README.md) | 材料全景、論文閱讀與博士口試 | 第 7–8 週 |

## 閱讀與列印

- [整套螢幕版](complete-teaching.pdf)：一張一頁，保留可搜尋文字。
- [整套列印講義](complete-handout.pdf)：A4 直式，上下兩張。
- [前兩週螢幕版](bootcamp-teaching.pdf)：第 1–4 章集中閱讀。
- 整套補充：[閱讀筆記與來源](complete-notes.pdf)、[分章練習合集](complete-exercises.pdf)、[詳解合集](complete-solutions.pdf)、[詳解補充](complete-solution-notes.pdf)。
- 前兩週也有 [列印版](bootcamp-handout.pdf)、[閱讀補充](bootcamp-notes.pdf)、[練習](bootcamp-exercises.pdf)、[詳解](bootcamp-solutions.pdf) 與 [詳解補充](bootcamp-solution-notes.pdf)。
- 每章另外提供練習、詳解、閱讀補充與可編輯 PowerPoint。閱讀補充包含推導說明、限制與來源，建議與投影片一起使用。
- PDF 保留固定版面。PPTX 使用 Noto Sans CJK TC；若編輯器替代字型，請以 PDF 對照換行與圖示位置。
- 投影片右下方的固定 ID 可用於對照詳解及閱讀補充。頁碼會因螢幕版、列印版與題解分離而不同。

## 實驗與證據

教材中的算例與示意圖用來學習，並非真實樣品結果，也不是可直接上機的製程或量測設定。Forming、電壓／電流範圍、氣體、真空與熱處理操作，必須遵守實驗室核定 SOP、設備資格與帶領者授權。未通過現場確認時，課表提供既有資料分析與紙上練習作替代。

量測的 I–V 形狀、單一光譜或一張顯微影像，通常不足以唯一判定切換機制。本課程要求分清觀察、模型假設、替代解釋與尚缺證據。

本課為原創整理與教學示例，不附第三方整套課件或論文全文。相關科學書目及逐頁來源見各章閱讀補充。沿用本書架的 [CC BY 4.0](../../../LICENSE)，第三方來源內容仍適用其原有權利。
