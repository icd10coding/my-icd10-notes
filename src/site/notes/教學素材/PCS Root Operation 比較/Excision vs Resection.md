---
{"dg-publish":true,"permalink":"//pcs-root-operation/excision-vs-resection/","title":"Excision vs Resection 比較","tags":["ICD-10-PCS","Root-Operation","比較","Excision","Resection"],"dg-note-properties":{"title":"Excision vs Resection 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Excision","Resection"],"system":"PCS 根本操作"}}
---

## Excision（切除部分）vs Resection（切除全部）比較

> PCS Root Operation B（Excision）vs T（Resection）
> 核心差異：切除**部分** vs 切除**全部** Body Part

---

## 核心定義

| 項目 | Excision（B） | Resection（T） |
|------|--------------|--------------|
| PCS 代碼 | B | T |
| 定義 | 切除 Body Part **部分**，不加替換 | 切除 Body Part **全部** |
| Qualifier X | ✅ Diagnostic（切片） | ❌ 無 Diagnostic qualifier |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Excision = 切除**部分** Body Part | 切除 Body Part 的一部分，不替換；若送病理加 Qualifier X（Diagnostic） | ICD-10-PCS Definitions | 2023 PCS, Section 0, Root Operation B |
| — | — | — | — | Resection = 切除**全部** Body Part | 切除整個 Body Part；由 PCS Body Part Table 定義「全部」的範圍 | ICD-10-PCS Definitions | 2023 PCS, Section 0, Root Operation T |
| — | — | — | — | 肺葉切除術（Lobectomy）= **Resection** | 肺葉（Lobe）在 PCS 中為獨立 Body Part，整葉切除 = Resection | ICD-10-PCS Table 0BB/0BT | 2023 PCS, Table 0BT |
| — | — | — | — | 肺段切除術（Segmentectomy）= **Excision** | 肺段（Segment）非獨立 Body Part，部分切除 = Excision | ICD-10-PCS Table 0BB | 2023 PCS, Table 0BB |
| — | — | — | — | 淺層腮腺切除（保留深葉）= **Excision** | 保留深葉，未切除整個 Body Part（Parotid Gland）→ Excision | AHA Coding Clinic | 2014, AHA Coding Clinic 依科別/耳鼻喉頭頸部, Q3 p.21 |
| — | — | — | — | 全腮腺切除（淺葉＋深葉）= **Resection** | 整個腮腺完整切除 → Resection | ICD-10-PCS Table 0CT | 2023 PCS, Table 0CT |
| — | — | — | — | Guideline B3.8：Excision 用於部分切除，Resection 用於全切 | 若 PCS Body Part Table 有獨立值，整個切除 = Resection；否則為 Excision | PCS Guidelines | 2023 PCS Guidelines, B3.8 |
| — | — | — | — | Qualifier X = Diagnostic（切片） | 切除目的為診斷（送病理）時，加 Qualifier X；治療性切除不加 | ICD-10-PCS Guidelines | 2023 PCS Guidelines, B3.4a |

---

## 臨床情境對照表

### 七個字元位置說明

> 依 2025 PCS Guidelines A1–A9：碼一律 **7 碼**、無小數點；每碼只用數字 0–9 與英文字母（**不含 I、O**）；一個值的意義取決於所在位置與前面的碼（A4）；**七碼全部指定才是有效碼**（A8）。第 4–7 碼必須落在 Table 的**同一列**才成立（A9）。

| 位置 | 名稱 | 意義（內外科 Section 0） |
|:--:|------|------|
| ① | Section 段落 | 手術大類；`0` 內外科、`1` 產科、`2` 放置、`X` 新科技 |
| ② | Body System 身體系統 | 手術所在的解剖系統 |
| ③ | Root Operation 根手術 | 手術的**目的**（本組筆記比較的核心） |
| ④ | Body Part 身體部位 | 手術目標部位；意義依第 2 碼而定 |
| ⑤ | Approach 途徑 | `0` 開放、`3` 經皮、`4` 經皮內視鏡、`7` 經自然/人工開口、`8` 經自然/人工開口＋內視鏡、`F` 經自然/人工開口＋經皮內視鏡輔助、`X` 外部 |
| ⑥ | Device 裝置 | 手術結束後**仍留在體內**的裝置（B6.1a）；無則 `Z`＝No Device |
| ⑦ | Qualifier 限定詞 | 補充屬性（診斷性、繞道終點、截肢層級、皮瓣類型…）；無則 `Z`＝No Qualifier |

| 情境（含原說明） | 代碼 | ① Section | ② Body System | ③ Root Operation | ④ Body Part | ⑤ Approach | ⑥ Device | ⑦ Qualifier | 來源 | 核對（2023 PCS Tables） |
|---|---|---|---|---|---|---|---|---|---|---|
| Lung lobectomy（肺葉切除術）→ **Resection**<br>*肺葉 = 獨立 Body Part；代碼：0BTC0ZZ（右上葉）等* | `0BTC0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `B`<br>呼吸系統<br><sub>Respiratory System</sub> | `T`<br>切除全部<br><sub>Resection</sub> | `C`<br>右肺上葉<br><sub>Upper Lung Lobe, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>使用者糾正，2026 session | ⚠️ 已修正：0BT 表 F＝右肺下葉、C＝右肺上葉（B3.8：肺葉切除＝Resection 該肺葉） |
| Segmentectomy（肺段切除術）→ **Excision**<br>*肺段非獨立 Body Part；代碼：0BBD0ZZ* | `0BBD0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `B`<br>呼吸系統<br><sub>Respiratory System</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `D`<br>右肺中葉<br><sub>Middle Lung Lobe, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0BB<br>2023 PCS, Table 0BB | ℹ️ 肺段無獨立碼值，依 B4.1a 編至整個肺葉（此例＝右肺中葉） |
| 淺層腮腺切除→ **Excision**（0CB80ZZ）<br>*保留深葉* | `0CB80ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `8`<br>右腮腺<br><sub>Parotid Gland, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2014, 耳鼻喉頭頸部, Q3 p.21 | ✅ 通過 |
| 甲舌管囊腫切除（Sistrunk）→ **Excision**（0WB60ZZ）<br>*頸部組織切除，非全切* | `0WB60ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `W`<br>解剖區域－一般<br><sub>Anatomical Regions, General</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `6`<br>頸部<br><sub>Neck</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2021, 耳鼻喉頭頸部, Q3 p.16 | ✅ 通過 |
| 梨形孔狹窄鑿骨→ **Excision**（0NBR0ZZ）<br>*切除增生骨質（非 Reposition）* | `0NBR0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `N`<br>頭與顏面骨<br><sub>Head and Facial Bones</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `R`<br>上頜骨<br><sub>Maxilla</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2022, 耳鼻喉頭頸部, Q2 p.22 | ✅ 通過 |
| 扁桃腺切除術（Tonsillectomy）→ **Resection**（0CTPXZZ）<br>*整個扁桃腺切除 = Resection* | `0CTPXZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `T`<br>切除全部<br><sub>Resection</sub> | `P`<br>扁桃腺<br><sub>Tonsils</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0CT<br>2023 PCS, Table 0CT | ✅ 通過 |
| 腺樣體切除術（Adenoidectomy）→ **Resection**（0CTQXZZ）<br>*整個腺樣體切除 = Resection* | `0CTQXZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `T`<br>切除全部<br><sub>Resection</sub> | `Q`<br>腺樣體<br><sub>Adenoids</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0CT<br>2023 PCS, Table 0CT | ✅ 通過 |
| 結腸息肉切除術→ **Excision**（0DBN8ZZ）<br>*切除部分結腸黏膜* | `0DBN8ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `D`<br>消化系統<br><sub>Gastrointestinal System</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `N`<br>乙狀結腸<br><sub>Sigmoid Colon</sub> | `8`<br>經自然/人工開口＋內視鏡<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0DB<br>2023 PCS, Table 0DB | ✅ 通過 |
| 皮膚腫瘤切除術→ **Excision**（0HB0XZZ）<br>*切除部分皮膚* | `0HB0XZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `H`<br>皮膚與乳房<br><sub>Skin and Breast</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `0`<br>頭皮皮膚<br><sub>Skin, Scalp</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0HB<br>2023 PCS, Table 0HB | ✅ 通過 |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Control vs Repair vs Destruction 比較\|Control vs Repair vs Destruction 比較]]
- [[Extraction vs Excision 比較\|Extraction vs Excision 比較]]
- [[教學素材/CM 系統分類/H - 耳鼻喉科/ENT 耳鼻喉科編碼彙整（AHA Coding Clinic Q&A）\|ENT 耳鼻喉科編碼彙整（AHA Coding Clinic Q&A）]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
