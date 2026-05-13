# 即時文字雲 (Firebase + GitHub Pages)

用 Firebase Firestore 即時同步的文字雲教學工具。

## 頁面

| 頁面 | 用途 |
|------|------|
| `index.html` | 學生輸入關鍵字（手機掃 QR Code 開啟） |
| `display.html` | 老師展示文字雲（投影幕） |

## 使用方式

1. 老師開啟 `display.html`，投影到大螢幕
2. 學生掃描螢幕右側 QR Code
3. 輸入關鍵字送出，文字雲即時更新

## 技術

- Firebase Firestore（即時資料庫）
- wordcloud2.js（文字雲渲染）
- qrcodejs（QR Code 產生）
- 純靜態 HTML，無需後端
