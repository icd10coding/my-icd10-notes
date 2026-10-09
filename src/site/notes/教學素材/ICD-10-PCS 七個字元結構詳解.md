---
{"dg-publish":true,"permalink":"//icd-10-pcs/","title":"ICD-10-PCS 七個字元結構詳解","tags":["ICD-10-PCS","編碼基礎","七碼結構"],"dg-note-properties":{"title":"ICD-10-PCS 七個字元結構詳解","date":"2026-10-09","tags":["ICD-10-PCS","編碼基礎","七碼結構"],"system":"PCS 結構","verified":"2023 PCS Tables／Definitions（★pcs_2023.md）＋2025 PCS Guidelines"}}
---

## ICD-10-PCS 輸出格式：7 個字元詳解

> 本篇內容已逐項對照官方工具書：`ICD 10/工具書/★pcs_2023.md`（Tables／Definitions／Index）與 `ICD 10/★ Coding Guidelines/2025/pcs_guidelines_2025.md`。

---

## 一、基本規則（Guidelines A1–A9）

| 規則 | 內容 |
|------|------|
| A1 | PCS 碼由 **7 個字元**組成，每個字元是一條「分類軸」；同一範圍內同一位置代表同類資訊（例：Section 0–4、7–9 的第 5 碼是 Approach） |
| A2 | 每個字元可用 34 種值：數字 **0–9** 與英文字母，**不含 I、O**（避免與 1、0 混淆）；無小數點 |
| A4 | 一個值的意義取決於**所在位置＋前面的碼**。例：第 4 碼 `0` 在中樞神經＝腦（Brain），在周邊神經＝頸神經叢（Cervical Plexus） |
| A5 | 同一個第 6 碼值因 Root Operation 不同而意義不同。例：下部關節的 Insertion 中 `3`＝Infusion Device，Replacement 中 `3`＝Ceramic Synthetic Substitute |
| A6–A7 | Index 只用來找 Table；可不經 Index 直接查 Table；一律以 Table 選出有效碼 |
| A8 | **七碼必須全部指定**才是有效碼；資料不足應詢問醫師 |
| A9 | 第 4–7 碼必須取自 Table **同一列**的選項才是有效碼（例：`0JHT3VZ` 有效，`0JHW3VZ` 無效） |
| A11 | 醫師不必使用 PCS 用語；由編碼員把病歷描述對應到 PCS 定義（例：partial resection → Excision） |

> 補充（Handbook）：沒有可指定的值時以 `Z` 填入，例如第 6 碼 `Z`＝No Device、第 7 碼 `Z`＝No Qualifier；所有位置都不可留白。

---

## 二、七個位置總覽（Section 0 內外科）

| 位置 | 名稱 | 說明 | 範例（`0FT44ZZ`） |
|:--:|------|------|------|
| ① | Section 段落 | 手術大類 | `0` Medical and Surgical |
| ② | Body System 身體系統 | 解剖系統 | `F` Hepatobiliary System and Pancreas |
| ③ | Root Operation 根手術 | 手術**目的** | `T` Resection |
| ④ | Body Part 身體部位 | 目標部位 | `4` Gallbladder |
| ⑤ | Approach 途徑 | 到達部位的方式 | `4` Percutaneous Endoscopic |
| ⑥ | Device 裝置 | 手術後留在體內的裝置 | `Z` No Device |
| ⑦ | Qualifier 限定詞 | 額外屬性 | `Z` No Qualifier |

口訣：**段 → 系 → 術 → 部 → 徑 → 裝 → 限**

---

## 三、第 1 碼 Section（官方 17 個）

| 碼 | Section | 中文 |
|:--:|---------|------|
| 0 | Medical and Surgical | 內外科 |
| 1 | Obstetrics | 產科 |
| 2 | Placement | 放置 |
| 3 | Administration | 給予 |
| 4 | Measurement and Monitoring | 測量與監測 |
| 5 | Extracorporeal or Systemic Assistance and Performance | 體外／全身輔助與執行 |
| 6 | Extracorporeal or Systemic Therapies | 體外／全身治療 |
| 7 | Osteopathic | 整骨 |
| 8 | Other Procedures | 其他處置 |
| 9 | Chiropractic | 脊骨神經 |
| B | Imaging | 影像 |
| C | Nuclear Medicine | 核子醫學 |
| D | Radiation Therapy | 放射治療 |
| F | Physical Rehabilitation and Diagnostic Audiology | 復健與診斷性聽力 |
| G | Mental Health | 心理健康 |
| H | Substance Abuse Treatment | 物質濫用治療 |
| X | New Technology | 新科技 |

---

## 四、第 2 碼 Body System（Section 0，官方 31 個）

| 碼 | Body System | 中文 | 碼 | Body System | 中文 |
|:--:|------|------|:--:|------|------|
| 0 | Central Nervous System and Cranial Nerves | 中樞神經與顱神經 | J | Subcutaneous Tissue and Fascia | 皮下組織與筋膜 |
| 1 | Peripheral Nervous System | 周邊神經 | K | Muscles | 肌肉 |
| 2 | Heart and Great Vessels | 心臟與大血管 | L | Tendons | 肌腱 |
| 3 | Upper Arteries | 上動脈 | M | Bursae and Ligaments | 滑囊與韌帶 |
| 4 | Lower Arteries | 下動脈 | N | Head and Facial Bones | 頭與顏面骨 |
| 5 | Upper Veins | 上靜脈 | P | Upper Bones | 上部骨骼 |
| 6 | Lower Veins | 下靜脈 | Q | Lower Bones | 下部骨骼 |
| 7 | Lymphatic and Hemic Systems | 淋巴與造血 | R | Upper Joints | 上部關節 |
| 8 | Eye | 眼 | S | Lower Joints | 下部關節 |
| 9 | Ear, Nose, Sinus | 耳鼻竇 | T | Urinary System | 泌尿系統 |
| B | Respiratory System | 呼吸系統 | U | Female Reproductive System | 女性生殖 |
| C | Mouth and Throat | 口與喉 | V | Male Reproductive System | 男性生殖 |
| D | Gastrointestinal System | 消化系統 | W | Anatomical Regions, General | 解剖區域－一般 |
| F | Hepatobiliary System and Pancreas | 肝膽胰 | X | Anatomical Regions, Upper Extremities | 解剖區域－上肢 |
| G | Endocrine System | 內分泌 | Y | Anatomical Regions, Lower Extremities | 解剖區域－下肢 |
| H | Skin and Breast | 皮膚與乳房 | | | |

> 「Upper／Lower」＝橫膈以上／以下（B2.1b）。

---

## 五、第 3 碼 Root Operation（Section 0，官方 31 個）

字母皆取自 2023 Tables 的 Operation 欄；定義依 Definitions／Table 標題改寫成中文。

| 組別 | 碼 | Root Operation | 中文與定義（重點） |
|------|:--:|------|------|
| 取出／切除 | B | Excision | 切除**部分**，不置換 |
| | T | Resection | 切除**全部**，不置換 |
| | 6 | Detachment | 截斷上／下肢全部或一部分 |
| | 5 | Destruction | 以能量或破壞劑**徹底消滅**全部或一部分 |
| | D | Extraction | 以力量拉出或剝除全部或一部分 |
| 取出液體／固體 | 9 | Drainage | 引出液體／氣體 |
| | C | Extirpation | 取出或切出固體物 |
| | F | Fragmentation | 將固體物在原處打碎 |
| 切開／分離 | 8 | Division | 切入但不引流，用以分離或切斷 |
| | N | Release | 鬆開被異常束縛的部位（切或用力） |
| 改變管腔 | 1 | Bypass | 改變管狀構造內容物的通路 |
| | 7 | Dilation | 擴大開口或管腔 |
| | L | Occlusion | **完全**封閉開口或管腔 |
| | V | Restriction | **部分**封閉開口或管腔 |
| 放入／取代 | H | Insertion | 放入**不取代**部位、作監測／輔助／執行功能的非生物裝置 |
| | R | Replacement | 以生物或合成材料**取代**全部或一部分 |
| | U | Supplement | 加入材料**補強**功能，原組織保留 |
| | 2 | Change | 不切穿皮膚／黏膜，換出同類裝置 |
| | P | Removal | 取出裝置 |
| | W | Revision | 修正故障或位移的裝置 |
| 移動／重組 | M | Reattachment | 把離斷的部位接回原位 |
| | S | Reposition | 移到正常或適當位置 |
| | X | Transfer | 移到他處接替功能，**血管神經連結保留** |
| | Y | Transplantation | 置入取自他人／他種動物的活體部位 |
| 改變構造 | 0 | Alteration | 改變外形而不影響功能（美容為主） |
| | 4 | Creation | 以材料形成新部位 |
| | G | Fusion | 使關節固定不動 |
| 檢查／其他 | J | Inspection | 目視或徒手探查 |
| | K | Map | 定位電傳導路徑或功能區 |
| | Q | Repair | 盡可能還原正常結構與功能（其他定義都不適用時） |
| | 3 | Control | 停止或試圖停止術後或其他急性出血 |

> 其他 Section 的第 3 碼意義不同：Obstetrics 的 `A` Abortion、`D` Extraction、`E` Delivery；Placement 的 `4` Packing 等。

---

## 六、第 4 碼 Body Part
- 意義依第 2 碼決定（A4）。例：`0` 在 Section 0／Body System 0 為 Brain，在 0／1 為 Cervical Plexus。
- 部位沒有獨立碼值時，編至**整個部位**（B4.1a）；沒有該分支碼值時，編到**最近端有碼值的分支**（B4.2）。
- 雙側碼值只有部分部位才有（如 Fallopian Tube, Bilateral），沒有時左右各編一碼（B4.3）。

## 七、第 5 碼 Approach（官方 7 種）

| 碼 | Approach | 定義（摘要） |
|:--:|------|------|
| 0 | Open | 切開皮膚／黏膜與必要的層次以暴露處置部位 |
| 3 | Percutaneous | 以穿刺或小切口將器械經皮送達處置部位 |
| 4 | Percutaneous Endoscopic | 經皮進入，並能**看見**處置部位 |
| 7 | Via Natural or Artificial Opening | 經自然或人工的外部開口送入器械 |
| 8 | Via Natural or Artificial Opening Endoscopic | 同上，並能看見處置部位 |
| F | Via Natural or Artificial Opening With Percutaneous Endoscopic Assistance | 自然開口進入＋經皮內視鏡輔助 |
| X | External | 直接作用於皮膚／黏膜，或經由皮膚施加外力間接進行 |

補充規則：
- 「開放＋經皮內視鏡輔助」編 **Open**（B5.2a）；內視鏡手術為取出標本而延伸切口，仍編 **Percutaneous Endoscopic**（B5.2b）。
- 口腔內肉眼可見的構造（如扁桃腺切除）編 **External**（B5.3a）；閉合性骨折復位亦為 External（B5.3b）。
- 經為此手術放置的裝置進行的經皮處置，編 **Percutaneous**（B5.4）。

## 八、第 6 碼 Device
- **只有手術結束後仍留在體內的裝置才編**；沒有則 `Z`＝No Device（B6.1a）。
- 縫線、結紮線、放射標記、術後暫時性引流管視為手術的一部分，不算裝置（B6.1b）。
- 官方 Table 中的實例：
  - `0BH`（氣管 Insertion）：`D` Intraluminal Device、`E` Intraluminal Device, Endotracheal Airway、`Y` Other Device
  - `0FU`（膽管 Supplement）：`7` Autologous Tissue Substitute、`J` Synthetic Substitute、`K` Nonautologous Tissue Substitute
  - `027`（冠狀動脈 Dilation）：`4` 藥物塗層支架、`D` Intraluminal Device、`Z` No Device

## 九、第 7 碼 Qualifier
同一個位置在不同 Table 代表不同屬性，以下皆為 Table 實例：

| 類型 | 例 |
|------|------|
| 診斷性 | `X` Diagnostic（如 `0WB` Excision、`08D` Extraction） |
| 繞道**終點** | `001` 腦室繞道：`6` Peritoneal Cavity；`021` 冠狀動脈繞道：`3` Coronary Artery |
| 截肢層級 | `0Y6` 小腿／大腿：`1` High、`2` Mid、`3` Low |
| 皮瓣類型 | `0KX` Transfer：`2` Skin and Subcutaneous Tissue、`6` TRAM 皮瓣 |
| 牙數 | `0CD` 拔牙：`0` Single、`1` Multiple、`2` All |
| 產科 | `10D` 產鉗等：`3` Low Forceps … `6` Vacuum；`10A` 人工流產：`6` Vacuum |

---

## 十、逐碼拆解實例（均經 2023 Table 驗證）

### 例 1　`0FT44ZZ`　腹腔鏡膽囊切除術
| ① | ② | ③ | ④ | ⑤ | ⑥ | ⑦ |
|---|---|---|---|---|---|---|
| `0` Medical and Surgical | `F` Hepatobiliary System and Pancreas | `T` Resection | `4` Gallbladder | `4` Percutaneous Endoscopic | `Z` No Device | `Z` No Qualifier |

### 例 2　`02703DZ`　經皮冠狀動脈擴張＋一般支架（一條）
| ① | ② | ③ | ④ | ⑤ | ⑥ | ⑦ |
|---|---|---|---|---|---|---|
| `0` Medical and Surgical | `2` Heart and Great Vessels | `7` Dilation | `0` Coronary Artery, One Artery | `3` Percutaneous | `D` Intraluminal Device | `Z` No Qualifier |

### 例 3　`0BH17EZ`　經口氣管內插管
| ① | ② | ③ | ④ | ⑤ | ⑥ | ⑦ |
|---|---|---|---|---|---|---|
| `0` Medical and Surgical | `B` Respiratory System | `H` Insertion | `1` Trachea | `7` Via Natural or Artificial Opening | `E` Intraluminal Device, Endotracheal Airway | `Z` No Qualifier |

### 例 4　`5A1955Z`　呼吸器通氣 >96 小時（**非 Section 0，欄位不同**）
| 位置 | ① | ② | ③ | ④ | ⑤ | ⑥ | ⑦ |
|---|---|---|---|---|---|---|---|
| 欄位名稱 | Section | Body System | Operation | Body System | **Duration** | **Function** | Qualifier |
| 值 | `5` Extracorporeal or Systemic Assistance and Performance | `A` Physiological Systems | `1` Performance | `9` Respiratory | `5` Greater than 96 Consecutive Hours | `5` Ventilation | `Z` No Qualifier |

> 所以第 4–7 碼的名稱依 Section／Table 而變（A1），務必看該 Table 的欄位標題。

---

## 十一、實務查表流程
1. 由 Index（或直接）找到 **Table（前 3 碼＝Section＋Body System＋Root Operation）**。
2. 在 Table 中找**同一列**：該列列出可選的 Body Part、Approach、Device、Qualifier。
3. 逐欄選值，確認 4–7 碼在同一列（A9）。
4. 七碼缺一不可（A8）。

## 相關連結
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
- Root Operation 比較系列：[[Excision vs Resection 比較\|Excision vs Resection 比較]]、[[Insertion vs Replacement vs Supplement 比較\|Insertion vs Replacement vs Supplement 比較]]、[[Transfer vs Reposition vs Detachment 比較\|Transfer vs Reposition vs Detachment 比較]]
