---
{"dg-publish":true,"permalink":"//pcs-root-operation/control-vs-repair-vs-destruction/","title":"Control vs Repair vs Destruction 比較","tags":["ICD-10-PCS","Root-Operation","比較","Control","Repair","Destruction"],"dg-note-properties":{"title":"Control vs Repair vs Destruction 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Control","Repair","Destruction"],"system":"PCS 根本操作"}}
---

## Control（控制）vs Repair（修復）vs Destruction（破壞）比較

> PCS Root Operation 3（Control）vs Q（Repair）vs 5（Destruction）
> 三者皆可用於「出血/病灶處置」，是臨床最常混淆的手術方式組合。

---

## 核心定義

| 項目 | Control（3） | Repair（Q）修復 | Destruction（5）破壞 |
|------|------------|--------------|-------------------|
| PCS 代碼 | 3 | Q | 5 |
| 核心目的 | 停止術後/急性出血 | 恢復正常結構（縫合修補） | 摧毀組織（燒灼/冷凍/雷射） |
| 出血必要條件 | ✅ 必須有出血 | ❌ | ❌ |
| 術後情境 | ✅ 術後出血首選 | ❌ | ❌ |
| 組織結果 | 保留（止血後） | 保留（縫合後） | 摧毀（不保留） |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Control = 停止**術後或急性**出血 | 用於術後出血返回手術室；Body Part 選用解剖區域（Anatomical Region），非具體器官 | ICD-10-PCS Definitions | 2023 PCS, Root Operation 3 |
| — | — | — | — | Repair = 恢復正常結構，**縫合修補** | 縫合裂傷、穿孔；Device = Z；非止血專用，可兼具止血效果 | ICD-10-PCS Definitions | 2023 PCS, Root Operation Q |
| — | — | — | — | Destruction（破壞）= 以能量/化學物質**摧毀**組織 | 電燒、硝酸銀、CO2 雷射、冷凍、RFA；無組織取出（有取出 = Excision） | ICD-10-PCS Definitions | 2023 PCS, Root Operation 5 |
| — | — | — | — | Control 使用解剖區域 Body Part（非器官） | 例：腹腔出血 → Gastrointestinal Tract；胸腔 → Pleural Cavity | ICD-10-PCS Guidelines | 2025 PCS Guidelines, B3.7；B2.1a |
| — | — | — | — | 雷射汽化術 = Destruction（破壞），非 Excision | 汽化後無組織取出 → Destruction；有標本取出 → Excision | ICD-10-PCS Guidelines | 2023 PCS, Root Operation 5 定義（原引 B3.5 為「重疊肌肉骨骼層次」，與本列無關） |

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
| 鼻出血硝酸銀燒灼→ **Control（控制）**（093K8ZZ）<br>*硝酸銀燒灼急性鼻出血 = Control（Guideline 範例）；非 Destruction* | `093K8ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `3`<br>控制出血<br><sub>Control</sub> | `K`<br>鼻黏膜組織<br><sub>Nasal Mucosa Tissue</sub> | `8`<br>經自然/人工開口＋內視鏡<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | PCS Guidelines + AHA Coding Clinic<br>2025 PCS Guidelines B3.7；2018 Q4（[[每日筆記/AHA CC 2018Q4/CC2018Q4-13 止鼻血（鼻黏膜軟組織 Control）\|CC2018Q4-13 止鼻血（鼻黏膜軟組織 Control）]]） | ⚠️ 已修正：原寫 Destruction／0W3Q8ZZ（0W3Q8ZZ 實為 Control of Respiratory Tract）；B3.7 範例明示硝酸銀燒灼鼻出血＝Control |
| 鼻出血縫合止血（原發性）→ **Repair**（09QKXZZ）<br>*非術後出血縫合 → Repair；非 Control* | `09QKXZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `Q`<br>修補<br><sub>Repair</sub> | `K`<br>鼻黏膜與軟組織<br><sub>Nasal Mucosa and Soft Tissue</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2014, 耳鼻喉頭頸部, Q4 p.20 | ✅ 通過 |
| 鼻出血鼻腔填塞→ **Packing**（2Y41X5Z）<br>*填塞屬安置章節，非手術方式* | `2Y41X5Z` | `2`<br>放置<br><sub>Placement</sub> | `Y`<br>解剖孔口<br><sub>Anatomical Orifices</sub> | `4`<br>填塞<br><sub>Packing</sub> | `1`<br>鼻腔<br><sub>Nasal</sub> | `X`<br>外部<br><sub>External</sub> | `5`<br>填塞材料<br><sub>Packing Material</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2017, 耳鼻喉頭頸部, Q4 p.106 | ✅ 通過 |
| 術後鼻出血返回手術室→ **Control**（0W3Q0ZZ）<br>*術後出血 = Control；2016/10 後定義更新* | `0W3Q0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `W`<br>解剖區域－一般<br><sub>Anatomical Regions, General</sub> | `3`<br>控制出血<br><sub>Control</sub> | `Q`<br>呼吸道<br><sub>Respiratory Tract</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2017, 耳鼻喉頭頸部, Q4 p.106 | ⚠️ 碼有效，但鼻部出血自 FY2019 另有 093K（Control Nasal Mucosa）專表；0W3Q 為「呼吸道」區域碼，請依出血部位／AHA 原文選擇 |
| 甲狀腺切除術後甲狀腺床出血→ **Control**<br>*術後出血；診斷碼 E36.01* | — | — | — | — | — | — | — | — | AHA Coding Clinic<br>2020, 依科別, Q1 | — 原文無 PCS 代碼 |
| ETT 插管撕裂軟腭縫合→ **Repair**<br>*醫療操作意外縫合；診斷碼 K91.72 + Y65.8* | — | — | — | — | — | — | — | — | AHA Coding Clinic<br>2019, 耳鼻喉頭頸部, Q2 p.23 | — 原文無 PCS 代碼 |
| 軟顎紅斑症 CO2 雷射汽化→ **Destruction（破壞）**（0C53XZZ）<br>*雷射汽化無標本 = 破壞* | `0C53XZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `5`<br>破壞<br><sub>Destruction</sub> | `3`<br>軟顎<br><sub>Soft Palate</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0C5<br>2023 PCS, Table 0C5 | ✅ 通過 |
| 肝腫瘤射頻消融（RFA）→ **Destruction（破壞）**（0F500ZZ）<br>*熱能摧毀，無標本取出* | `0F500ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `F`<br>肝膽胰<br><sub>Hepatobiliary System and Pancreas</sub> | `5`<br>破壞<br><sub>Destruction</sub> | `0`<br>肝臟<br><sub>Liver</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0F5<br>2023 PCS, Table 0F5 | ✅ 通過 |
| NG 管置入後鼻出血→診斷碼 **J95.831**，非外傷碼<br>*醫療干預造成 → 術後出血診斷碼；PCS 另編* | — | — | — | — | — | — | — | — | AHA Coding Clinic<br>2023, 耳鼻喉頭頸部, Q2 p.28 | — 原文無 PCS 代碼 |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Repair vs Replacement vs Supplement 比較\|Repair vs Replacement vs Supplement 比較]]
- [[Excision vs Resection 比較\|Excision vs Resection 比較]]
- [[教學素材/CM 系統分類/H - 耳鼻喉科/ENT 耳鼻喉科編碼彙整（AHA Coding Clinic Q&A）\|ENT 耳鼻喉科編碼彙整（AHA Coding Clinic Q&A）]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
