# Wiki 操作日誌（Log）

本檔案為按時間順序附加的唯讀操作紀錄（`ingest`、`query`、`lint`）。

## [2026-11-17] ingest | 01_cochrane_blue_light_review.md
- 來源：`raw/01_cochrane_blue_light_review.md`（https://www.cochrane.org/about-us/news/blue-light-filtering-spectacles-probably-make-no-difference-eye-strain-eye-health-or-sleep）
- 新建：`[[01_Cochrane_抗藍光眼鏡系統性回顧]]`、`[[數位視覺疲勞與用眼行為]]`、`[[藍光暴露、晝夜節律與視網膜風險]]`、`[[抗藍光濾鏡眼鏡]]`
- 摘要：納入 17 項 RCT（5–156 人、追蹤 <1 天至 5 週），指出抗藍光眼鏡對短期視覺疲勞可能無差異、對睡眠影響尚無定論，且螢幕藍光僅為自然日光約 1/1000。

## [2026-11-17] ingest | 02_aao_computer_glasses.md
- 來源：`raw/02_aao_computer_glasses.md`（https://www.aao.org/eye-health/tips-prevention/are-computer-glasses-worth-it）
- 新建：`[[02_AAO_電腦眼鏡與藍光立場聲明]]`、`[[裝置夜間模式與色溫調整]]`
- 更新：`[[數位視覺疲勞與用眼行為]]`、`[[藍光暴露、晝夜節律與視網膜風險]]`、`[[抗藍光濾鏡眼鏡]]`
- 摘要：AAO 不建議配戴電腦／抗藍光眼鏡；數位視覺疲勞主因為眨眼減少；螢幕未測得 UVA/UVB；建議 20-20-20 原則與睡前 2–3 小時避螢幕或開夜間模式。

## [2026-11-17] ingest | 03_mohw_blue_light_vision.md
- 來源：`raw/03_mohw_blue_light_vision.md`（https://www.mohw.gov.tw/cp-3199-36773-1.html）
- 新建：`[[03_衛福部國健署_3C藍光與兒童視力]]`、`[[爭議_藍光是否造成視網膜傷害與視覺疲勞]]`、`[[爭議_抗藍光眼鏡能否改善睡眠品質與晝夜節律]]`、`[[各機構對抗藍光與3C護眼立場比較]]`
- 更新：`[[藍光暴露、晝夜節律與視網膜風險]]`、`[[數位視覺疲勞與用眼行為]]`、`[[抗藍光濾鏡眼鏡]]`、`[[裝置夜間模式與色溫調整]]`
- 摘要：補充台灣學童視力不良率與國健署「護眼 6 招」；針對視網膜自由基、兒童水晶體透光率及高色溫白內障風險與 AAO/Cochrane 立場標註 `[⚠️ 論點衝突]` 並另立爭議追蹤頁。

## [2026-11-17] ingest | 04_zenottic_glasses_vs_night_mode.md
- 來源：`raw/04_zenottic_glasses_vs_night_mode.md`（https://www.zenottic.com/blogs/eyewear-style-guide/blue-light-glasses-vs-night-mode）
- 新建：`[[04_ZENOTTIC_抗藍光眼鏡與夜間模式比較]]`、`[[抗藍光眼鏡與夜間模式比較]]`
- 更新：`[[抗藍光濾鏡眼鏡]]`、`[[裝置夜間模式與色溫調整]]`、`[[數位視覺疲勞與用眼行為]]`、`[[各機構對抗藍光與3C護眼立場比較]]`、`[[爭議_抗藍光眼鏡能否改善睡眠品質與晝夜節律]]`
- 摘要：建立螢幕端調整（夜間模式）與配戴端調整（眼鏡）之實務比較表，納入驗光處方與眩光控制優先性。

## [2026-11-17] ingest | 05_wikipedia_ar_coating.md
- 來源：`raw/05_wikipedia_ar_coating.md`（https://en.wikipedia.org/wiki/Anti-reflective_coating）
- 新建：`[[05_Wikipedia_抗反射鍍膜光學原理]]`、`[[薄膜干涉與四分之一波長鍍膜原理]]`、`[[減反射膜_AR鍍膜]]`
- 更新：`[[抗藍光濾鏡眼鏡]]`、`[[數位視覺疲勞與用眼行為]]`、`[[overview]]`、`[[index]]`
- 摘要：補齊光學鍍膜物理基礎，涵蓋菲涅耳反射、Rayleigh 折射率匹配、四分之一波長破壞性干涉、$\text{MgF}_2$ 單層與多層寬頻 AR 鍍膜及帶色反光成因。

## [2026-11-17] lint | 初始 5 篇文獻全庫健康檢查
- **矛盾與證據不一致**：通過。已於 [[藍光暴露、晝夜節律與視網膜風險]]、[[各機構對抗藍光與3C護眼立場比較]] 明確標註 `[⚠️ 論點衝突]`，並建立 [[爭議_藍光是否造成視網膜傷害與視覺疲勞]] 與 [[爭議_抗藍光眼鏡能否改善睡眠品質與晝夜節律]] 兩份獨立爭議追蹤頁。
- **引用與數據完整性**：通過（15 篇內容頁皆已附上 `raw/` 來源檔名、原始 URL、研究類型與實驗條件／關鍵原文引述）。
- **結構與連結健康度**：已修正 [[各機構對抗藍光與3C護眼立場比較]] 表格內的 `\|` 跳脫雙向連結語法；全庫共 18 頁，**0 個孤島頁面（Orphan pages）**、**0 個斷裂連結（Broken links）**、`index.md` 全數收錄。
- **研究缺口分析（Gap Analysis）**：
  1. 缺乏「抗藍光反射型多層介電膜（Blue-cut Dielectric Coating） vs. 吸收型基材（Blue-absorbing Substrate）」的具體光譜透過率曲線與反射光譜（如 400–455 nm 截斷特性）。
  2. 缺乏國際光學與抗藍光鏡片量測標準（如 ISO 12312-1、ISO 8980-3、ANSI Z80.3 或 CNS 15067）的具體濾波分級定義。
  3. 缺乏內在光敏視網膜神經節細胞（ipRGC）與視黑素（Melanopsin，峰值敏感波長 ~480 nm）的分子生理機轉文獻，以進一步定量對比「一般抗藍光眼鏡（濾除 400–450 nm 為主）為何對睡眠影響不明確」。
