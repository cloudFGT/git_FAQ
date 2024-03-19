



# git账户信息配置

```bash
git config --global user.name "cloudFGT"

git config --global user.email "blukexiong@outlook.com"
```
查看配置结果：`git config --list`




# git中文显示乱码
```bash
git config --global core.quotepath false


```


# git仓库与本地仓库保持同步

```bash

先在GitHub上创建仓库，再克隆到本地

cd 本地仓库目录

git fetch origin   # step 1、 拉取git仓库

git merge origin/main  # step 2、 合并


```


# 将本地仓库同步到git上

```bash

cd 本地仓库目录                  # 进入本地仓库目录    


git add .  或者  git add 文件名   # 把改动的文件添加到暂存区

git commit -m "添加你的推送信息"  # 提交文件


#git branch -M main              # 创建main分支，第一次上传文件必须执行此命令

git push -u origin main         # 把文件推送到GitHub上



```



# 无法连接github
取消http代理，重新push，给git授权



# 创建脚本自动同步本地仓库与github

```bash





```

