# 🎄 圣诞邀请函 GitHub 部署指南

## 📋 需要上传的文件

你只需要上传这两个文件：

```
✅ index.html          (圣诞邀请函主文件)
✅ README.md           (项目说明)
```

## 🚀 快速部署步骤

### 第一步：创建 GitHub 仓库

1. 登录 [GitHub](https://github.com)
2. 点击右上角 "+" → "New repository"
3. 仓库名称：`christmas-invitation`
4. 设置为 **Public**（重要！）
5. 点击 "Create repository"

### 第二步：上传文件

**方法A：网页拖拽（推荐）**

1. 在新仓库页面，点击 "uploading an existing file"
2. 拖拽这两个文件到上传区域：
   - `index.html`
   - `README.md`
3. 提交信息：`🎄 圣诞团建邀请函上线`
4. 点击 "Commit changes"

**方法B：Git 命令行**

```bash
cd /Users/tingtingong/Desktop/drawTool/gift-draw-main

# 只添加需要的文件
git init
git add index.html README.md
git commit -m "🎄 圣诞团建邀请函上线"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/christmas-invitation.git
git push -u origin main
```

### 第三步：启用 GitHub Pages

1. 进入仓库 → "Settings" → "Pages"
2. Source: "Deploy from a branch"
3. Branch: "main"
4. Folder: "/ (root)"
5. 点击 "Save"

### 第四步：获取网址

等待 2-5 分钟后，你的网址将是：
```
https://YOUR_USERNAME.github.io/christmas-invitation
```

## 🎯 完成！

现在你可以：
1. 把网址分享给团队成员
2. 大家用英文名登录查看心愿
3. 管理员用 `admin` 查看完整配对

## 🔄 如需更新

直接在 GitHub 网页上编辑 `index.html` 文件，保存后会自动重新部署。

---

🎄 **祝部署顺利，圣诞快乐！** 🎅