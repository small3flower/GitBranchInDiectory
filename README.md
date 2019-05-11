# git 仓库分支多文件夹管理



分支是 git 管理的一大特性，在多人开发大型项目中，经常遇到分支很多，且很多分支需要暂时保留的情况，可以考虑使用文件夹管理不同特性的分支。

> 经过测试，git branch 创建分支命令支持 路径/分支名 这种形式，且能够将路径一同推送到远端。

命令行中所示：

![git 仓库分支多文件夹管理](https://github.com/small3flower/GitBranchInDiectory/blob/master/images/git%20%E4%BB%93%E5%BA%93%E5%88%86%E6%94%AF%E5%A4%9A%E6%96%87%E4%BB%B6%E5%A4%B9%E7%AE%A1%E7%90%86.png)

在图形化工具 sourceTree 中效果：

![sourcetree_eg](https://github.com/small3flower/GitBranchInDiectory/blob/master/images/sourcetree_eg.png)

git 命令如下：

```
// 创建并切换到分支 branchName
git checkout -b [path]/[branchName]
// 将当前新创建的分支推送到远端
git push origin [path]/[branchName]
```


