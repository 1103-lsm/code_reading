# 代码阅读仓库

本仓库专用于存放和阅读代码示例，作为理解和分析不同代码库的个人收藏。

## 开始使用

使用 SSH 克隆此仓库：
```bash
git clone git@github.com:1103-lsm/code_reading.git
```

## 添加新的 Git 代码阅读仓库

1. **从 Git 跟踪中移除该文件夹**：
   ```bash
   git rm -r --cached -f folder_name
   ```
   将 `folder_name` 替换为你想要移除的实际文件夹名称。

2. **删除文件夹中的 `.git` 目录**：
   ```bash
   rm -rf folder_name/.git
   ```
   这将删除嵌套的 Git 仓库，使该文件夹变为普通目录。

3. **提交并推送更改**：
   ```bash
   git add .
   git commit -m "add new"
   git push origin main
   ```

## 贡献

欢迎提交 Pull Request 以改进代码或添加更多示例。

## 许可

本仓库为开源项目，可自由用于个人和教育用途。
