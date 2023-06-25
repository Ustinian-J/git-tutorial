# Git 常用操作

### 1. 初始化仓库

```
git init
```

### 2. 提交

```
# 将待提交内容放到暂存区
git add xxxx
# 保存仓库的历史记录
git commit [-m message]
# 提交至仓库
git pull
```

### 3. 查看状态

```
git status
```

### 4. 查看日志

```
# 查看完整日志
git log
# 只查看每个日志的一行
git log --pretty=short
# 只显示指定目录、文件的日志
git log xxxx
# 显示文件的改动
git log -p xxxx
```

### 5. 查看更改前后的差别

```
# 查看当前工作树和暂存区的差别
git diff
# 查看工作树和最新提交之间的差别
git diff HEAD
```

### 6. 分支操作

```
# 显示分支列表
git branch
# 创建、切换分支
git checkout -b xxxx
```

### fix-B

feature-c

feature-D

