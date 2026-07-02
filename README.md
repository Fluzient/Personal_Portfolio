# 刘子畅个人网站


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
