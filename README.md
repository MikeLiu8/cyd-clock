# CYD 時鐘安裝網站

Stage13-v17 朋友試用版，供 GitHub Pages 部署。

- 支援基準：ESP32-2432S028R、4MB、ILI9341_2_DRIVER、XPT2046、R1／320×240。
- `index.html`：安裝、SD下載及首次設定說明。
- `manifest.json`：ESP Web Tools，完整 BIN 於 offset0。
- `downloads/firmware-v17.bin`：由 v17 已燒錄的四個 segment 合併；app byte不變。完整安裝會重設板上設定。
- `downloads/sd-card-v17.zip`：Stage10 Bible／daily fonts＋v05 marquee＋v06 reflections。無 wifi.cfg、NVS、原始網頁、私人設定或診斷log。
- `downloads/firmware-source-v17.zip`：此版 firmware source，無專案歷史。
- `THIRD_PARTY_NOTICES.md`：來源／授權。
- `release.json`／`downloads/SHA256SUMS.txt`：版本及hash。

已知問題：巴士第2／3收藏偶爾更新失敗後恢復，原因未確認。另一塊板的觸控校正及本次瀏覽器全新安裝仍未實測。

## Pages

發布到獨立 public repository `cyd-clock`，Pages source為 `main` root `/`，HTTPS。只上載這個目錄的公開文件，不推送上層整個工作資料庫。Repository：https://github.com/MikeLiu8/cyd-clock 。網站：https://mikeliu8.github.io/cyd-clock/ 。使用者已授權本次發布，文件已上載並啟用 Pages；HTTPS 正式頁面、manifest、BIN、SD ZIP及source ZIP均已下載核對，與本地檔案一致。瀏覽器新板燒錄仍未實測。
