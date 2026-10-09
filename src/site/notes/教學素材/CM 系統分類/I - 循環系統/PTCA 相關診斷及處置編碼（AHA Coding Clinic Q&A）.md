---
{"dg-publish":true,"permalink":"//cm/i/ptca-aha-coding-clinic-q-and-a/","title":"PTCA 相關診斷及處置編碼（AHA Coding Clinic Q&A）","tags":["ICD-10-PCS","PTCA","Dilation","心臟內科","AHA-Coding-Clinic","循環系統"],"dg-note-properties":{"title":"PTCA 相關診斷及處置編碼（AHA Coding Clinic Q&A）","date":"2026-09-03","tags":["ICD-10-PCS","PTCA","Dilation","心臟內科","AHA-Coding-Clinic","循環系統"],"system":"循環系統（Chapter I）"}}
---

## PTCA 相關診斷及處置編碼（AHA Coding Clinic Q&A）

> PTCA = Percutaneous Transluminal Coronary Angioplasty（經皮冠狀動脈血管成形術）
> ICD-10-PCS 手術方式 = **Dilation（擴張，7）**
> 排列：由新至舊

---

## 一、PCS 基礎編碼結構

| 碼位 | 說明 | 常見值 |
|------|------|--------|
| Section | Medical & Surgical | **0** |
| Body System | Heart & Great Vessels | **2** |
| Root Operation | Dilation（擴張） | **7** |
| Body Part | 幾條動脈（sites） | 0=1條 / 1=2條 / 2=3條 / 3=4條以上 |
| Approach | 路徑 | **3** = Percutaneous |
| Device | 支架類型 | Z=無支架 / D=一般支架 / 4=藥物塗層支架 |
| Qualifier | — | **Z**（一般）/ **J**（Intraoperative，2017Q4新增） |

---

## 二、AHA Coding Clinic Q&A（由新至舊）

### 2018 Q3｜冠狀動脈近接放射治療（Brachytherapy）＋ PTCA

| Excludes1 vs Excludes2 | Code first | Code also | Additional code     | Note                                                          | 說明                                                                                 | 資料來源              | 資料來源依據             |
| ---------------------- | ---------- | --------- | ------------------- | ------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ----------------- | ------------------ |
| —                      | —          | —         | **3E073GC**（近接放射治療） | Radioactive ribbon 術後取出 → **不算 Device** → PTCA 編 No Device（Z） | Circumflex artery 近端及中段 PTCA＋60mm 高劑量近接放射治療；近接放射治療另用 Administration section（3E-）編碼 | AHA Coding Clinic | 2018, 心臟內科/依科別, Q3 |
| —                      | —          | —         | —                   | PTCA 代碼：**02703ZZ**（No Device）                                | Dilation of coronary artery, one artery, percutaneous approach                     | AHA Coding Clinic | 2018, 心臟內科/依科別, Q3 |

---

### 2017 Q4｜PTCA ＋ Impella® 術中使用（新 Qualifier J）

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | **02HA3RJ**（Impella 置入，Intraoperative） | **5A0221D**（輔助心輸出量） | 自 **2017/10/01** 起新增 Qualifier **J（Intraoperative）**，術中短暫使用之心輔裝置；有 Qualifier J 後**不需另編 Removal** | PTCA 術中使用 Impella® 輔助循環，手術結束時移除 | AHA Coding Clinic | 2017, 心臟內科/依科別, Q4 |
| — | — | — | — | PTCA 代碼：**027_3_Z**（視病灶動脈數） | Dilation of coronary artery（依條數選 Body Part 0/1/2/3） | AHA Coding Clinic | 2017, 心臟內科/依科別, Q4 |
| — | — | — | — | Impella 置入：**02HA3RJ** | Insertion of short-term external heart assist system into heart, intraoperative, percutaneous approach | AHA Coding Clinic | 2017, 心臟內科/依科別, Q4 |
| — | — | — | — | 輔助循環：**5A0221D** | Assistance with cardiac output using impeller pump, continuous | AHA Coding Clinic | 2017, 心臟內科/依科別, Q4 |

---

### 2017 Q1｜PTCA ＋ Impella® 術中使用（舊規則，已更新）

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | ⚠️ **已由 2017 Q4 新規則取代**；術中放入術後即移除 → 舊規則只編 Assistance，不編 Insertion | 依 Guideline B6.1a：裝置必須手術結束後仍留體內才算 Device | AHA Coding Clinic | 2017, 心臟內科/依科別, Q1 |
| — | — | — | — | 舊做法：**5A0221D**（Assistance only） | 現行做法請依 2017 Q4 新 Qualifier J 編碼 | AHA Coding Clinic | 2017, 心臟內科/依科別, Q1 |

---

### 2015 Q3｜PTCA 成功但支架置放失敗

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | 支架未成功置入 → Device = **Z（No Device）**；但 PTCA 球囊擴張已完成 → **仍須編碼** | RCA 行 PTCA，球囊擴張完成，但支架置放未成功 | AHA Coding Clinic | 2015, 心臟內科/依科別, Q3 |
| — | — | — | — | 代碼：**02703ZZ** | Dilation of coronary artery, one artery, percutaneous approach, no device | AHA Coding Clinic | 2015, 心臟內科/依科別, Q3 |

---

### 2015 Q2｜同一條動脈兩處病灶用不同支架

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | **02703DZ**（BMS，one site） | — | **Device 類型不同 → 不可合併 → 拆開編兩個代碼** | LAD 近端 DES＋LAD 遠端 BMS；同一條動脈，但 Device 不同，需各編一碼 | AHA Coding Clinic | 2015, 心臟內科/依科別, Q2 |
| — | — | — | — | DES 代碼：**027034Z**；BMS 代碼：**02703DZ** | 各計 one artery（Body Part 0） | AHA Coding Clinic | 2015, 心臟內科/依科別, Q2 |

---

### 2015 Q2｜三條不同動脈各放一個 DES

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | Body Part 計**動脈條數（sites）**，非支架數量 | D1、LCX、RCA 各一病灶各一 DES = 3 sites | AHA Coding Clinic | 2015, 心臟內科/依科別, Q2 |
| — | — | — | — | 代碼：**027234Z** | Dilation of coronary artery, three sites, drug-eluting intraluminal device, percutaneous | AHA Coding Clinic | 2015, 心臟內科/依科別, Q2 |

---

### 2015 Q2｜兩條動脈共 4 個 DES

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | **支架數量不影響代碼**；計的是動脈條數（sites） | RCA 放 2 個 DES＋LAD 放 2 個 DES = 2 sites（2 條動脈） | AHA Coding Clinic | 2015, 心臟內科/依科別, Q2 |
| — | — | — | — | 代碼：**027134Z** | Dilation of coronary artery, two sites, drug-eluting intraluminal device, percutaneous | AHA Coding Clinic | 2015, 心臟內科/依科別, Q2 |

---

## 三、常見錯誤整理

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | ❌ 支架沒放成功 → 不編 PTCA | ✅ 球囊擴張完成就要編，Device = Z | AHA Coding Clinic | 2015, Q3 |
| — | — | — | — | ❌ 3 個支架全在同一條動脈 → 編 three sites | ✅ 同一條動脈不論幾個支架，算 one site | AHA Coding Clinic | 2015, Q2 |
| — | — | — | — | ❌ Device 類型不同合併成一個代碼 | ✅ Device 不同 → 拆開編兩個代碼 | AHA Coding Clinic | 2015, Q2 |
| — | — | — | — | ❌ 術中用 Impella 就編 Insertion（舊規則） | ✅ 2017 Q4 後：用 Qualifier J，不需另編 Removal | AHA Coding Clinic | 2017, Q4 |
| — | — | — | — | ❌ Brachytherapy 放 Device 欄位 | ✅ Radioactive ribbon 取出 → 不算 Device；另編 3E073GC | AHA Coding Clinic | 2018, Q3 |

---

## 四、診斷碼（ICD-10-CM）搭配

| Excludes1 vs Excludes2 | Code first | Code also | Additional code | Note | 說明 | 資料來源 | 資料來源依據 |
|------------------------|-----------|----------|----------------|------|------|---------|------------|
| — | — | — | — | STEMI：**I21.0–I21.3**（依部位） | ST 上升型心肌梗塞 | ICD-10-CM Tabular | 2023 CM Tabular, I21 |
| — | — | — | — | NSTEMI：**I21.4** | Non-ST elevation MI | ICD-10-CM Tabular | 2023 CM Tabular, I21.4 |
| — | — | — | — | 不穩定型狹心症：**I20.0** | Unstable angina | ICD-10-CM Tabular | 2023 CM Tabular, I20.0 |
| — | — | — | — | 穩定型缺血性心臟病：**I25.110–I25.118** | 慢性缺血性心臟病（依有無狹心症） | ICD-10-CM Tabular | 2023 CM Tabular, I25 |

---

## 相關筆記
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
- [[教學素材/CM 系統分類/E - 糖尿病編碼容易混淆整理\|E - 糖尿病編碼容易混淆整理]]
