# Git完全に理解した

(main) 今日はcommitとbranch, mergeについて勉強する。
ブランチは次のようにして切ることができる。
``` zsh
git branch <branchname>
git branch develop # developというローカルブランチができる
```

(develop) ここではdevelopブランチに記述してます。
``` zsh
git checkout <branchname>
```
でブランチを切り替えることができます。

コンフリクトが起きても落ち着いて修正すればOK
特に余計な改行や空行を挟まないことがリーダブルなコードを書く上で、Gitで管理する上で大事だと思いました。