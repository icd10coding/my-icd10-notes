---
{"dg-publish":true,"permalink":"//pcs-root-operation/occlusion-vs-restriction-vs-bypass/","title":"Occlusion vs Restriction vs Bypass 比較","tags":["ICD-10-PCS","Root-Operation","比較","Occlusion","Restriction","Bypass"],"dg-note-properties":{"title":"Occlusion vs Restriction vs Bypass 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Occlusion","Restriction","Bypass"],"system":"PCS 根本操作"}}
---

## Occlusion（阻塞）vs Restriction（限縮）vs Bypass（繞道）比較

> PCS Root Operation L（Occlusion）vs V（Restriction）vs 1（Bypass）
> 三者皆與「管腔/血流」相關，常見於血管介入、腸胃、泌尿系統手術。

---

## 核心定義

| 項目 | Occlusion（L）阻塞 | Restriction（V）限縮 | Bypass（1）繞道 |
|------|-----------------|---------------------|----------------|
| PCS 代碼 | L | V | 1 |
| 管腔結果 | **完全封閉**（0% 通過） | **縮小**（仍可通過） | **改道**（繞過原路徑） |
| 是否保留流通 | ❌ 完全阻斷 | ✅ 部分保留 | ✅ 改道後仍流通 |
| 類比 | 完全關閉水管 | 夾緊水管 | 改挖新水道 |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Occlusion（阻塞）= **完全封閉**管腔或血管 | 結紮、栓塞；目的是永久或暫時完全阻斷 | ICD-10-PCS Definitions | 2023 PCS, Root Operation L |
| — | — | — | — | Restriction（限縮）= **縮小**管腔，不完全封閉 | 束帶、環紮、縮環；液體/氣體仍可通過 | ICD-10-PCS Definitions | 2023 PCS, Root Operation V |
| — | — | — | — | Bypass（繞道）= 改變管狀 Body Part 內容物流通路徑 | 第七碼 Qualifier 代表流向**終點**（To where） | ICD-10-PCS Definitions | 2023 PCS, Root Operation 1 |
| — | — | — | — | Bypass Qualifier = 終點（目的地） | 如 CABG Qualifier 3 = Coronary Artery（冠狀動脈） | ICD-10-PCS Table | 2023 PCS, Table 021 |
| — | — | — | — | Device C = Extraluminal（管腔外夾緊） | 胃束帶（Lap-Band 屬 Extraluminal Device，0DV64CZ）；子宮頸環紮碼 0UVC7ZZ 第6碼為 Z（無裝置） | ICD-10-PCS Table | 2023 PCS, Device column |
| — | — | — | — | Device D = Intraluminal（管腔內裝置） | 支架（Stent）、栓塞線圈（Coil） | ICD-10-PCS Table | 2023 PCS, Device column |

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
| 輸卵管結紮術→ **Occlusion（阻塞）**（0UL74ZZ）<br>*完全封閉輸卵管；永久避孕* | `0UL74ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `U`<br>女性生殖<br><sub>Female Reproductive System</sub> | `L`<br>阻塞<br><sub>Occlusion</sub> | `7`<br>雙側輸卵管<br><sub>Fallopian Tubes, Bilateral</sub> | `4`<br>經皮內視鏡<br><sub>Percutaneous Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0UL<br>2023 PCS, Table 0UL | ✅ 通過 |
| 腦動脈瘤栓塞術（Coil）→ **Restriction（限縮）**（03VG3DZ）<br>*腦動脈瘤栓塞：目的是縮窄瘤處管腔、非完全封閉 → Restriction* | `03VG3DZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `3`<br>上動脈<br><sub>Upper Arteries</sub> | `V`<br>限縮<br><sub>Restriction</sub> | `G`<br>顱內動脈<br><sub>Intracranial Artery</sub> | `3`<br>經皮<br><sub>Percutaneous</sub> | `D`<br>腔內裝置<br><sub>Intraluminal Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | PCS Guidelines<br>2025 PCS Guidelines B3.12（Embolization of a cerebral aneurysm → Restriction） | ⚠️ 已修正：B3.12 範例明示腦動脈瘤栓塞＝Restriction |
| 子宮肌瘤栓塞術（UAE）→ **Occlusion（阻塞）**（04LE3DZ）<br>*栓塞子宮動脈阻斷供血* | `04LE3DZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `4`<br>下動脈<br><sub>Lower Arteries</sub> | `L`<br>阻塞<br><sub>Occlusion</sub> | `E`<br>右髂內動脈<br><sub>Internal Iliac Artery, Right</sub> | `3`<br>經皮<br><sub>Percutaneous</sub> | `D`<br>腔內裝置<br><sub>Intraluminal Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 04L<br>2023 PCS, Table 04L | ℹ️ 子宮動脈無獨立碼值，依 B4.2 編至最近端有碼值的分支（髂內動脈）；腫瘤栓塞＝Occlusion（B3.12）；雙側另編左側 |
| 食道靜脈曲張結紮（套扎）→ **Occlusion（阻塞）**（06L38CZ）<br>*內視鏡套扎曲張靜脈：Extraluminal Device（C）、經自然開口內視鏡（8）* | `06L38CZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `6`<br>下靜脈<br><sub>Lower Veins</sub> | `L`<br>阻塞<br><sub>Occlusion</sub> | `3`<br>食道靜脈<br><sub>Esophageal Vein</sub> | `8`<br>經自然/人工開口＋內視鏡<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `C`<br>腔外裝置<br><sub>Extraluminal Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Index<br>2023 PCS, Index「Banding, esophageal varices」→ Occlusion, Vein, Esophageal 06L3 | ⚠️ 已修正：硬化劑注射屬 Administration（Introduction of Destructive Agent），非 Occlusion；套扎才是 06L3 |
| 胃束帶術（Gastric banding）→ **Restriction（限縮）**（0DV64CZ）<br>*縮小胃口；Device C（Extraluminal）* | `0DV64CZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `D`<br>消化系統<br><sub>Gastrointestinal System</sub> | `V`<br>限縮<br><sub>Restriction</sub> | `6`<br>胃<br><sub>Stomach</sub> | `4`<br>經皮內視鏡<br><sub>Percutaneous Endoscopic</sub> | `C`<br>腔外裝置<br><sub>Extraluminal Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0DV<br>2023 PCS, Table 0DV | ✅ 通過 |
| 子宮頸環紮術（Cerclage）→ **Restriction（限縮）**（0UVC7ZZ）<br>*縮小頸口防早產；第6碼＝Z（無裝置）* | `0UVC7ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `U`<br>女性生殖<br><sub>Female Reproductive System</sub> | `V`<br>限縮<br><sub>Restriction</sub> | `C`<br>子宮頸<br><sub>Cervix</sub> | `7`<br>經自然/人工開口<br><sub>Via Natural or Artificial Opening</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0UV<br>2023 PCS, Table 0UV | ℹ️ 官方 Index：Cerclage → Restriction；第6碼為 Z，非原寫的 Device C |
| 心瓣膜環縮術（Annuloplasty）→ **Supplement（強化）**（02UG0JZ）<br>*天然瓣膜保留，以環強化 → Supplement（Index：Annuloplasty → Repair 02Q／Supplement 02U）* | `02UG0JZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `U`<br>補強<br><sub>Supplement</sub> | `G`<br>二尖瓣<br><sub>Mitral Valve</sub> | `0`<br>開放<br><sub>Open</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Index／Definitions<br>2023 PCS, Index「Annuloplasty」；Operation U 定義舉例含 mitral valve ring annuloplasty | ⚠️ 已修正：02V 表無第4碼 F；環縮術不屬 Restriction，Index 指向 Repair／Supplement（二尖瓣環＝02UG0JZ） |
| 會厭固定術（Epiglottopexy）→ **Reposition（復位）**（0CSR8ZZ）<br>*會厭固定術：移動會厭至適當位置 → Reposition（第3碼 S）* | `0CSR8ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `C`<br>口與喉<br><sub>Mouth and Throat</sub> | `S`<br>復位<br><sub>Reposition</sub> | `R`<br>會厭<br><sub>Epiglottis</sub> | `8`<br>經自然/人工開口＋內視鏡<br><sub>Via Natural or Artificial Opening Endoscopic</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2016, 耳鼻喉頭頸部, Q3 p.28 | ⚠️ 已修正根手術：碼的第3碼 S＝Reposition，非 Restriction |
| 冠狀動脈繞道術（CABG）→ **Bypass（繞道）**（0210093）<br>*靜脈橋接繞過狹窄；Qualifier 3 = Coronary Artery* | `0210093` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `2`<br>心臟與大血管<br><sub>Heart and Great Vessels</sub> | `1`<br>繞道<br><sub>Bypass</sub> | `0`<br>冠狀動脈（一條）<br><sub>Coronary Artery, One Artery</sub> | `0`<br>開放<br><sub>Open</sub> | `9`<br>自體靜脈組織<br><sub>Autologous Venous Tissue</sub> | `3`<br>繞道終點：冠狀動脈<br><sub>Coronary Artery</sub> | ICD-10-PCS Table 021<br>2023 PCS, Table 021 | ✅ 通過 |
| 全喉切除術後 TEP→ **Bypass（繞道）**（0B110D6）<br>*氣管繞道至食道；Qualifier 6 = Esophagus* | `0B110D6` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `B`<br>呼吸系統<br><sub>Respiratory System</sub> | `1`<br>繞道<br><sub>Bypass</sub> | `1`<br>氣管<br><sub>Trachea</sub> | `0`<br>開放<br><sub>Open</sub> | `D`<br>腔內裝置<br><sub>Intraluminal Device</sub> | `6`<br>繞道終點：食道<br><sub>Esophagus</sub> | AHA Coding Clinic<br>2025, 耳鼻喉頭頸部, Q1 | ✅ 通過 |
| VP shunt（腦室腹腔分流）→ **Bypass（繞道）**（00160J6）<br>*腦室液繞至腹腔；Qualifier 6 = Peritoneal Cavity* | `00160J6` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `0`<br>中樞神經與顱神經<br><sub>Central Nervous System and Cranial Nerves</sub> | `1`<br>繞道<br><sub>Bypass</sub> | `6`<br>腦室<br><sub>Cerebral Ventricle</sub> | `0`<br>開放<br><sub>Open</sub> | `J`<br>合成替代物<br><sub>Synthetic Substitute</sub> | `6`<br>繞道終點：腹腔<br><sub>Peritoneal Cavity</sub> | ICD-10-PCS Table 001<br>2023 PCS, Table 001 | ✅ 通過 |
| 冠狀動脈 PTCA＋支架→ **Dilation（擴張）**（非 Occlusion）<br>*擴張狹窄，不封閉；見 Dilation vs Restriction* | — | — | — | — | — | — | — | — | ICD-10-PCS Table 027<br>2023 PCS, Table 027 | — 原文無 PCS 代碼 |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Dilation vs Restriction 比較\|Dilation vs Restriction 比較]]
- [[Control vs Repair vs Destruction 比較\|Control vs Repair vs Destruction 比較]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
