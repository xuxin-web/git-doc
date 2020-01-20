# git 命令指南

## 创建新项目
```
git init
```

## 克隆已有项目
```
git clone 项目地址
```

## 从分支克隆项目
```
git clone -b 分支名 
```

## 将项目推送到指定分支
```
git push origin 分支名
```

## 添加跟踪文件
```
git add 文件名
git add .
git add *
```

## 提交代码
```
git commit -m "所更新内容的提示"
```

## 首次远程推送项目
```
git remote add origin 项目地址
```
## 创建分支
```
git checkout -b 分支名称
```

## 切换分支
```
git checkout 分支名称
```

## 删除分支
```
git branch -d 分支名
```

## 合并分支
```
git merge 分支名
```

## 预览差异
```
git diff 参照分支版本 你的分支版本
```

## 获取提交的历史信息
```
git log
```

## 替换本地改动
```
git checkout --文件名
```

## 丢弃本地的所有改动的提交
```
git fetch origin
git reset --hard origin/master
```

## 更新项目
```
git pull
```

