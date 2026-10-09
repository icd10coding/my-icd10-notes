---
{"dg-publish":true,"permalink":"//pcs-root-operation/insertion-vs-fusion-vs-reposition/","title":"Insertion vs Fusion vs Reposition 比較","tags":["ICD-10-PCS","Root-Operation","比較","Insertion","Fusion","Reposition"],"dg-note-properties":{"title":"Insertion vs Fusion vs Reposition 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Insertion","Fusion","Reposition"],"system":"PCS 根本操作"}}
---

## Insertion（置入）vs Fusion（融合）vs Reposition（復位）比較

> PCS Root Operation H（Insertion）vs G（Fusion）vs S（Reposition）
> 三者都常見於**脊椎手術**，是骨科編碼最高頻混淆組合。

---

## 核心定義

| 項目 | Insertion（H）置入 | Fusion（G）融合 | Reposition（S）復位 |
|------|-----------------|--------------|-------------------|
| PCS 代碼 | H | G | S |
| 關節是否固定 | ❌（裝置只是放進去） | ✅ **永久固定** | ❌（復位後仍可活動） |
| 是否有骨折/脫位 | 不需要 | 不需要 | ✅ 必要前提 |
| 典型裝置 | 神經刺激器、導管 | PEEK cage、骨移植 | 骨釘（復位用） |
| 類比 | 安裝螺絲（固定結構） | 焊死（永不動） | 歸位（可繼續動） |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Insertion（置入）= 放入裝置，Body Part **不改變** | 神經刺激器、引流管、人工椎間盤（保留活動度）；不固定關節 | ICD-10-PCS Definitions | 2023 PCS, Root Operation H |
| — | — | — | — | Fusion（融合）= 使關節**永久固定**不動 | PEEK cage、骨移植、骨釘使椎間關節永久融合 | ICD-10-PCS Definitions | 2023 PCS, Root Operation G |
| — | — | — | — | Reposition（復位）= 將移位 Body Part 移回原位 | 骨折復位、脫位復位；移回後仍可活動 | ICD-10-PCS Definitions | 2023 PCS, Root Operation S |
| — | — | — | — | **骨釘不是獨立 Root Operation**，是其他手術的 Device | 骨折復位後固定 → Reposition Device=4；融合固定 → Fusion Device=4；單純置入 → Insertion | ICD-10-PCS Guidelines | 2023 PCS Guidelines, B6.1 |
| — | — | — | — | Guideline B3.10：若 Fusion 含固定骨釘，**不另編 Insertion** | 骨釘已含於 Fusion 代碼中，不需另行編碼 Insertion | PCS Guidelines | 2023 PCS Guidelines, B3.10 |
| — | — | — | — | Guideline B3.1b：若 Reposition 是 Fusion 固有步驟，**不另編 Reposition** | 退化性疾病行融合術（無骨折）→ 只編 Fusion | PCS Guidelines | 2023 PCS Guidelines, B3.1b |
| — | — | — | — | 骨折椎體先復位再融合：**Reposition ＋ Fusion 均編** | 兩者為不同 Root Operation，依 Guideline B3.2 分別編碼 | PCS Guidelines | 2023 PCS Guidelines, B3.2 |
| — | — | — | — | Fusion Device A = **Interbody Fusion Device**（PEEK cage、鈦合金 cage） | ⚠️ 非 Synthetic Substitute（J） | ICD-10-PCS Table 0SG | 2023 PCS, Table 0SG, Device column |
| — | — | — | — | Fusion Qualifier J = 後路進入，融合**前柱**（PLIF/TLIF）⚠️ 最常考 | 後路（Posterior）進入，融合前柱（Anterior Column） | ICD-10-PCS Table 0SG | 2023 PCS, Table 0SG, Qualifier column |
| — | — | — | — | Fusion Qualifier 0 = 前路進入，融合前柱（ACDF/ALIF） | 前路進入，前柱融合 | ICD-10-PCS Table 0RG/0SG | 2023 PCS, Table 0RG/0SG |

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
| 脊髓神經刺激器置入（SCS）→ **Insertion（置入）**（00HV0MZ）<br>*不融合，只放電極；Device M（Neurostimulator Lead）* | `00HV0MZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `0`<br>中樞神經與顱神經<br><sub>Central Nervous System and Cranial Nerves</sub> | `H`<br>置入<br><sub>Insertion</sub> | `V`<br>脊髓<br><sub>Spinal Cord</sub> | `0`<br>開放<br><sub>Open</sub> | `M`<br>神經刺激器導線<br><sub>Neurostimulator Lead</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 00H<br>2023 PCS, Table 00H | ✅ 通過 |
| 人工椎間盤置換（保留活動度）→ **Replacement（置換）**<br>*移除椎間盤，換人工盤；保留活動度（非 Fusion）* | — | — | — | — | — | — | — | — | ICD-10-PCS Table 0RR<br>2023 PCS, Table 0RR | — 原文無 PCS 代碼 |
| 椎體成形術（Vertebroplasty，骨水泥）→ **Supplement（強化）**<br>*骨水泥填補椎體，不融合；見 Repair vs Replacement vs Supplement* | — | — | — | — | — | — | — | — | ICD-10-PCS Table 0PU<br>2023 PCS, Table 0PU | — 原文無 PCS 代碼 |
| 腰椎 TLIF/PLIF→ **Fusion（融合）**（0SG10AJ）<br>*Device A（PEEK cage）；Qualifier J（後路前柱）⚠️* | `0SG10AJ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `S`<br>下部關節<br><sub>Lower Joints</sub> | `G`<br>融合<br><sub>Fusion</sub> | `1`<br>腰椎關節（2 個以上）<br><sub>Lumbar Vertebral Joints, 2 or more</sub> | `0`<br>開放<br><sub>Open</sub> | `A`<br>椎體間融合裝置<br><sub>Interbody Fusion Device</sub> | `J`<br>後路進入、前柱<br><sub>Posterior Approach, Anterior Column</sub> | ICD-10-PCS Table 0SG<br>2023 PCS, Table 0SG | ℹ️ 第4碼 1＝腰椎關節 2 個以上；單一椎間關節為 0（B3.10a）；第7碼 J＝後路進入、前柱 |
| 頸椎 ACDF→ **Fusion（融合）**（0RG10A0）<br>*Device A（cage）；Qualifier 0（前路前柱）* | `0RG10A0` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `R`<br>上部關節<br><sub>Upper Joints</sub> | `G`<br>融合<br><sub>Fusion</sub> | `1`<br>頸椎關節（單一）<br><sub>Cervical Vertebral Joint</sub> | `0`<br>開放<br><sub>Open</sub> | `A`<br>椎體間融合裝置<br><sub>Interbody Fusion Device</sub> | `0`<br>前路進入、前柱<br><sub>Anterior Approach, Anterior Column</sub> | ICD-10-PCS Table 0RG<br>2023 PCS, Table 0RG | ⚠️ 已修正：0RG 表無第4碼 3；頸椎單一關節＝1（2 個以上＝2） |
| 脊椎骨折椎體復位＋骨釘→ **Reposition（復位）**（0PS304Z）<br>*Device 4（骨釘）；骨釘為 Reposition 的 Device，不另編 Insertion* | `0PS304Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `P`<br>上部骨骼<br><sub>Upper Bones</sub> | `S`<br>復位<br><sub>Reposition</sub> | `3`<br>頸椎<br><sub>Cervical Vertebra</sub> | `0`<br>開放<br><sub>Open</sub> | `4`<br>內固定裝置<br><sub>Internal Fixation Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0PS<br>2023 PCS, Table 0PS | ✅ 通過 |
| 脊椎骨折復位後行融合→ **Reposition ＋ Fusion** 兩碼均編<br>*不同 Root Operation，依 B3.2 分別編碼* | — | — | — | — | — | — | — | — | PCS Guidelines<br>2023 PCS Guidelines, B3.2 | — 原文無 PCS 代碼 |
| 退化性椎間盤行融合術（無骨折）→ 只編 **Fusion**<br>*Reposition 非必要，不另編* | — | — | — | — | — | — | — | — | PCS Guidelines<br>2023 PCS Guidelines, B3.1b | — 原文無 PCS 代碼 |
| 內耳暫時性輸注裝置→ **Insertion（置入）**（X9HD01B）<br>*新 PCS Table X9H；Device 1（Temporary Infusion）* | `X9HD01B` | `X`<br>新科技<br><sub>New Technology</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `H`<br>置入<br><sub>Insertion</sub> | `D`<br>右內耳<br><sub>Inner Ear, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `1`<br>暫時性輸注裝置<br><sub>Infusion Device, Temporary</sub> | `B`<br>新科技群組 11<br><sub>New Technology Group 11</sub> | AHA Coding Clinic<br>2026, 耳鼻喉頭頸部, Q1 p.18 | ❔ 2023 版工具書無 X9H 表；欄位值引自 AHA CC 2026 Q1（vault：依科別／耳鼻喉頭頸部） |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Fusion vs Reposition 比較\|Fusion vs Reposition 比較]]
- [[Insertion vs Replacement vs Supplement 比較\|Insertion vs Replacement vs Supplement 比較]]
- [[Repair vs Replacement vs Supplement 比較\|Repair vs Replacement vs Supplement 比較]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
