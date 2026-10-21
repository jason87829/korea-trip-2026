# 韓國旅遊嚮導 · 2026 秋

我跟家人 2026/10/23 – 10/31 的韓國行程備忘錄，做成可互動的旅遊嚮導頁面。

- **釜山 4 晚**（10/23 – 10/27）：[busan.html](busan.html) · [線上瀏覽](https://jason87829.github.io/korea-trip-2026/busan.html)
- **首爾 4 晚**（10/27 – 10/31）：在首頁切到「首爾」分頁 · [線上瀏覽](https://jason87829.github.io/korea-trip-2026/#seoul)
- 首頁 [index.html](index.html) 合併釜山＋首爾兩個分頁

## 內容
- 上午 / 下午 / 晚上各一個主軸 + 周邊景點 chip
- 互動式 Leaflet 地圖（含每日交通方式、Sky Capsule / Beach Train / Uber 等路線）
- 每個景點附 Google Maps 連結
- Hotel GUESS WHO Gwangalli（猜猜飯店）設為每日起點 / 終點

## 技術
純 HTML / CSS / 原生 JS，無 build step。地圖用 [Leaflet](https://leafletjs.com) + OpenStreetMap (CARTO Voyager tiles)。
