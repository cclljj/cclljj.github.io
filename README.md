# Ling-Jyh Chen 個人網站 / Personal Website

![Hugo](https://img.shields.io/badge/Hugo-black.svg?style=for-the-badge&logo=Hugo)
![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

網站網址 / Website: [https://cclljj.github.io](https://cclljj.github.io)

## 繁體中文（台灣）

### 專案簡介
本專案為 Ling-Jyh Chen 的學術個人網站，使用 Hugo 建置並部署到 GitHub Pages。  
網站內容包含個人簡介、研究、出版品、演講、課程與下載資源。

### 特色
- `Publications` 已整併為單頁分區（含分類錨點導覽）
- 舊出版品分類連結可相容導向
- 全站提供 AI agent 友善輸出（JSON、JSON-LD、`llms.txt`）
- SEO/AEO 強化（meta description、FAQ schema、Breadcrumb、日期與 citation meta）

### 技術棧
- Static Site Generator: Hugo
- Theme: [hugo-resume](https://themes.gohugo.io/themes/hugo-resume/)
- Deployment: GitHub Pages（GitHub Actions）

### 本機開發
1. 安裝依賴（若尚未安裝 Hugo）
```bash
npx --yes hugo-bin version
```

2. 啟動本機伺服器
```bash
npx --yes hugo-bin server -D
```

3. 建置靜態檔
```bash
npx --yes hugo-bin --gc --minify
```

### 內容維護重點
- 站台設定：`config.toml`
- 內容檔案：`content/`
- 版型模板：`layouts/`
- 靜態資源：`static/`
- AI 讀取提示：
  - `static/llms.txt`
  - `static/llms-full.txt`

### 發布流程
- Push 到 `main` 分支後，GitHub Actions 會自動建置並部署到 `gh-pages` 分支。
- workflow 檔案位置：`.github/workflows/hugo_deploy.yml`

---

## English

### Overview
This repository hosts Ling-Jyh Chen’s academic personal website, built with Hugo and deployed to GitHub Pages.  
The site includes profile, research, publications, talks, courses, and downloadable resources.

### Highlights
- `Publications` is consolidated into a single-page, category-anchored layout
- Legacy category URLs are redirected for compatibility
- AI-agent-friendly outputs are available (JSON, JSON-LD, `llms.txt`)
- SEO/AEO enhancements are included (meta description, FAQ schema, breadcrumbs, freshness dates, citation meta)

### Tech Stack
- Static Site Generator: Hugo
- Theme: [hugo-resume](https://themes.gohugo.io/themes/hugo-resume/)
- Deployment: GitHub Pages (via GitHub Actions)

### Local Development
1. Check Hugo (via `hugo-bin`)
```bash
npx --yes hugo-bin version
```

2. Run local server
```bash
npx --yes hugo-bin server -D
```

3. Build static site
```bash
npx --yes hugo-bin --gc --minify
```

### Key Paths
- Site config: `config.toml`
- Content: `content/`
- Layout templates: `layouts/`
- Static assets: `static/`
- AI crawling guidance:
  - `static/llms.txt`
  - `static/llms-full.txt`

### Deployment
- Pushing to `main` triggers GitHub Actions and deploys to `gh-pages`.
- Workflow file: `.github/workflows/hugo_deploy.yml`
