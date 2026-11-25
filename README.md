# 楊敏寬 攝影

Yang Ming-kuan Photography 作品網站。純靜態網頁（HTML／CSS／JS），以 GitHub Pages 發布。

- `index.html`：全站頁面（首頁、四個系列展廳、關於、聯絡）
- `img/w/`：作品圖 WebP，含浮水印，每張兩種尺寸：`系列-編號-800.webp`、`系列-編號-1600.webp`；首頁主視覺為 `h-名稱-1200.webp`、`h-名稱-2200.webp`
- `img/t/`：縮圖 WebP（長邊 480px，無浮水印）
- `img/h/home-01.jpg`：社群分享預覽圖；`img/about-01.jpg`：關於頁肖像

新增作品：照片先裁成 3:2（橫）或 2:3（直），依上述命名產生各尺寸 WebP 放進 `img/w/` 與 `img/t/`，再到 `index.html` 的 `SERIES` 資料中更新該系列的 `shape`（每張一個字元：L 橫幅、P 直幅），並在 `sitemap.xml` 補上新圖。
