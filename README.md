# 值班排班表 v2（含調班申請）

## 部署步驟 — GitHub Pages（免費）

### 第一步：建立 GitHub 帳號
前往 https://github.com 註冊免費帳號

### 第二步：建立新的 Repository
1. 登入後點右上角「+」→「New repository」
2. Repository name 填：`schedule-app`（或任意名稱）
3. 選「Public」
4. 按「Create repository」

### 第三步：上傳檔案
1. 進入剛建立的 repository
2. 點「uploading an existing file」
3. 把以下三個檔案拖曳上傳：
   - index.html
   - manifest.json
   - sw.js
4. 按「Commit changes」

### 第四步：開啟 GitHub Pages
1. 點上方「Settings」
2. 左側找「Pages」
3. Source 選「Deploy from a branch」
4. Branch 選「main」，按「Save」
5. 等 1~2 分鐘，網址出現：
   https://你的帳號.github.io/schedule-app/

---

## 分享給同事

把網址傳給大家，並說明：

**iPhone / iPad：**
Safari 開啟 → 下方工具列分享鈕（方形加箭頭）→「加入主畫面」

**Android：**
Chrome 開啟 → 右上三點選單 →「新增到主畫面」或「安裝應用程式」

**電腦（Chrome/Edge）：**
網址列右側會出現安裝圖示，點擊即可安裝

---

## App 功能說明

### 月曆頁
- 瀏覽每月排班，顏色區分輪班 / 麗卿 / 已調班
- 可查詢任意日期的值班人員

### 申請調班
- 選擇申請人、自己的排班日、對調人、對調日
- 系統自動驗證人員是否符合
- 送出後進入「待審核」狀態

### 調班紀錄
- 可篩選「全部 / 待審核 / 已核准 / 已拒絕」
- 開啟「管理員模式」才能看到核准 / 拒絕按鈕
- 核准後月曆立即更新

---

## 排班規則

- 起始日：2026 年 4 月 6 日（光男）
- 輪班順序：光男 → 玉輝 → 國華 → 賜海 → 順裕（每日輪替，含週日）
- 週五固定：麗卿

---

## App 圖示（選用）

如需精美圖示，前往 https://realfavicongenerator.net
上傳任何圖片，下載後把 icon-192.png 和 icon-512.png 放在同一資料夾上傳。
