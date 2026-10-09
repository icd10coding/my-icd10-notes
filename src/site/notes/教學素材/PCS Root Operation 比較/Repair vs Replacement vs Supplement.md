---
{"dg-publish":true,"permalink":"//pcs-root-operation/repair-vs-replacement-vs-supplement/","title":"Repair vs Replacement vs Supplement 比較","tags":["ICD-10-PCS","Root-Operation","比較","Repair","Replacement","Supplement"],"dg-note-properties":{"title":"Repair vs Replacement vs Supplement 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Repair","Replacement","Supplement"],"system":"PCS 根本操作"}}
---

## Repair（修復）vs Replacement（置換）vs Supplement（強化）比較

> PCS Root Operation Q（Repair）vs R（Replacement）vs U（Supplement）
> 核心差異：不加材料修補 vs 移除原組織換新 vs 保留原組織加材料補強

---

## 核心定義

| 項目 | Repair（Q） | Replacement（R）置換 | Supplement（U）強化 |
|------|-----------|-------------------|-------------------|
| PCS 代碼 | Q | R | U |
| 是否移除原組織 | ❌ | ✅ 移除 | ❌ |
| 是否使用 Device | 通常 Z | 必須有 | 必須有 |
| 類比 | 縫合修補 | 換零件 | 打補丁補強 |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Repair（修復）= 恢復正常結構，**不加材料** | 縫合、修補，Device = Z No Device | ICD-10-PCS Definitions | 2023 PCS, Root Operation Q |
| — | — | — | — | Replacement（置換）= 移除原組織，**以材料取代** | 須先有 Excision/Resection；但前置切除**不另編碼**（Guideline B3.1b；B3.18） | ICD-10-PCS Guidelines | 2025 PCS Guidelines, B3.1b；B3.18 |
| — | — | — | — | Supplement（強化）= 保留原組織，**加材料補強功能** | 原 Body Part 保留，材料輔助強化；Device 必填 | ICD-10-PCS Definitions | 2023 PCS, Root Operation U |
| — | — | — | — | Replacement 前置切除不另編 | Guideline B6.1a：若 Replacement 含切除步驟，不另編 Excision/Resection | PCS Guidelines | 2025 PCS Guidelines, B3.1b；B3.18 |
| — | — | — | — | Device 7 = Autologous（自體組織） | 自體骨、自體腱、自體皮膚 | ICD-10-PCS Table | 2023 PCS, Device column |
| — | — | — | — | Device J = Synthetic Substitute（合成） | 鈦板、網片、PE、PTFE | ICD-10-PCS Table | 2023 PCS, Device column |
| — | — | — | — | Device K = Nonautologous（異種/異體） | 豬皮、牛心包膜、同種異體骨 | ICD-10-PCS Table | 2023 PCS, Device column |

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
| 鼻翼撕裂縫合→ **Repair**（09QKXZZ）<br>*縫合，不加材料* | `09QKXZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `Q`<br>修補<br><sub>Repair</sub> | `K`<br>鼻黏膜與軟組織<br><sub>Nasal Mucosa and Soft Tissue</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 09Q<br>2023 PCS, Table 09Q | ✅ 通過 |
| VSD 直接縫合（小缺損）→ **Repair**（02QM0ZZ）<br>*縫合心室中隔，不加材料* | `02QM0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `Q`<br>修補<br><sub>Repair</sub> | `M`<br>心室中隔<br><sub>Ventricular Septum</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 02Q<br>2023 PCS, Table 02Q | ⚠️ 已修正：02Q 的 6＝右心房；心室中隔（VSD）＝M |
| VSD 補丁修補（大缺損）→ **Supplement**（02UM0JZ）<br>*保留室中隔，加補丁強化* | `02UM0JZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `U`<br>補強<br><sub>Supplement</sub> | `M`<br>心室中隔<br><sub>Ventricular Septum</sub> | `0`<br>開放<br><sub>Open</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 02U<br>2023 PCS, Table 02U | ⚠️ 已修正：02U 的 6＝右心房；心室中隔（VSD）＝M |
| 全髖關節置換術（THA）→ **Replacement**（0SR902Z）<br>*全髖置換（右髖例：金屬對聚乙烯）；側別、材質、固定方式決定第4、6、7碼* | `0SR902Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `S`<br>下部關節<br><sub>Lower Joints</sub> | `R`<br>置換<br><sub>Replacement</sub> | `9`<br>右髖關節<br><sub>Hip Joint, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `2`<br>合成替代物（金屬對聚乙烯）<br><sub>Synthetic Substitute, Metal on Polyethylene</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 05R<br>2023 PCS, Table 05R | ⚠️ 已修正：05R 為上靜脈（B＝右貴要靜脈），不是髖關節；髖關節屬 0S（下部關節） |
| 白內障（IOL）→ **Replacement**（08RJ3JZ）<br>*移除天然水晶體，換人工水晶體* | `08RJ3JZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `8`<br>眼<br><sub>Eye</sub> | `R`<br>置換<br><sub>Replacement</sub> | `J`<br>右眼水晶體<br><sub>Lens, Right</sub> | `3`<br>經皮<br><sub>Percutaneous</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 08R<br>2023 PCS, Table 08R | ✅ 通過 |
| 疝氣修補＋網片→ **Supplement**（0WUF0JZ）<br>*腹壁保留，網片補強（最經典 Supplement 範例）* | `0WUF0JZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `W`<br>解剖區域－一般<br><sub>Anatomical Regions, General</sub> | `U`<br>補強<br><sub>Supplement</sub> | `F`<br>腹壁<br><sub>Abdominal Wall</sub> | `0`<br>開放<br><sub>Open</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0WU<br>2023 PCS, Table 0WU | ✅ 通過 |
| 心瓣膜環縮術（Annuloplasty）→ **Supplement**（02UG0JZ）<br>*天然瓣膜保留，縮環強化* | `02UG0JZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `U`<br>補強<br><sub>Supplement</sub> | `G`<br>二尖瓣<br><sub>Mitral Valve</sub> | `0`<br>開放<br><sub>Open</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 02U<br>2023 PCS, Table 02U | ✅ 通過 |
| 心瓣膜置換術（SAVR）→ **Replacement**（02RF08Z）<br>*主動脈瓣置換，生物瓣＝動物源組織 Zooplastic（8）；自體組織（7，如 Ross）才用 7* | `02RF08Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `R`<br>置換<br><sub>Replacement</sub> | `F`<br>主動脈瓣<br><sub>Aortic Valve</sub> | `0`<br>開放<br><sub>Open</sub> | `8`<br>動物源組織<br><sub>Zooplastic Tissue</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 02R<br>2023 PCS, Table 02R | ⚠️ 已修正：第6碼 7＝Autologous Tissue Substitute，動物源生物瓣為 8 Zooplastic Tissue |
| 上半規管骨水泥修補→ **Supplement**（0NU50KZ）<br>*顳骨保留，骨水泥填補強化* | `0NU50KZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `N`<br>頭與顏面骨<br><sub>Head and Facial Bones</sub> | `U`<br>補強<br><sub>Supplement</sub> | `5`<br>右顳骨<br><sub>Temporal Bone, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `K`<br>非自體組織替代物<br><sub>Nonautologous Tissue Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2021, 耳鼻喉頭頸部, Q3 p.17 | ℹ️ 第6碼 K＝Nonautologous Tissue Substitute（官方）；原敘述「骨水泥」請對照 AHA 原文確認材質歸類 |
| 軟顎切除＋阻塞器→ **Replacement**（0CR3XJZ）<br>*移除軟顎組織，阻塞器取代功能* | `0CR3XJZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `R`<br>置換<br><sub>Replacement</sub> | `3`<br>軟顎<br><sub>Soft Palate</sub> | `X`<br>外部<br><sub>External</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2014, 耳鼻喉頭頸部, Q3 p.25 | ✅ 通過 |
| 下頜骨重建（自體骨）→ **Replacement**（0NRV07Z）<br>*移除骨段，自體骨置換* | `0NRV07Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `N`<br>頭與顏面骨<br><sub>Head and Facial Bones</sub> | `R`<br>置換<br><sub>Replacement</sub> | `V`<br>左下頜骨<br><sub>Mandible, Left</sub> | `0`<br>開放<br><sub>Open</sub> | `7`<br>自體組織替代物<br><sub>Autologous Tissue Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2017, 耳鼻喉頭頸部, Q1 p.20 | ✅ 通過 |
| 唇裂修復（旋轉推進皮瓣）→ **Transfer**（非 Repair）<br>*帶蒂皮瓣移至新位置 = Transfer，非 Repair* | — | — | — | — | — | — | — | — | AHA Coding Clinic<br>2015, 耳鼻喉頭頸部, Q3 p.33 | — 原文無 PCS 代碼 |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Control vs Repair vs Destruction 比較\|Control vs Repair vs Destruction 比較]]
- [[Insertion vs Replacement vs Supplement 比較\|Insertion vs Replacement vs Supplement 比較]]
- [[Fusion vs Reposition 比較\|Fusion vs Reposition 比較]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
