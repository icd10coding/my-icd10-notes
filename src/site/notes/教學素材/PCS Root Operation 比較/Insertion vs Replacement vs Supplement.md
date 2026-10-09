---
{"dg-publish":true,"permalink":"//pcs-root-operation/insertion-vs-replacement-vs-supplement/","title":"Insertion vs Replacement vs Supplement 比較","tags":["ICD-10-PCS","Root-Operation","比較","Insertion","Replacement","Supplement"],"dg-note-properties":{"title":"Insertion vs Replacement vs Supplement 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Insertion","Replacement","Supplement"],"system":"PCS 根本操作"}}
---

## Insertion（置入）vs Replacement（置換）vs Supplement（強化）比較

> PCS Root Operation H（Insertion）vs R（Replacement）vs U（Supplement）
> 三者都涉及「放入裝置或材料」，但目的與是否移除原組織完全不同。

---

## 核心定義

| 項目 | Insertion（H）置入 | Replacement（R）置換 | Supplement（U）強化 |
|------|-----------------|---------------------|-------------------|
| PCS 代碼 | H | R | U |
| 是否移除原組織 | ❌ | ✅ 移除 | ❌ |
| 裝置是否取代 Body Part | ❌（只是放進去） | ✅ 取代功能 | ✅ 輔助強化 |
| 類比 | 安裝監視器 | 換零件 | 打補丁補強 |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Insertion（置入）= 放入非生物裝置，Body Part **不改變** | 監測器、導管、節律器、骨釘（固定用）；裝置不取代 Body Part | ICD-10-PCS Definitions | 2023 PCS, Root Operation H |
| — | — | — | — | Replacement（置換）= 移除原組織，以材料**取而代之** | 須先 Excision/Resection；前置切除**不另編**（Guideline B3.1b；B3.18） | ICD-10-PCS Guidelines | 2025 PCS Guidelines, B3.1b；B3.18 |
| — | — | — | — | Supplement（強化）= 保留原組織，加材料**補強功能** | 原 Body Part 保留；裝置執行輔助/強化功能 | ICD-10-PCS Definitions | 2023 PCS, Root Operation U |
| — | — | — | — | 判斷 Insertion vs Supplement 關鍵：裝置是否執行 Body Part 結構功能 | 監測/管路 → Insertion；補強功能 → Supplement | ICD-10-PCS Guidelines | 2023 PCS Guidelines |
| — | — | — | — | Device 7 = Autologous（自體）；J = Synthetic（合成）；K = Nonautologous（異種/異體） | 用於 Replacement 和 Supplement | ICD-10-PCS Table | 2023 PCS, Device column |

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
| 心臟節律器置入→ **Insertion（置入）**（0JH60PZ）<br>*節律器脈衝產生器（胸部皮下）；導線另編 02H63JZ（右心房）；雙腔節律器為 0JH606Z* | `0JH60PZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `J`<br>皮下組織與筋膜<br><sub>Subcutaneous Tissue and Fascia</sub> | `H`<br>置入<br><sub>Insertion</sub> | `6`<br>胸部皮下組織與筋膜<br><sub>Subcutaneous Tissue and Fascia, Chest</sub> | `0`<br>開放<br><sub>Open</sub> | `P`<br>心律相關裝置<br><sub>Cardiac Rhythm Related Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0JH<br>2023 PCS, Table 0JH | ⚠️ 已修正：原碼 0JH60NZ 的第6碼 N＝組織擴張器（Tissue Expander）；心律相關裝置為 P |
| 中心靜脈導管（CVC）→ **Insertion（置入）**（02HV33Z）<br>*靜脈保留；Device 3（Infusion Device）* | `02HV33Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `H`<br>置入<br><sub>Insertion</sub> | `V`<br>上腔靜脈<br><sub>Superior Vena Cava</sub> | `3`<br>經皮<br><sub>Percutaneous</sub> | `3`<br>輸注裝置<br><sub>Infusion Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 02H<br>2023 PCS, Table 02H | ✅ 通過 |
| 內耳暫時性輸注裝置→ **Insertion（置入）**（X9HD01B）<br>*新 PCS Table X9H；Device 1（Temporary Infusion）* | `X9HD01B` | `X`<br>新科技<br><sub>New Technology</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `H`<br>置入<br><sub>Insertion</sub> | `D`<br>右內耳<br><sub>Inner Ear, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `1`<br>暫時性輸注裝置<br><sub>Infusion Device, Temporary</sub> | `B`<br>新科技群組 11<br><sub>New Technology Group 11</sub> | AHA Coding Clinic<br>2026, 耳鼻喉頭頸部, Q1 p.18 | ❔ 2023 版工具書無 X9H 表；欄位值引自 AHA CC 2026 Q1（vault：依科別／耳鼻喉頭頸部） |
| 梨形孔狹窄鼻形器→ **Insertion（置入）**（09HK7YZ×2）<br>*鼻形器置入，鼻腔保留；兩側各一碼* | `09HK7YZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `H`<br>置入<br><sub>Insertion</sub> | `K`<br>鼻黏膜與軟組織<br><sub>Nasal Mucosa and Soft Tissue</sub> | `7`<br>經自然/人工開口<br><sub>Via Natural or Artificial Opening</sub> | `Y`<br>其他裝置<br><sub>Other Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2022, 耳鼻喉頭頸部, Q2 p.22 | ℹ️ 第4碼 K 為單一碼值（無左右側）；原筆記「×2、兩側各一碼」請對照 AHA 原文 |
| 全髖關節置換術（THA）→ **Replacement（置換）**（0SR902Z）<br>*全髖置換（右髖例：金屬對聚乙烯）；側別、材質、固定方式決定第4、6、7碼* | `0SR902Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `S`<br>下部關節<br><sub>Lower Joints</sub> | `R`<br>置換<br><sub>Replacement</sub> | `9`<br>右髖關節<br><sub>Hip Joint, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `2`<br>合成替代物（金屬對聚乙烯）<br><sub>Synthetic Substitute, Metal on Polyethylene</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 05R<br>2023 PCS, Table 05R | ⚠️ 已修正：05R 為上靜脈（B＝右貴要靜脈），不是髖關節；髖關節屬 0S（下部關節） |
| 主動脈瓣置換術（SAVR）→ **Replacement（置換）**（02RF08Z）<br>*主動脈瓣置換，生物瓣＝動物源組織 Zooplastic（8）；自體組織（7，如 Ross）才用 7* | `02RF08Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `R`<br>置換<br><sub>Replacement</sub> | `F`<br>主動脈瓣<br><sub>Aortic Valve</sub> | `0`<br>開放<br><sub>Open</sub> | `8`<br>動物源組織<br><sub>Zooplastic Tissue</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 02R<br>2023 PCS, Table 02R | ⚠️ 已修正：第6碼 7＝Autologous Tissue Substitute，動物源生物瓣為 8 Zooplastic Tissue |
| 軟顎切除＋阻塞器→ **Replacement（置換）**（0CR3XJZ）<br>*移除軟顎組織，阻塞器取代功能* | `0CR3XJZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `R`<br>置換<br><sub>Replacement</sub> | `3`<br>軟顎<br><sub>Soft Palate</sub> | `X`<br>外部<br><sub>External</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2014, 耳鼻喉頭頸部, Q3 p.25 | ✅ 通過 |
| 疝氣修補＋網片→ **Supplement（強化）**（0WUF0JZ）<br>*腹壁保留；Device J（網片）* | `0WUF0JZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `W`<br>解剖區域－一般<br><sub>Anatomical Regions, General</sub> | `U`<br>補強<br><sub>Supplement</sub> | `F`<br>腹壁<br><sub>Abdominal Wall</sub> | `0`<br>開放<br><sub>Open</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0WU<br>2023 PCS, Table 0WU | ✅ 通過 |
| EVAR（主動脈瘤腔內修復）→ **Restriction（限縮）**（04V03DZ）<br>*EVAR：腹主動脈、經皮、腔內裝置 → Restriction* | `04V03DZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `4`<br>下動脈<br><sub>Lower Arteries</sub> | `V`<br>限縮<br><sub>Restriction</sub> | `0`<br>腹主動脈<br><sub>Abdominal Aorta</sub> | `3`<br>經皮<br><sub>Percutaneous</sub> | `D`<br>腔內裝置<br><sub>Intraluminal Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | Coding Handbook<br>2026 ICD-10-CM/PCS Coding Handbook, Restriction of abdominal aorta with intraluminal device, percutaneous 04V03DZ | ⚠️ 已修正：EVAR 為 Restriction（04V03DZ），原 04U00JZ 為開放式 Supplement |
| 上半規管骨水泥修補→ **Supplement（強化）**（0NU50KZ）<br>*顳骨保留；Device K（骨水泥）* | `0NU50KZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `N`<br>頭與顏面骨<br><sub>Head and Facial Bones</sub> | `U`<br>補強<br><sub>Supplement</sub> | `5`<br>右顳骨<br><sub>Temporal Bone, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `K`<br>非自體組織替代物<br><sub>Nonautologous Tissue Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2021, 耳鼻喉頭頸部, Q3 p.17 | ℹ️ 第6碼 K＝Nonautologous Tissue Substitute（官方）；原敘述「骨水泥」請對照 AHA 原文確認材質歸類 |
| 組織擴張器置入（暫時）→ **Insertion（置入）**<br>*暫時撐開，不取代乳房* | — | — | — | — | — | — | — | — | ICD-10-PCS Table 0JH<br>2023 PCS, Table 0JH | — 原文無 PCS 代碼 |
| 組織擴張器換為永久植入物→ **Replacement（置換）**<br>*移除擴張器，換永久植入物* | — | — | — | — | — | — | — | — | ICD-10-PCS Table 0HR<br>2023 PCS, Table 0HR | — 原文無 PCS 代碼 |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Repair vs Replacement vs Supplement 比較\|Repair vs Replacement vs Supplement 比較]]
- [[Insertion vs Fusion vs Reposition 比較\|Insertion vs Fusion vs Reposition 比較]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
