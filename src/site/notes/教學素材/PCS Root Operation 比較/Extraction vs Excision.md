---
{"dg-publish":true,"permalink":"//pcs-root-operation/extraction-vs-excision/","title":"Extraction vs Excision 比較","tags":["ICD-10-PCS","Root-Operation","比較","Extraction","Excision","Delivery"],"dg-note-properties":{"title":"Extraction vs Excision 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Extraction","Excision","Delivery"],"system":"PCS 根本操作"}}
---

## Extraction（拉除）vs Excision（切除）比較

> PCS Root Operation D（Extraction）vs B（Excision）
> 核心差異：不切割直接拉出 vs 切割後取出部分

---

## 核心定義

| 項目 | Extraction（D）拉除 | Excision（B）切除 | Delivery（E）娩出 |
|------|-----------------|----------------|----------------|
| PCS 代碼 | D | B | E |
| 是否切割 | ❌ 不切割 Body Part | ✅ 切割後取出 | ❌ 自然娩出 |
| 適用對象 | 拔牙、骨髓抽取、靜脈剝除 | 皮膚腫瘤、息肉、活體切片 | **自然產（專用）** |
| Qualifier X | ✅（診斷性抽取） | ✅（切片） | — |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Extraction（拉除）= 以力量拉出，**不切割** Body Part 本身 | 拔、抽、剝、扯；工具可為鑷子、針筒、負壓吸引 | ICD-10-PCS Definitions | 2023 PCS, Root Operation D |
| — | — | — | — | Excision（切除）= **切割**後移除 Body Part **部分** | 有切割、有標本取出；全部切除 = Resection（T） | ICD-10-PCS Definitions | 2023 PCS, Root Operation B |
| — | — | — | — | Delivery（娩出）= **自然產專用**，胎兒自然娩出 | 僅用於產科章節（Section 1）；無需器械施力 | ICD-10-PCS Definitions | 2023 PCS, Section 1, Root Operation E |
| — | — | — | — | **⚠️ 自然產 = Delivery（E）10E0XZZ，絕非 Extraction** | Extraction 用於需器械施力取出（產鉗、真空、剖腹、吸引術） | ICD-10-PCS Section 1 | 2023 PCS, Table 10E |
| — | — | — | — | Phacoemulsification（超音波乳化術）= **Extraction（拉除）** | 超音波碎化後**吸出**，最終取除方式為吸出，非切割 | ICD-10-PCS Table 08D | 2023 PCS, Table 08D |
| — | — | — | — | 雷射汽化無標本 = **Destruction（破壞）**，非 Excision | 有標本 = Excision；無標本（原位摧毀）= Destruction | ICD-10-PCS Guidelines | 2023 PCS Guidelines, B3.5 |
| — | — | — | — | Qualifier X = Diagnostic（診斷性切片/抽取） | Excision + X = 刀切切片；Extraction + X = 抽吸切片（如骨髓） | ICD-10-PCS Guidelines | 2023 PCS Guidelines, B3.4a |

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
| 拔牙→ **Extraction（拉除）**（0CDXXZ0）<br>*拔牙：外部途徑，第7碼必填（0 單顆／1 多顆／2 全部）；下顎＝X，上顎＝W* | `0CDXXZ0` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `D`<br>拉除<br><sub>Extraction</sub> | `X`<br>下顎牙齒<br><sub>Lower Tooth</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `0`<br>單顆<br><sub>Single</sub> | ICD-10-PCS Table 0CD<br>2023 PCS, Table 0CD | ⚠️ 已修正：0CD 表拔牙第7碼無 Z，原碼無效 |
| 骨髓活體切片（Bone marrow biopsy）→ **Extraction（拉除）**（07DT0ZX）<br>*針筒抽取骨髓；Qualifier X* | `07DT0ZX` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `7`<br>淋巴與造血<br><sub>Lymphatic and Hemic Systems</sub> | `D`<br>拉除<br><sub>Extraction</sub> | `T`<br>骨髓<br><sub>Bone Marrow</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `X`<br>診斷性<br><sub>Diagnostic</sub> | ICD-10-PCS Table 07D<br>2023 PCS, Table 07D | ℹ️ 碼有效（Open）；針抽骨髓多為經皮 07DT3ZX（亦有效）。B3.4a：骨髓切片＝Extraction＋Diagnostic |
| 靜脈曲張剝除術（Vein stripping）→ **Extraction（拉除）**（06DP0ZZ）<br>*大隱靜脈剝除（右 P／左 Q）* | `06DP0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `6`<br>下靜脈<br><sub>Lower Veins</sub> | `D`<br>拉除<br><sub>Extraction</sub> | `P`<br>右大隱靜脈<br><sub>Saphenous Vein, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 06D<br>2023 PCS, Table 06D | ⚠️ 已修正：06D 表無第4碼 1；大隱靜脈右＝P、左＝Q |
| 白內障超音波乳化術（**未**植入 IOL）→ **Extraction（拉除）**（08DJ3ZZ，右眼）<br>*無 IOL 才編 Extraction；有植入 IOL 則編 Replacement（08RJ3JZ），不另編 Extraction* | `08DJ3ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `8`<br>眼<br><sub>Eye</sub> | `D`<br>拉除<br><sub>Extraction</sub> | `J`<br>右眼水晶體<br><sub>Lens, Right</sub> | `3`<br>經皮<br><sub>Percutaneous</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Index<br>2023 PCS, Index「Phacoemulsification, lens」 | ⚠️ 已修正：08D 表無第4碼 1，右眼水晶體＝J；Index：with IOL → Replacement 08R，without IOL → Extraction 08D |
| **自然產**（Vaginal delivery）→ **Delivery（E）**（10E0XZZ）<br>*⚠️ 非 Extraction；自然娩出專用 Root Operation* | `10E0XZZ` | `1`<br>產科<br><sub>Obstetrics</sub> | `0`<br>妊娠<br><sub>Pregnancy</sub> | `E`<br>分娩<br><sub>Delivery</sub> | `0`<br>妊娠產物<br><sub>Products of Conception</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 10E<br>2023 PCS, Table 10E | ✅ 10E 表驗證：Delivery 僅有 0 Products of Conception＋X External |
| 剖腹產（C-section）→ **Extraction（拉除）**（10D00Z0）<br>*切開子宮後取出胎兒；切的是子宮，Root Op 針對胎兒* | `10D00Z0` | `1`<br>產科<br><sub>Obstetrics</sub> | `0`<br>妊娠<br><sub>Pregnancy</sub> | `D`<br>拉除<br><sub>Extraction</sub> | `0`<br>妊娠產物<br><sub>Products of Conception</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `0`<br>高位<br><sub>High</sub> | ICD-10-PCS Table 10D<br>2023 PCS, Table 10D | ✅ 通過 |
| 產鉗助產（Forceps delivery）→ **Extraction（拉除）**（10D07Z3）<br>*產鉗助產：第7碼依產鉗位置（3 低位／4 中位／5 高位）* | `10D07Z3` | `1`<br>產科<br><sub>Obstetrics</sub> | `0`<br>妊娠<br><sub>Pregnancy</sub> | `D`<br>拉除<br><sub>Extraction</sub> | `0`<br>妊娠產物<br><sub>Products of Conception</sub> | `7`<br>經自然/人工開口<br><sub>Via Natural or Artificial Opening</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `3`<br>低位產鉗<br><sub>Low Forceps</sub> | ICD-10-PCS Table 10D<br>2023 PCS, Table 10D | ⚠️ 已修正：10D 表 7 途徑第7碼必填（3–8），Z 無效；此例以低位產鉗 3 示範 |
| 吸引式人工流產（Suction curettage）→ **Abortion（人工流產）**（10A07Z6）<br>*人工流產真空吸引：Abortion（10A0）、經自然開口 7、qualifier 6 Vacuum* | `10A07Z6` | `1`<br>產科<br><sub>Obstetrics</sub> | `0`<br>妊娠<br><sub>Pregnancy</sub> | `A`<br>人工流產<br><sub>Abortion</sub> | `0`<br>妊娠產物<br><sub>Products of Conception</sub> | `7`<br>經自然/人工開口<br><sub>Via Natural or Artificial Opening</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `6`<br>真空吸引<br><sub>Vacuum</sub> | ICD-10-PCS Index／Guidelines<br>2023 PCS, Index「Abortion, Vacuum 10A07Z6」；2025 PCS Guidelines C2（產後／流產後清除殘留→Extraction, Retained） | ⚠️ 已修正：10D00Z0 為剖腹產（High）；人工流產屬 Abortion |
| 皮膚腫瘤切除術→ **Excision（切除）**（0HB0XZZ）<br>*切割取出部分皮膚；有標本* | `0HB0XZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `H`<br>皮膚與乳房<br><sub>Skin and Breast</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `0`<br>頭皮皮膚<br><sub>Skin, Scalp</sub> | `X`<br>外部<br><sub>External</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0HB<br>2023 PCS, Table 0HB | ✅ 通過 |
| 結腸息肉切除術→ **Excision（切除）**（0DBN8ZZ）<br>*內視鏡切除息肉；有標本* | `0DBN8ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `D`<br>消化系統<br><sub>Gastrointestinal System</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `N`<br>乙狀結腸<br><sub>Sigmoid Colon</sub> | `8`<br>經自然/人工開口＋內視鏡<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0DB<br>2023 PCS, Table 0DB | ✅ 通過 |
| 淺層腮腺切除術→ **Excision（切除）**（0CB80ZZ）<br>*保留深葉，切割取出淺葉* | `0CB80ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `B`<br>切除部分<br><sub>Excision</sub> | `8`<br>右腮腺<br><sub>Parotid Gland, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2014, 耳鼻喉頭頸部, Q3 p.21 | ✅ 通過 |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Excision vs Resection 比較\|Excision vs Resection 比較]]
- [[Control vs Repair vs Destruction 比較\|Control vs Repair vs Destruction 比較]]
- [[Repair vs Replacement vs Supplement 比較\|Repair vs Replacement vs Supplement 比較]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
