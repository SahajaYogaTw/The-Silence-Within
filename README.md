# 霎哈嘉瑜伽靜坐法｜Mobile First 網站原型

這是一套純 HTML、CSS 與少量原生 JavaScript 製作的靜態網站，可直接開啟，也可手動上傳至 GitHub Pages。沒有使用 React、網站框架或 ChatGPT 專屬技術。

目前四個頁面均設有 `noindex` 搜尋引擎禁止收錄標記。正式準備公開收錄時，請移除各 HTML `<head>` 內的 robots meta 標記。

## 頁面

- `index.html`：手機優先首頁
- `activities.html`：近期活動、課程資訊與報名入口
- `about.html`：認識我們、靜坐方法與常見問題
- `cooperate.html`：機關、學校、企業、社區與團體合作洽詢

所有照片放在 `assets` 資料夾。請保留 HTML 檔案與整個 `assets` 資料夾的相對位置。

`assets/og.png` 是網站的社群分享縮圖。各頁已使用 `https://sahajayogatw.github.io/The-Silence-Within/` 的完整公開網址設定 Open Graph、X/Twitter 圖片與 canonical URL。

## 本機查看

直接以瀏覽器開啟 `index.html`，即可從首頁進入其餘頁面。

## 手動上傳 GitHub Pages

1. 建立 GitHub repository。
2. 將本資料夾內所有 HTML 檔案、`README.md` 與整個 `assets` 資料夾上傳至 repository 根目錄。
3. 前往 **Settings → Pages**。
4. 將來源設為 **Deploy from a branch**，選擇 `main` 與 `/ (root)` 後儲存。

## 維護

文案與連結直接在各 HTML 檔案中修改。更換照片時，建議保留原檔名；若改用新檔名，也要同步修改對應 HTML 內的 `assets/檔名`。
