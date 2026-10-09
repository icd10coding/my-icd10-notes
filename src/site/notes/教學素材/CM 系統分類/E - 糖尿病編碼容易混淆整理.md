---
{"dg-publish":true,"permalink":"//cm/e/","title":"糖尿病 ICD-10-CM 編碼容易混淆整理","tags":["ICD-10-CM","糖尿病","E11","E10","E13","內分泌系統","比較表"],"dg-note-properties":{"title":"糖尿病 ICD-10-CM 編碼容易混淆整理","date":"2026-06-14","tags":["ICD-10-CM","糖尿病","E11","E10","E13","內分泌系統","比較表"],"system":"內分泌、代謝（Chapter E）"}}
---

## 糖尿病 ICD-10-CM 編碼容易混淆整理

---

### 第一關：先選對「類型」

| 代碼 | 糖尿病類型 | 記憶口訣 |
|------|-----------|---------|
| **E10** | Type 1（第一型） | **10** → 1型，胰島素依賴，自體免疫 |
| **E11** | Type 2（第二型） | **11** → 2型，最常見，通常成人 |
| **E08** | 由其他疾病引起（Diabetes due to underlying condition） | 先編原發疾病，再編 E08 |
| **E09** | 藥物或化學物質引起 | 先編藥物（T code），再編 E09 |
| **E13** | 其他特定糖尿病 | 不符合以上分類時用 |

> ⚠️ **最常見錯誤**：文件沒寫型別時，**預設用 E11（Type 2）**，不要亂猜 E10。

---

### 第二關：有沒有用胰島素？≠ Type 1

這是最大的混淆點！

| 情況 | 正確做法 |
|------|---------|
| Type 2 + 有用胰島素 | E11.xxx + **Z79.4**（長期使用胰島素） |
| Type 2 + 有用口服降血糖藥 | E11.xxx + **Z79.84**（長期使用口服降血糖藥） |
| Type 1 | E10.xxx（**不需要**加 Z79.4，Type 1 本來就用胰島素） |

> ⚠️ **陷阱**：看到「用胰島素」就改成 E10 是錯的！Type 2 也會用胰島素，這時要用 E11 + Z79.4。

---

### 第三關：併發症的第 4、5、6 碼

糖尿病代碼結構：`E11` + `.` + **併發症代碼**

#### 常見併發症對照表

| 子代碼 | 意義 | 例子 |
|--------|------|------|
| **.x1x** | 糖尿病腎病變（Diabetic nephropathy） | E11.21 |
| **.x2x** | 糖尿病視網膜病變（Retinopathy） | E11.311–E11.359 |
| **.x4x** | 糖尿病神經病變（Neuropathy） | E11.40–E11.49 |
| **.x5x** | 糖尿病周邊循環障礙（Peripheral angiopathy） | E11.51–E11.52 |
| **.x6x** | 糖尿病其他特定併發症 | E11.610–E11.649 |
| **.x8** | 糖尿病非特定併發症 | E11.8 |
| **.x9** | 無併發症（without complications） | E11.9 |

---

### 第四關：視網膜病變的細分（最複雜）

E11.3xx 視網膜病變需要選到第 6–7 碼，很多人這裡放棄。

| 代碼 | 意義 |
|------|------|
| E11.311 | Nonproliferative DR, mild, right eye |
| E11.312 | Nonproliferative DR, mild, left eye |
| E11.321 | Nonproliferative DR, moderate, right eye |
| E11.331 | Nonproliferative DR, severe, right eye |
| E11.341 | Proliferative DR, right eye |
| E11.351 | Proliferative DR, right eye with traction detachment |

> 記憶技巧：
> - 第 5 碼：**1**=Non-prolif mild / **2**=Non-prolif moderate / **3**=Non-prolif severe / **4**=Proliferative
> - 最後一碼：**1**=右眼 / **2**=左眼 / **3**=雙眼 / **9**=非特定眼

---

### 第五關：低血糖 vs 高血糖 vs 酮酸中毒

| 情況 | 代碼 | 關鍵字 |
|------|------|--------|
| 酮酸中毒（DKA）不昏迷 | E11.10 | with ketoacidosis without coma |
| 酮酸中毒（DKA）昏迷 | E11.11 | with ketoacidosis with coma |
| 高血糖（Hyperglycemia） | E11.65 | with hyperglycemia |
| 低血糖（Hypoglycemia）不昏迷 | E11.649 | with hypoglycemia without coma |
| 低血糖（Hypoglycemia）昏迷 | E11.641 | with hypoglycemia with coma |
| 無併發症 | E11.9 | without complications |

> ⚠️ **陷阱**：DKA 幾乎只出現在 **Type 1（E10）**，但 Type 2 也可能發生（E11.10/E11.11），不要只記 E10。

---

### 常見錯誤整理

| 錯誤做法 | 正確做法 |
|---------|---------|
| 病歷只說「diabetes」→ 編 E10 | 沒有指定型別 → 預設 **E11.9**（Type 2） |
| Type 2 用胰島素 → 改編 E10 | 維持 **E11** + 加 **Z79.4** |
| 有腎病變就選 E11.9 | 要選 **E11.21**（diabetic nephropathy）等具體併發症碼 |
| 視網膜病變只編到 E11.3 | 要繼續細分到 6–7 碼（nonprolif/prolif + 左右眼） |
| 糖尿病足潰瘍只編 E11.52 | 還要另外加 **L97.xxx**（足部潰瘍部位代碼） |

---

### 教學建議

1. **教學順序**：先 E11.9（最簡單）→ 加併發症 → 加胰島素 Z 碼 → 視網膜病變細分
2. **重點強調**：「用胰島素 ≠ Type 1」這個觀念，初學者幾乎必錯
3. **練習題設計**：
   - 給 5 種不同情境的糖尿病病例（含胰島素使用、視網膜、腎病變）
   - 讓學員從 E10/E11/E08/E09 中選正確的起始碼
4. **口訣**：「沒說型別 → E11；有用胰島素且是 Type 2 → E11 + Z79.4；DKA 要看有無昏迷」

---

### 相關筆記
- [[教學素材/ICD-10 課綱總覽\|ICD-10 課綱總覽]]
- [[E - 內分泌系統編碼總覽\|E - 內分泌系統編碼總覽]]（待建立）
- [[Excision vs Resection 比較\|Excision vs Resection 比較]]
