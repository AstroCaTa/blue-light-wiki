---
type: source
tags:
  - 光學物理
  - 抗反射鍍膜
  - 薄膜干涉
  - 折射率
evidence_level: physics-textbook
sources:
  - "raw/05_wikipedia_ar_coating.md"
source_urls:
  - "https://en.wikipedia.org/wiki/Anti-reflective_coating"
updated: 2026-11-17
---

# 05_Wikipedia_抗反射鍍膜光學原理

## 來源基本資訊
- **原始檔案**：`raw/05_wikipedia_ar_coating.md`
- **原始網址**：https://en.wikipedia.org/wiki/Anti-reflective_coating
- **發布機構**：Wikipedia — Anti-reflective coating
- **資料類型**：光學物理與工程百科摘要

---

## 核心光學原理與關鍵數據

### 1. 減反射膜（Anti-Reflective Coating, AR）的功用
- 一種鍍於鏡片與光學元件表面的光學薄膜，目的在於**減少表面反射（reduce surface reflection）**並提高透光率（light transmission）。
- 以未鍍膜的一般冕牌玻璃（Crown Glass，$n_S \approx 1.5$）置於空氣（$n_0 \approx 1.0$）中為例，依菲涅耳方程式（Fresnel equations），單一表面反射率 $R \approx 4\%$（前後兩面合計光損失約 **7.7%**）。
- **高折射率鏡片（High-index eyeglass lenses）**未鍍膜時的表面反射率更高，因此特別需要 AR 鍍膜來減少眩光與反射損失。
- 參見：[[減反射膜_AR鍍膜]]。

### 2. 物理機制：薄膜干涉（Thin-Film Interference）
- **折射率匹配（Rayleigh's film）**：當薄膜折射率符合 $n_1 = \sqrt{n_0 n_S}$（針對 $n_S = 1.5$ 理想值約 $n_1 \approx 1.225$）時，原本單一空氣-玻璃介面的反射會被拆分為兩道較弱的反射，使反射損失減半。
- **四分之一波長干涉鍍膜（Quarter-wave interference coating）**：將鍍膜光學厚度精確控制為設計波長的四分之一（$\lambda/4 = \lambda_0 / (4n_1)$）。從第二介面反射的光比第一介面反射的光多走半個波長的光程，產生**破壞性干涉（Destructive Interference）**，進而抵銷反射光。
- **單層膜材料**：氟化鎂（Magnesium Fluoride, $\text{MgF}_2$，$n = 1.38$）因耐用性高而被廣泛使用，可將冕牌玻璃單面反射率從約 4% 降至約 **1%**。
- **多層寬頻鍍膜（Multi-layer broadband coatings）**：交替堆疊低折射率（如二氧化矽 Silica）與高折射率材料，可在整個可見光譜（**400–700 nm**）達成低於 **0.5%** 的反射率，或在特定目標波長低於 **0.1%**。
- 參見：[[薄膜干涉與四分之一波長鍍膜原理]]。

### 3. 為何鍍膜鏡片會出現帶色反光？
- 由於薄膜干涉效果高度依賴**波長（wavelength）**與**入射角（incident angle）**，實際鍍膜在不同顏色波段的反射抑制表現略有差異。
- 常見的眼鏡 AR 鍍膜常呈現微弱的**偏藍、偏綠或偏粉紅（bluish, greenish, or pinkish）**反光，這正代表該波段相較其他波段有略高的殘餘反射率。
- **名詞區辨**：矯正視力用的 AR 鍍膜鏡片不應與太陽眼鏡常用的**偏光鏡片（Polarized Lenses）**混淆（後者用於吸收水面、雪地或路面反射的偏振眩光）。
- 原文重點："Common AR coatings on eyeglasses often show a faint bluish, greenish, or pinkish reflection—indicating the wavelengths slightly more reflected than others."

---

## 關聯頁面
- 概念：[[薄膜干涉與四分之一波長鍍膜原理]]
- 實體與技術：[[減反射膜_AR鍍膜]]、[[抗藍光濾鏡眼鏡]]
