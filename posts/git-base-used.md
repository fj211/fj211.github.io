---
title: git的基础使用
date: 2026-8-31
permalink:
---

GitHub 克隆项目到本地

1. 在空文件夹目录下打开Git Bash

2. 执行克隆命令

   ```bash
   git clone 地址
   ```

Push本地

```bash
git pull --rebase origin master

git add .
git commit -m "备注"
git push origin master
```

Git回滚

1. 先看提交id

   ```bash
   git log --oneline
   ```

2. 本地回滚到目标版本

   ```bash
   git reset --hard 提交id
   回退一个版本
   git reset -- hard HEAD~1
   ```

3. 覆盖远程分支

   ```bash
   git push -f origin 分支
   ```

   

