# 🧮 神算子

朋友分帳神器 — 一鍵神算，唔使爭。每個活動有自己嘅「阿公」（公數）。

[![開啟 Web App](https://img.shields.io/badge/開啟-Web_App-7c3aed?style=for-the-badge)](https://nik-neural.github.io/sansuanzi/)

## 同圓子基金有咩分別？

| | 圓子基金 | 神算子 |
|---|---------|--------|
| 名稱 | 圓子基金 | 神算子（潮啲，朋友一眼就明） |
| 共同錢包 | 圓子基金（全局共享） | 阿公 / 公數（每個活動獨立） |
| 適合 | 長期一齊用嘅共同基金 | 單次聚會、旅行、活動分帳 |

## 功能

- 多人活動記帳，自動計算每人應付 / 應收
- 阿公墊支開支、結算轉入（每個活動獨立計算）
- 建議還款方案 + WhatsApp 分享
- 活動匯出 / 匯入（兼容圓子基金格式）

## 加入主畫面（PWA）

1. 用手機或電腦開啟上方連結
2. **Safari / Chrome** → 分享 / 選單 → **加入主畫面**

## 同系列 App

| | App | 說明 | 連結 |
|---|-----|------|------|
| 🚌 | **巴士到站** | 九巴 / 城巴 ETA + 天氣 | [nik-neural.github.io/hk-bus](https://nik-neural.github.io/hk-bus/) |
| 💰 | **圓子基金** | 群組消費記帳 + 全局基金 | [nik-neural.github.io/circle-fund](https://nik-neural.github.io/circle-fund/) |
| 🧮 | **神算子** | 朋友分帳 + 每活動阿公 | [nik-neural.github.io/sansuanzi](https://nik-neural.github.io/sansuanzi/) |
| ⚡ | **香港 EV 泊車** | 全港 EV 停車場即時空位 | [nik-neural.github.io/hk-ev-park](https://nik-neural.github.io/hk-ev-park/) |

## 技術

- 單一 HTML · Tailwind CDN · 零後端
- [GitHub Pages](https://pages.github.com/) 部署
- PWA（`manifest.json` + `icons/`）
- 資料儲存喺瀏覽器 localStorage，唔会上傳伺服器