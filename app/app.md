
### 添加新文件

创建分支 `feature/add-newfile`，添加新文件；

然后切换回主分支；

重新创建新的分支 'feature/add-file2‘,添加文件 file2.json;
相当于两人在做不同的开发；

切换回主分支；
创建分支 `release/1.0.1`, 合并分支`feature/add-newfile`;
（一人合并分支）；

切换回 `feature/add-newfile`， git  diff release/1.0.1

切换回 `release/1.0.1', 合并分支'feature/add-file2.json'


// add-file2 分支出现错误，`release/1.0.1`要在回退版本；

```
git log 

git reset --hard 版本号

```

如果此刻我将 release/1.0.1分支合并到主分支的话， 主分支是否还有add-file2文件？




