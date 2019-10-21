# GitHub Practice 1
## 初期手順
```bash
mkdir **; cd **
git init
vi README.md
git add .
git commit → first commit
git remote add origin (SSH key)
git push -u origin master
```

その他コマンド
```buildoutcfg
git status
git log --oneline
```
home直下の.gitconfigからエイリアス編集してショトカ登録

## Pull Request手順
GitHubの子のリポジトリで「Compare ＆ pull request」選択
親のリポジトリでmergeする  
→いらないbranchは消す「Delete Branch」