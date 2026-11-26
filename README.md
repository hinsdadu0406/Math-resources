# Math Gym · 數學教材

公開的數學 Concept 筆記與 Quiz，供中三至中六學生參考。

網站：https://hinsdadu0406.github.io/Math-resources/

## 內容

- **notes/f3–f6/** — 各年級 Concept 筆記（PDF）
- **quiz/** — 課題小管測（PDF）

只公開 Concept 和自建 Quiz。Exercise、答案和其他人的作品不作公開。

## 維護備註（Maintainer notes）

新增或更新教材的固定流程：

1. **準備檔案** — PDF 按頁面左上角 CONCEPT / EXERCISE 標記分界（必須用截圖視覺確認，不能只靠文字擷取）；用 `pymupdf.rewrite_images(dpi_target=110)` 壓縮；放入對應資料夾；更新 `index.html` 連結。
2. **上傳** — GitHub Add file → Upload files → 拖資料夾 → Commit changes。
3. **等待** — 約 1 分鐘後 Pages 自動更新。

替換單一檔案：拖同名檔案上傳，選覆蓋即可。

注意：一次拖整個大資料夾可能超過 100MB 限制；壓縮後體積約 28MB，沒有問題。
