# home.iamblwb.com

iamblwb.com 專案入口頁 — 所有產品的清單與連結。

## 部署

自動 CI/CD via GitHub Actions → VPS SSH deploy。

### 本地預覽
直接在瀏覽器開 `index.html`。

### 新增專案卡片
在 `index.html` 複製 `.card` 區塊，修改：
- `class="c-xxx"` → 顏色主題
- `icon-wrap` → emoji 圖示
- `.card-title` → 專案名稱
- `.card-desc` → 說明文字
- `.card-url` → 子網域
- `href=` → 實際連結
