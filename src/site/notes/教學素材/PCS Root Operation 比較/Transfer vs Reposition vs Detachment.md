---
{"dg-publish":true,"permalink":"//pcs-root-operation/transfer-vs-reposition-vs-detachment/","title":"Transfer vs Reposition vs Detachment 比較","tags":["ICD-10-PCS","Root-Operation","比較","Transfer","Reposition","Detachment"],"dg-note-properties":{"title":"Transfer vs Reposition vs Detachment 比較","date":"2026-09-03","tags":["ICD-10-PCS","Root-Operation","比較","Transfer","Reposition","Detachment"],"system":"PCS 根本操作"}}
---

## Transfer（轉移）vs Reposition（復位）vs Detachment（截除）比較

> PCS Root Operation X（Transfer）vs S（Reposition）vs 6（Detachment）
> 三者皆涉及「移動組織或肢體」，常見於整形外科、骨科、燒傷、截肢手術。

---

## 核心定義

| 項目 | Transfer（X）轉移 | Reposition（S）復位 | Detachment（6）截除 |
|------|----------------|-------------------|-------------------|
| PCS 代碼 | X | S | 6 |
| 血液供應 | ✅ 保留（帶蒂） | ✅ 保留 | ❌ 截斷分離 |
| 組織去向 | 移至新位置執行新功能 | 移回原位 | 永久離開身體 |
| 適用部位 | 皮瓣、肌瓣、肌腱 | 骨折、脫位、鼻中隔 | **僅限四肢** |
| 類比 | 帶家具搬去新家 | 回到原位 | 斷尾（永久分離） |

---

## 標準編碼說明表

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Transfer（轉移）= 組織移至新位置，**血管連結保留（帶蒂）** | 不離開身體；在新位置執行功能；常見於皮瓣重建、肌腱轉移 | ICD-10-PCS Definitions | 2023 PCS, Root Operation X |
| — | — | — | — | Reposition（復位）= 將 Body Part 移回正常或適當位置 | 骨折、脫位復位；移回後仍可活動 | ICD-10-PCS Definitions | 2023 PCS, Root Operation S |
| — | — | — | — | Detachment（截除）= 截斷上肢或下肢全部或部分，**僅限四肢** | 非四肢截除（乳房、陰莖等）= Resection（T） | ICD-10-PCS Definitions | 2023 PCS, Root Operation 6 |
| — | — | — | — | Transfer Qualifier = **組織層次**（非目的地） | 0=皮膚；1=皮下組織；2=皮膚與皮下組織；肌皮瓣另有專屬值（5 背闊肌肌皮瓣、6 TRAM、7 DIEP…，依身體部位而異） | ICD-10-PCS Table | 2023 PCS, Qualifier column |
| — | — | — | — | **帶蒂皮瓣 = Transfer；游離皮瓣 = Replacement 或 Supplement** | 帶蒂（血管連結保留）→ Transfer；游離（顯微吻合）→ Replacement/Supplement | ICD-10-PCS Guidelines | 2023 PCS Guidelines |
| — | — | — | — | 截肢 Detachment Qualifier = 截除**層級**（0=Complete/1=High/2=Mid/3=Low） | 代表截肢高度，非終點 | ICD-10-PCS Table | 2023 PCS, Table 0X6/0Y6 |
| — | — | — | — | **截指/截趾 = Detachment，非 Resection** | 手指/腳趾屬四肢 → Detachment；乳房 = Resection | ICD-10-PCS Table 0X6/0Y6 | 2023 PCS, Table 0X6 |

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
| 唇裂修復（Millard 旋轉推進皮瓣）→ **Transfer（轉移）**（0KX10Z2）<br>*帶蒂臉部肌肉皮瓣旋轉；第7碼 2＝皮膚與皮下組織* | `0KX10Z2` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `K`<br>肌肉<br><sub>Muscles</sub> | `X`<br>轉移<br><sub>Transfer</sub> | `1`<br>顏面肌肉<br><sub>Facial Muscle</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `2`<br>皮膚與皮下組織<br><sub>Skin and Subcutaneous Tissue</sub> | AHA Coding Clinic<br>2015, 耳鼻喉頭頸部, Q3 p.33 | ℹ️ 第7碼 2＝Skin and Subcutaneous Tissue（官方標籤）；原敘述「含筋膜」不符 |
| 後咽壁皮瓣至軟腭→ **Transfer（轉移）**（0KX40Z2）<br>*帶蒂咽部肌肉轉移至軟腭執行新功能* | `0KX40Z2` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `K`<br>肌肉<br><sub>Muscles</sub> | `X`<br>轉移<br><sub>Transfer</sub> | `4`<br>舌、顎、咽肌<br><sub>Tongue, Palate, Pharynx Muscle</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `2`<br>皮膚與皮下組織<br><sub>Skin and Subcutaneous Tissue</sub> | AHA Coding Clinic<br>2015, 耳鼻喉頭頸部, Q2 p.26 | ✅ 通過 |
| 腹直肌皮瓣乳房重建（TRAM flap）→ **Transfer（轉移）**（0KXL0Z6）<br>*帶蒂腹直肌轉至胸部；第7碼 6＝TRAM 皮瓣* | `0KXL0Z6` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `K`<br>肌肉<br><sub>Muscles</sub> | `X`<br>轉移<br><sub>Transfer</sub> | `L`<br>左腹部肌肉<br><sub>Abdomen Muscle, Left</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `6`<br>TRAM 皮瓣（橫向腹直肌肌皮瓣）<br><sub>Transverse Rectus Abdominis Myocutaneous Flap</sub> | ICD-10-PCS Table 0KX<br>2023 PCS, Table 0KX | ℹ️ B3.17：多層皮瓣以最深層（肌肉）定身體部位；第7碼 6＝TRAM 皮瓣（官方標籤，非泛稱「含肌肉」） |
| 游離皮瓣（Free flap，顯微吻合）→ **Replacement（置換）** 或 **Supplement（強化）**<br>*完全切離後顯微吻合重接血管 → 非 Transfer* | — | — | — | — | — | — | — | — | ICD-10-PCS Guidelines<br>2023 PCS Guidelines | — 原文無 PCS 代碼 |
| 皮膚移植（Skin graft，無血管連結）→ **Replacement（置換）**<br>*切下後縫合，無直接血供 → Replacement* | — | — | — | — | — | — | — | — | ICD-10-PCS Table 0HR<br>2023 PCS, Table 0HR | — 原文無 PCS 代碼 |
| 股骨骨折復位固定→ **Reposition（復位）**（0QS604Z）<br>*Device 4（內固定）；移回原位後仍可活動* | `0QS604Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `Q`<br>下部骨骼<br><sub>Lower Bones</sub> | `S`<br>復位<br><sub>Reposition</sub> | `6`<br>右股骨上段<br><sub>Upper Femur, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `4`<br>內固定裝置<br><sub>Internal Fixation Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Table 0QS<br>2023 PCS, Table 0QS | ✅ 通過 |
| Le Fort I 截骨術→ **Reposition（復位）**（0NSR04Z）<br>*上頜骨截骨重新定位* | `0NSR04Z` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `N`<br>頭與顏面骨<br><sub>Head and Facial Bones</sub> | `S`<br>復位<br><sub>Reposition</sub> | `R`<br>上頜骨<br><sub>Maxilla</sub> | `0`<br>開放<br><sub>Open</sub> | `4`<br>內固定裝置<br><sub>Internal Fixation Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | AHA Coding Clinic<br>2014, 耳鼻喉頭頸部, Q3 p.23 | ✅ 通過 |
| 睪丸固定術（Orchiopexy）→ **Reposition（復位）**（0VS90ZZ，右側）<br>*隱睪移至正常位置（適當位置，非原位）* | `0VS90ZZ` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `V`<br>男性生殖<br><sub>Male Reproductive System</sub> | `S`<br>復位<br><sub>Reposition</sub> | `9`<br>右睪丸<br><sub>Testis, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `Z`<br>無限定詞<br><sub>No Qualifier</sub> | ICD-10-PCS Index／Table<br>2023 PCS, Index「Orchiopexy」→ Reposition 0VS；Table 0VS | ⚠️ 已修正：0VS 表無第4碼 0；睪丸右＝9、左＝B、雙側＝C |
| 小腿截肢（BKA）→ **Detachment（截除）**（0Y6H0Z1）<br>*四肢截除；Qualifier 1（High）* | `0Y6H0Z1` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `Y`<br>解剖區域－下肢<br><sub>Anatomical Regions, Lower Extremities</sub> | `6`<br>截斷（肢體）<br><sub>Detachment</sub> | `H`<br>右小腿<br><sub>Lower Leg, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `1`<br>高位<br><sub>High</sub> | ICD-10-PCS Table 0Y6<br>2023 PCS, Table 0Y6 | ℹ️ B3.19：小腿截肢第7碼 1＝High（脛腓骨幹近端） |
| 大腿截肢（AKA）→ **Detachment（截除）**（0Y6C0Z3）<br>*大腿截肢（右大腿 C）；第7碼 3＝Low（股骨幹遠端）* | `0Y6C0Z3` | `0`<br>內外科<br><sub>Medical and Surgical</sub> | `Y`<br>解剖區域－下肢<br><sub>Anatomical Regions, Lower Extremities</sub> | `6`<br>截斷（肢體）<br><sub>Detachment</sub> | `C`<br>右大腿<br><sub>Upper Leg, Right</sub> | `0`<br>開放<br><sub>Open</sub> | `Z`<br>無裝置<br><sub>No Device</sub> | `3`<br>低位<br><sub>Low</sub> | ICD-10-PCS Table 0Y6<br>2023 PCS, Table 0Y6 | ⚠️ 已修正：0Y6 表無第4碼 B；右大腿＝C、左＝D |
| 乳房切除術→ **Resection（切除全部）**，非 Detachment<br>*乳房非四肢 → Resection* | — | — | — | — | — | — | — | — | ICD-10-PCS Table 0HT<br>2023 PCS, Table 0HT | — 原文無 PCS 代碼 |

> 核對方式：逐碼比對 `ICD 10/工具書/★pcs_2023.md` 的 Table 列（第 4–7 碼須同列）；Guideline 引用 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。✅＝2023 Table 驗證通過；⚠️＝原筆記代碼或根手術有誤，已修正；ℹ️＝碼有效但需注意；❔＝2023 版工具書查無，需以較新版本核對。

---

## 相關筆記
- [[Repair vs Replacement vs Supplement 比較\|Repair vs Replacement vs Supplement 比較]]
- [[Fusion vs Reposition 比較\|Fusion vs Reposition 比較]]
- [[Extraction vs Excision 比較\|Extraction vs Excision 比較]]
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
