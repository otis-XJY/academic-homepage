# 学术主页

这是一个简洁的个人学术主页模板，基于 **HTML + CSS**，可直接部署在 GitHub Pages 上。

---

## 📂 文件结构
```
academic-homepage/
 ├─ index.html       ← 主页面（你要修改的地方）
 ├─ images/          ← 存放照片（例如 profile.jpg）
 └─ files/           ← 存放简历 (CV.pdf)、出版物列表 (publications.pdf) 等附件
```

---

## 🚀 部署到 GitHub Pages

1. **创建仓库**
   - 登录 GitHub，点击右上角 **➕ → New repository**
   - 仓库名可取为 `academic-homepage`，或者直接用 `username.github.io`  
     - ⚠️ 如果仓库名是 `username.github.io`，其中 `username` 必须是你的 GitHub 用户名

2. **上传文件**
   - 下载并解压本项目
   - 上传 `index.html`、`images/`、`files/` 到仓库根目录

3. **启用 Pages**
   - 进入仓库 **Settings → Pages**
   - 在 **Build and deployment** 中：
     - Source 选 **Deploy from branch**
     - Branch 选 `main` (或 `master`)，文件夹保持 `/root`
   - 保存后等待约 1 分钟，GitHub 会自动生成访问链接

4. **访问主页**
   - 如果仓库名是 `academic-homepage`：  
     `https://username.github.io/academic-homepage/`
   - 如果仓库名是 `username.github.io`：  
     `https://username.github.io/`

---

## ✏️ 修改主页内容

- 打开 `index.html`，修改以下部分：
  - **姓名 / 英文名**  
  - **职称 / 单位 / 实验室**  
  - **研究方向简介**  
  - **出版物列表**  
  - **联系方式（邮箱、GitHub、Google Scholar 等）**

- 替换 `/images/profile.jpg` 为你的个人照片
- 上传 `CV.pdf` 和 `publications.pdf` 到 `/files/` 文件夹，并在 `index.html` 中保持链接正确

---

## 🛠️ 未来扩展

- 增加中英文切换
- 美化主题（暗色 / 浅色）
- 使用 Markdown 自动生成出版物列表

---

📌 部署后，每次修改 `index.html` 并提交 (commit + push)，网页会自动更新。
