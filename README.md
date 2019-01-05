### 1. 从远程仓库克隆到本地
       git clone 加ssh连接
### 2. 更改本地代码之后提交相关操作
        git status 查看本地仓库的状态

        git add . 把更改的添加到本地暂存区

        git commit -m "提交日志" 提交到本地仓库
### 3. 回滚

    git reset --hard HEAD 回滚到最近的一个版本
    git reset --hard 版本号 回滚到指定的版本

### 4. 把本地代码提交到git服务器
        git push origin master -u xxx 配置了ssh秘钥可以直接git push    

## 使用git 来创建分支


## 使用git checkout -b 切换分支

### git checkout -b v1.2_bugfix

