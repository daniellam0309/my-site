# 一鍵 GitHub Pages 網站樣板

這是我為你生成的 **靜態單頁網站**，可直接部署到 GitHub Pages。

## 快速開始

1. 在 GitHub 建一個新 Repository（例如 `my-site`）。
2. 下載本專案的 zip，解壓後把所有檔案推到 `main` 分支。
3. 到 **Settings → Pages**，把 **Source** 選為 **GitHub Actions**。
4. 推一次 commit，Actions 會自動部署。完成後，專案的 **Environments** 會顯示網站 URL。

## 自訂
- 把 `index.html` 內的「Your Brand」與文案替換成你的品牌內容。
- 在 `assets/` 放入你的圖片與圖示資源。
- 表單目前用 `mailto:`，可改接第三方（如 Formspree）或自家後端。

## 工作流程說明
此專案使用 GitHub Actions 官方的 Pages 工作流程：
- `actions/configure-pages` 配置 Pages
- `actions/upload-pages-artifact` 上傳靜態檔為 artifact
- `actions/deploy-pages` 部署到 Pages

> 部署設定參考 GitHub 官方文件。

---

產生時間：2025-09-04T03:38:36
