# 鮮乳坊的商業革命 — 研究成果網站

農產品電商行銷策略分析，屏東科技大學農企業管理系農企二A

---

## 📁 檔案命名規則與放置位置

上傳到 GitHub Pages 前，請將您的原始檔案**重新命名**後放入對應資料夾：

```
你的專案資料夾/
├── index.html                        ← 主網頁（已提供，勿更動）
├── README.md                         ← 說明文件
│
├── docs/                             ← 放 PDF 和 Word 文件
│   ├── research-report.pdf           ← 完整研究報告（農產品電商行銷策略分析.docx 轉PDF）
│   ├── slides.pdf                    ← 簡報PDF（鮮乳訪店商行銷革命.pdf 直接複製改名）
│   └── podcast-transcript.docx      ← Podcast逐字稿（Podcast_逐字稿.docx 直接複製改名）
│
└── media/                            ← 放音頻和影片
    ├── podcast.m4a                   ← Podcast音檔（鮮乳坊最貴牛奶的八億商戰.m4a 複製改名）
    └── video-overview.mp4            ← 教學影片（鮮乳坊的電商革命_營收奇蹟.mp4 複製改名）
```

---

## 🔄 您需要做的檔案處理

| 原始檔案名稱 | 目標路徑 | 操作 |
|---|---|---|
| `農產品電商行銷策略分析.docx` | `docs/research-report.pdf` | 用 Word 另存為 PDF |
| `鮮乳訪店商行銷革命.pdf` | `docs/slides.pdf` | 直接複製並改名 |
| `Podcast_逐字稿.docx` | `docs/podcast-transcript.docx` | 直接複製並改名 |
| `鮮乳坊最貴牛奶的八億商戰.m4a` | `media/podcast.m4a` | 直接複製並改名 |
| `鮮乳坊的電商革命_營收奇蹟.mp4` | `media/video-overview.mp4` | 直接複製並改名 |

> **研究報告轉PDF方法：**
> - Word → 檔案 → 匯出 → 建立PDF/XPS → 儲存為 `research-report.pdf`

---

## 🚀 上傳 GitHub Pages 步驟

### 第一步：建立 GitHub Repository

1. 登入 [github.com](https://github.com)，點擊右上角 **「+」→「New repository」**
2. Repository name 填入：`freshmart-research`（或任何英文名稱）
3. 設定為 **Public**（GitHub Pages 免費版需要公開）
4. 勾選 **「Add a README file」**
5. 點擊 **「Create repository」**

### 第二步：上傳檔案

**方法A（建議新手）：直接在網頁上傳**

1. 進入你剛建立的 repository
2. 點擊 **「Add file」→「Upload files」**
3. 將整個資料夾的內容（`index.html`、`docs/`、`media/`）**全部拖曳**進去
4. 在下方 Commit 欄填入說明，例如：`初次上傳研究成果網站`
5. 點擊 **「Commit changes」**

**方法B（使用 Git 命令列）**
```bash
git clone https://github.com/你的帳號/freshmart-research.git
# 將所有檔案複製進去
git add .
git commit -m "初次上傳研究成果網站"
git push origin main
```

### 第三步：開啟 GitHub Pages

1. 進入 repository → 點擊上方 **「Settings」**
2. 左側選單找到 **「Pages」**
3. Source 選擇 **「Deploy from a branch」**
4. Branch 選 **「main」**，資料夾選 **「/ (root)」**
5. 點擊 **「Save」**

### 第四步：等待部署完成

- 等待約 **1–3 分鐘**
- 頁面上會出現網址，格式為：
  `https://你的帳號.github.io/freshmart-research/`
- 將此網址提交給老師即可 🎉

---

## ⚠️ 注意事項

- **影片和音頻檔案**如果超過 **100MB**，GitHub 會拒絕上傳。
  解決方案：使用 [Git LFS](https://git-lfs.github.com/) 或將影片上傳至 YouTube，
  再將 `index.html` 中的影片 `<source>` 改為 YouTube 嵌入碼。
- 成員照片：若要加入真實照片，將圖片命名為 `images/photo-lin.jpg`、`images/photo-chen.jpg`、`images/photo-hong.jpg`，
  並在 `index.html` 中將 `.member-photo-placeholder` 替換為 `<img>` 標籤。
- 所有路徑**區分大小寫**，請確保檔名完全符合上表。

---

## 👥 研究團隊

- **林子津**：主要研究者、數據分析
- **陳柔瑩**：行銷策略、視覺設計  
- **洪愷呈**：永續策略、創意發想

屏東科技大學農企業管理系農企二A，2026年
