---
{"dg-publish":true,"permalink":"//pcs-root-operation/dilation-vs-restriction/","title":"Dilation vs Restriction 比較","tags":["ICD-10-PCS","Root-Operation","比較","Dilation","Restriction"],"dg-note-properties":{"title":"Dilation vs Restriction 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Dilation","Restriction"],"system":"PCS 根本操作"}}
---

## Dilation（擴張）vs Restriction（限縮）比較

> PCS Root Operation 7（Dilation）vs V（Restriction）
> 方向相反：一個「撐大」，一個「縮小」

---

## 核心定義

| 項目 | Dilation（7）擴張 | Restriction（V）限縮 |
|------|----------------|---------------------|
| PCS 代碼 | 7 | V |
| 管腔結果 | 變大（通暢） | 變小（受限） |
| 適應症 | 管腔狹窄 | 管腔過大/鬆弛 |
| 類比 | 撐開水管 | 夾緊水管 |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Dilation（擴張）= 擴大管狀 Body Part 的開口或管腔 | 氣球擴張、支架置入；管腔狹窄時使用 | ICD-10-PCS Definitions | 2023 PCS, Root Operation 7 |
| — | — | — | — | Restriction（限縮）= **部分**關閉管狀 Body Part 的開口或管腔 | 束帶、環紮、縮環；管腔仍可部分通過 | ICD-10-PCS Definitions | 2023 PCS, Root Operation V |
| — | — | — | — | Dilation＋支架（Stent）= Device D（Intraluminal）；不另編 Insertion | PTCA＋支架於同一代碼編 Device D，不需另編 Insertion | ICD-10-PCS Guidelines | 2023 PCS Table 027 Device 欄；Guideline B6.1a（裝置留於體內才編碼） |
| — | — | — | — | Restriction Device C = Extraluminal（管腔外夾緊） | 胃束帶（Lap-Band 屬 Extraluminal Device，0DV64CZ）；子宮頸環紮碼 0UVC7ZZ 第6碼為 Z（無裝置） | ICD-10-PCS Table | 2023 PCS, Device column |
| — | — | — | — | Restriction Device D = Intraluminal（管腔內縮限） | 管腔內縮限裝置 | ICD-10-PCS Table | 2023 PCS, Device column |
| — | — | — | — | Restriction Device Z = No Device（縫合縮小） | 縫合縮小管腔，無置入裝置 | ICD-10-PCS Table | 2023 PCS, Device column |

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
| 冠狀動脈 PTCA→ **Dilation（擴張）**（02703DZ）<br>*氣球擴張＋一般冠狀動脈支架：Device D（Intraluminal Device）* | `02703DZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `7`<br>擴張<br><sub>Dilation</sub> | `0`<br>冠狀動脈（一條）<br><sub>Coronary Artery, One Artery</sub> | `3`<br>經皮<br><sub>Percutaneous</sub> | `D`<br>腔內裝置<br><sub>Intraluminal Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 027<br>2023 PCS, Table 027 | ⚠️ 已修正：原碼 0270346 第6碼 4＝藥物塗層支架、第7碼 6＝分叉，與「Device D」敘述不符；一般支架為 02703DZ |
| 後鼻孔閉鎖擴張術→ **Dilation（擴張）**（0978NZZ）<br>*新增 Body Part N（Nasopharynx）* | `0978NZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `7`<br>擴張<br><sub>Dilation</sub> | `8`<br>鼻咽<br><sub>Nasopharynx</sub> | `N`<br>Via Natural or Artificial Opening Endoscopic<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2024, 耳鼻喉頭頸部, Q1 | ❔ 2023 版工具書 097 表無 N（鼻咽）；依 AHA CC 2024 Q1 新增（vault：依科別／耳鼻喉頭頸部）。官方 2023 表無法核對 |
| 食道狹窄氣球擴張術→ **Dilation（擴張）**（0D758ZZ）<br>*內視鏡氣球擴張食道狹窄段（食道 5、經自然開口內視鏡 8）* | `0D758ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `D`<br>消化系統<br><sub>Gastrointestinal System</sub> | `7`<br>擴張<br><sub>Dilation</sub> | `5`<br>食道<br><sub>Esophagus</sub> | `8`<br>經自然/人工開口＋內視鏡<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0D7<br>2023 PCS, Table 0D7 | ⚠️ 已修正：原碼 0D773ZZ 第4碼 7＝胃幽門（Stomach, Pylorus）；食道為 5 |
| 尿道狹窄擴張術→ **Dilation（擴張）**（0T7D7ZZ）<br>*擴張尿道* | `0T7D7ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `T`<br>泌尿系統<br><sub>Urinary System</sub> | `7`<br>擴張<br><sub>Dilation</sub> | `D`<br>尿道<br><sub>Urethra</sub> | `7`<br>經自然/人工開口<br><sub>Via Natural or Artificial Opening</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0T7<br>2023 PCS, Table 0T7 | ✅ 通過 |
| 膽管狹窄 ERCP 擴張→ **Dilation（擴張）**（0F798ZZ）<br>*擴張膽管* | `0F798ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `F`<br>肝膽胰<br><sub>Hepatobiliary System and Pancreas</sub> | `7`<br>擴張<br><sub>Dilation</sub> | `9`<br>總膽管<br><sub>Common Bile Duct</sub> | `8`<br>經自然/人工開口＋內視鏡<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0F7<br>2023 PCS, Table 0F7 | ✅ 通過 |
| 氣球鼻竇成形術（Balloon sinuplasty）→ AHA 預設 **Repair**（09QT4ZZ）<br>*2013 Q4 AHA 無特定擴張代碼，預設 Repair* | `09QT4ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `9`<br>耳鼻竇<br><sub>Ear, Nose, Sinus</sub> | `Q`<br>修補<br><sub>Repair</sub> | `T`<br>左額竇<br><sub>Frontal Sinus, Left</sub> | `4`<br>經皮內視鏡<br><sub>Percutaneous Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2013, 耳鼻喉頭頸部, Q4 p.114 | ℹ️ 第4碼 T＝左額竇（Frontal Sinus, Left）；其他鼻竇各有獨立碼值 |
| 胃束帶術（Lap-Band）→ **Restriction（限縮）**（0DV64CZ）<br>*縮小胃口；Device C（Extraluminal）* | `0DV64CZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `D`<br>消化系統<br><sub>Gastrointestinal System</sub> | `V`<br>限縮<br><sub>Restriction</sub> | `6`<br>胃<br><sub>Stomach</sub> | `4`<br>經皮內視鏡<br><sub>Percutaneous Endoscopic</sub> | `C`<br>腔外裝置<br><sub>Extraluminal Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0DV<br>2023 PCS, Table 0DV | ✅ 通過 |
| 子宮頸環紮術（Cerclage）→ **Restriction（限縮）**（0UVC7ZZ）<br>*縮小頸口防早產；第6碼＝Z（無裝置）* | `0UVC7ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `U`<br>女性生殖<br><sub>Female Reproductive System</sub> | `V`<br>限縮<br><sub>Restriction</sub> | `C`<br>子宮頸<br><sub>Cervix</sub> | `7`<br>經自然/人工開口<br><sub>Via Natural or Artificial Opening</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0UV<br>2023 PCS, Table 0UV | ℹ️ 官方 Index：Cerclage → Restriction；第6碼為 Z，非原寫的 Device C |
| 心瓣膜環縮術（Annuloplasty ring）→ **Supplement（強化）**（02UG0JZ）<br>*天然瓣膜保留，以環強化 → Supplement（Index：Annuloplasty → Repair 02Q／Supplement 02U）* | `02UG0JZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `U`<br>補強<br><sub>Supplement</sub> | `G`<br>二尖瓣<br><sub>Mitral Valve</sub> | `0`<br>開放<br><sub>Open</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Index／Definitions<br>2023 PCS, Index「Annuloplasty」；Operation U 定義舉例含 mitral valve ring annuloplasty | ⚠️ 已修正：02V 表無第4碼 F；環縮術不屬 Restriction，Index 指向 Repair／Supplement（二尖瓣環＝02UG0JZ） |
| 會厭固定術（Epiglottopexy）→ **Reposition（復位）**（0CSR8ZZ）<br>*會厭固定術：移動會厭至適當位置 → Reposition（第3碼 S）* | `0CSR8ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `S`<br>復位<br><sub>Reposition</sub> | `R`<br>會厭<br><sub>Epiglottis</sub> | `8`<br>經自然/人工開口＋內視鏡<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2016, 耳鼻喉頭頸部, Q3 p.28 | ⚠️ 已修正根手術：碼的第3碼 S＝Reposition，非 Restriction |
| 膀胱頸懸吊術（Bladder neck sling）→ **Reposition（復位）**（0TSC0ZZ）<br>*膀胱頸懸吊（肌肉吊帶）→ Reposition, Bladder Neck* | `0TSC0ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `T`<br>泌尿系統<br><sub>Urinary System</sub> | `S`<br>復位<br><sub>Reposition</sub> | `C`<br>膀胱頸<br><sub>Bladder Neck</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Index<br>2023 PCS, Index「Sling, Levator／Pubococcygeal muscle, for urethral suspension」→ 0TSC | ⚠️ 已修正：原碼 0TVD0ZZ 為 Restriction, Urethra；Index 對肌肉吊帶尿道懸吊指向 Reposition Bladder Neck 0TSC。其他吊帶材質請另查 Index |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Occlusion vs Restriction vs Bypass 比較\|Occlusion vs Restriction vs Bypass 比較]]
- [[Control vs Repair vs Destruction 比較\|Control vs Repair vs Destruction 比較]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
