# 六十四卦產生器 · 易經八卦

設定六爻（少陽、老陽、少陰、老陰），即時產生卦象圖，並下載成 SVG 或 PNG 圖示。

**線上使用**：https://kftseng2oo1.github.io/HG/

## 主要功能
- 逐爻設定四象，老陽、老陰會標示為變爻並顯示變卦
- 快速選卦：六十四卦格子點選、🎲 隨機起卦、全陽（乾）、全陰（坤）
- 顏色預設：金、玉、朱、銀、墨、海、土、火，也可自訂
- 下載 SVG、PNG 192×192、PNG 512×512（可直接當 App 圖示）

## 技術與依賴
- 單檔 HTML PWA（`index.html` 內含全部 HTML/CSS/JS），`manifest.json` + `sw.js` 提供安裝到主畫面與離線快取。
- SVG 產生圖形、Canvas 轉 PNG，純前端

## 相關 repo
- [gamei](https://github.com/kftseng2oo1/gamei)：六十四卦猜卦名遊戲
