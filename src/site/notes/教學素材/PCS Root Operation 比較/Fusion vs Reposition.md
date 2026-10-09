---
{"dg-publish":true,"permalink":"//pcs-root-operation/fusion-vs-reposition/","title":"Fusion vs Reposition 比較","tags":["ICD-10-PCS","Root-Operation","比較","Fusion","Reposition"],"dg-note-properties":{"title":"Fusion vs Reposition 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Fusion","Reposition"],"system":"PCS 根本操作"}}
---

## Fusion（融合）vs Reposition（復位）比較

> PCS Root Operation G（Fusion）vs S（Reposition）
> 核心差異：永久固定關節 vs 將移位 Body Part 移回原位

---

## 核心定義

| 項目 | Fusion（G）融合 | Reposition（S）復位 |
|------|--------------|-------------------|
| PCS 代碼 | G | S |
| 關節活動度 | **永久喪失** | **恢復**（仍可活動） |
| 適應症 | 退化性關節炎、脊椎不穩定 | 骨折、脫位、先天性異位 |
| 類比 | 永久焊死 | 歸位（可繼續動） |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Fusion（融合）= 使關節永久固定不動 | 以 cage、骨移植、骨釘使關節永久融合；Device + Qualifier 必填 | ICD-10-PCS Definitions | 2023 PCS, Root Operation G |
| — | — | — | — | Reposition（復位）= 將 Body Part 移回正常位置 | 骨折復位、關節脫位復位、先天異位矯正；移回後仍可活動 | ICD-10-PCS Definitions | 2023 PCS, Root Operation S |
| — | — | — | — | Fusion Device A = **Interbody Fusion Device**（最常用） | **PEEK cage、鈦合金 cage** 均屬 Device A；非 Synthetic Substitute（J） | ICD-10-PCS Table 0RG/0SG | 2023 PCS, Table 0SG, Device column |
| — | — | — | — | Fusion Qualifier J = 後路進入，融合**前柱**（PLIF/TLIF）⚠️ 最常考 | 後路（Posterior）進入，但融合前柱（Anterior Column）→ Qualifier J | ICD-10-PCS Table 0SG | 2023 PCS, Table 0SG, Qualifier column |
| — | — | — | — | Fusion Qualifier 0 = 前路進入，融合前柱（ACDF/ALIF） | 前路進入，融合前柱 → Qualifier 0 | ICD-10-PCS Table 0RG/0SG | 2023 PCS, Table 0RG/0SG |
| — | — | — | — | Fusion Qualifier 1 = 後路進入，融合後柱 | 後路進入，融合後柱（Posterior Column）→ Qualifier 1 | ICD-10-PCS Table 0SG | 2023 PCS, Table 0SG |
| — | — | — | — | 骨折復位後行融合：**Reposition + Fusion 均編** | 兩者為不同 Root Operation，依 Guideline B3.2 分別編碼 | PCS Guidelines | 2023 PCS Guidelines, B3.2 |
| — | — | — | — | 退化性疾病行融合：只編 **Fusion**（無 Reposition） | 無骨折/脫位，Reposition 非必要操作 | PCS Guidelines | 2023 PCS Guidelines, B3.1b |
| — | — | — | — | 脊椎滑脫復位＋融合是否兩碼均編：**待查確認** | vault 內未找到具體 AHA Coding Clinic 引用 | — | ⚠️ 待補充 |

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
| 腰椎 TLIF/PLIF→ **Fusion**（0SG10AJ）<br>*Device A（PEEK cage）；Qualifier J（後路前柱）* | `0SG10AJ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `S`<br>下部關節<br><sub>Lower Joints</sub> | `G`<br>融合<br><sub>Fusion</sub> | `1`<br>腰椎關節（2 個以上）<br><sub>Lumbar Vertebral Joints, 2 or more</sub> | `0`<br>開放<br><sub>Open</sub> | `A`<br>椎體間融合裝置<br><sub>Interbody Fusion Device</sub> | `J`<br>後路進入、前柱<br><sub>Posterior Approach, Anterior Column</sub> | ICD-10-PCS Table 0SG<br>2023 PCS, Table 0SG | ℹ️ 第4碼 1＝腰椎關節 2 個以上；單一椎間關節為 0（B3.10a）；第7碼 J＝後路進入、前柱 |
| 頸椎 ACDF→ **Fusion**（0RG10A0）<br>*Device A（cage）；Qualifier 0（前路前柱）* | `0RG10A0` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `R`<br>上部關節<br><sub>Upper Joints</sub> | `G`<br>融合<br><sub>Fusion</sub> | `1`<br>頸椎關節（單一）<br><sub>Cervical Vertebral Joint</sub> | `0`<br>開放<br><sub>Open</sub> | `A`<br>椎體間融合裝置<br><sub>Interbody Fusion Device</sub> | `0`<br>前路進入、前柱<br><sub>Anterior Approach, Anterior Column</sub> | ICD-10-PCS Table 0RG<br>2023 PCS, Table 0RG | ⚠️ 已修正：0RG 表無第4碼 3；頸椎單一關節＝1（2 個以上＝2） |
| 脊椎壓迫性骨折椎體成形術（Vertebroplasty）→ **Supplement（強化）**<br>*骨水泥填補強化，不融合；見 Repair vs Replacement vs Supplement* | — | — | — | — | — | — | — | — | ICD-10-PCS Table 0PU<br>2023 PCS, Table 0PU | — 原文無 PCS 代碼 |
| 股骨頸骨折復位固定→ **Reposition**（0QS604Z）<br>*Device 4（內固定）；移回原位後仍可活動* | `0QS604Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `Q`<br>下部骨骼<br><sub>Lower Bones</sub> | `S`<br>復位<br><sub>Reposition</sub> | `6`<br>右股骨上段<br><sub>Upper Femur, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `4`<br>內固定裝置<br><sub>Internal Fixation Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0QS<br>2023 PCS, Table 0QS | ✅ 通過 |
| 鼻中隔整形術（Septoplasty）→ **Reposition**（09SM0ZZ）<br>*偏曲軟骨移回正中位置（非 Excision）* | `09SM0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `S`<br>復位<br><sub>Reposition</sub> | `M`<br>鼻中隔<br><sub>Nasal Septum</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 09S<br>2023 PCS, Table 09S | ✅ 通過 |
| Le Fort I 截骨術→ **Reposition**（0NSR04Z）<br>*上頜骨截骨後重新定位；Device 4（內固定）* | `0NSR04Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `N`<br>頭與顏面骨<br><sub>Head and Facial Bones</sub> | `S`<br>復位<br><sub>Reposition</sub> | `R`<br>上頜骨<br><sub>Maxilla</sub> | `0`<br>開放<br><sub>Open</sub> | `4`<br>內固定裝置<br><sub>Internal Fixation Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2014, 耳鼻喉頭頸部, Q3 p.23 | ✅ 通過 |
| 梨形孔狹窄修擴術（鑿骨）→ **Excision**（0NBR0ZZ），非 Reposition<br>*切除增生骨質，非移位骨頭復位* | `0NBR0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `N`<br>頭與顏面骨<br><sub>Head and Facial Bones</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `R`<br>上頜骨<br><sub>Maxilla</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2022, 耳鼻喉頭頸部, Q2 p.22 | ✅ 通過 |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## Reposition Device 選擇

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Device Z = 無固定（徒手復位、石膏） | 閉合復位不固定 | ICD-10-PCS Table | 2023 PCS |
| — | — | — | — | Device 4 = 內固定（骨釘、骨板） | 開放或閉合復位＋固定 | ICD-10-PCS Table | 2023 PCS |
| — | — | — | — | Device 5 = 外固定（外固定架） | 外固定器 | ICD-10-PCS Table | 2023 PCS |
| — | — | — | — | Device 6 = 髓內釘（Intramedullary nail） | IM nail | ICD-10-PCS Table | 2023 PCS |

---

## 相關筆記
- [[Insertion vs Fusion vs Reposition 比較\|Insertion vs Fusion vs Reposition 比較]]
- [[Repair vs Replacement vs Supplement 比較\|Repair vs Replacement vs Supplement 比較]]
- [[Excision vs Resection 比較\|Excision vs Resection 比較]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
