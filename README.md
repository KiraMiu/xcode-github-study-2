# xcode-github-study-2
学习项目2。用于学习如果操作xcode与github进行版本控制。

## 前提：
1. 本地仓库已存在，且经过多次commit操作，有n个版本。
2. 新建的远程仓库，且为空仓库。

## 操作：
1. 本地终端中进行如下操作：

```
cd 本地项目路径

git add .

git commit -m "版本描述信息：标题"

git remote add 本地仓库名 远端仓库的https地址

git push -u 本地仓库名 master
```

2. 之后再在xcode打开项目文件，此时就能在xcode下进行push、pull等与远端仓库进行交互的操作了。
