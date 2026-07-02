# 刘子畅个人简历网站

这是一个使用原生 HTML、CSS、JavaScript 搭建的单页个人简历网站，适合直接部署到 GitHub Pages，面向中文求职场景。

## 本地预览

可以直接双击打开 `index.html` 预览页面。

如果想用本地服务查看，也可以在当前目录执行：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 文件说明

- `index.html`：页面结构与简历内容
- `styles.css`：页面样式
- `script.js`：导航、滚动高亮、复制邮箱等交互
- `*.pdf`：原始简历 PDF

## 发布到 GitHub Pages

推荐使用 GitHub 用户主页方式发布：

1. 在 GitHub 创建一个仓库，仓库名必须为 `你的用户名.github.io`
2. 在当前目录初始化 Git 仓库
3. 提交网页文件
4. 关联远程仓库
5. 推送到 `main` 分支

示例命令：

```powershell
git init -b main
git add .
git commit -m "初始化个人简历网站"
git remote add origin https://github.com/你的用户名/你的用户名.github.io.git
git push -u origin main
```

## 开启 Pages

对于 `你的用户名.github.io` 这种用户主页仓库，通常推送到 `main` 分支后会自动发布。

如果没有自动上线，可以到仓库的：

`Settings` -> `Pages`

确认发布来源为：

- Branch: `main`
- Folder: `/ (root)`

发布成功后的地址为：

`https://你的用户名.github.io/`

## 后续可扩展

- 增加中英双语切换
- 增加项目截图或作品集模块
- 增加 PDF 下载按钮
- 增加 GitHub、博客或其他社交链接
