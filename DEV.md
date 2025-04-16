## Update from original repo

```bash
git remote add upstream https://github.com/honza/vim-snippets.github

git fetch upstream
git checkout main            # 或你本地的主分支名
git merge upstream/main      # 合并上游的更改到你的主分支
```


## Modify code

```
git checkout -b feature/my-change
# 进行修改后：
git add .
git commit -m "自定义修改"
```


