# 烟花爱心 - 吴桐

一个浪漫的烟花爱心动画网页，展示爱心形状烟花绽放、小爱心飘散，最后显示"吴桐"字样。

## 部署到 GitHub Pages

### 方法一：使用 GitHub Desktop（推荐）

1. **创建 GitHub 账号**
   - 访问 https://github.com/ 注册账号

2. **下载安装 GitHub Desktop**
   - 访问 https://desktop.github.com/ 下载安装

3. **创建新仓库**
   - 打开 GitHub Desktop
   - 点击 "File" -> "New Repository"
   - 仓库名称：`fireworks-love`（或任意名称）
   - 本地路径选择：`c:\Users\13995\Desktop\心`
   - 勾选 "Initialize this repository with a README"
   - 点击 "Create repository"

4. **上传文件**
   - 将 `index.html` 拖放到仓库目录
   - 在 GitHub Desktop 中输入提交信息：`Add fireworks animation`
   - 点击 "Commit to main"
   - 点击 "Publish branch"

5. **开启 Pages**
   - 访问你的 GitHub 仓库页面（如 https://github.com/你的用户名/fireworks-love）
   - 点击 "Settings" -> "Pages"
   - 在 "Source" 中选择 `main` 分支，点击 "Save"
   - 等待几分钟后，访问 `https://你的用户名.github.io/fireworks-love/` 即可

### 方法二：手动上传（无需 GitHub Desktop）

1. 创建仓库后，在仓库页面点击 "Add file" -> "Upload files"
2. 拖拽 `index.html` 和 `README.md` 到上传区域
3. 填写提交信息后点击 "Commit changes"
4. 按照方法一的步骤 5 开启 Pages

## 效果预览

- 烟花从爱心轮廓绽放
- 小爱心从中心飘散
- 最后显示 "吴桐" 字样，周围持续飘出小爱心

## 技术特点

- 纯前端实现，无需后端
- 使用 Canvas 动画，流畅不卡顿
- 响应式设计，适配手机和电脑

## 本地预览

直接用浏览器打开 `index.html` 即可预览效果。