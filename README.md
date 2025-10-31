# toucheng-parking｜頭城停車場自治條例專案

本專案彙整：
- **法規正文庫（regulations/）**：宜蘭縣與各鄉鎮正式條文。
- **制法與修法歷程（lawmaking-process/）**：比較表、總說明、逐條理由書、會議資料。
- **公開網站（docs/）**：GitHub Pages，用於 QR 固定網址與對外下載。
- **資料集（datasets/）**：費率、場站位置等結構化資料。
- **參考資料（references/）**：契約、標竿條例、媒體資料。

## 部署 GitHub Pages（固定網址）
1. 上傳整個 repo 至 GitHub，將分支設為 `main`。
2. 設定：Settings → Pages → Source: `Deploy from a branch`；Branch: `main`；Folder: `/docs`。
3. 取得網址 `https://<user>.github.io/toucheng-parking/`，把 QR 印在對外文件上。

## 更新最新版文件
- 覆蓋 `docs/files/latest/` 中的：
  - `policy-brief.pdf`（一頁式）
  - `compare-A3.pdf`（全縣/鄉鎮對照）
  - `article-by-article.pdf`（逐條理由書）
- 歷史版本請放入 `docs/files/briefs/` 或 `docs/files/compare/`。

## 版本紀律
- 檔名含日期：`YYYY-MM-DD_主題_型式.ext`
- 正式 vs 草案：`_final`、`_draft` 或 `v1/v2`。
- 多語系：尾綴 `zh-TW` / `en` / `ja`。

---
自動建立：2025-10-31
