## gitの操作方法

```markdown

変更を書き加えるとき（push）
git add <変更をコミット準備するファイルを選択する、通常の場合は「.」でok>
git commit -m "コメント"
git push origin main

最新の情報に更新するとき（pull）
git pull <更新するファイル名>
git pull . // こうしておけば全部更新されてので問題なし

リモートリポジトリに登録する時（リモートリポジトリ：オンライン上に上がっているブランチのこと）
git remote add <リモートリポジトリの名前（基本的にはorigin）> <リモートブランチのURL>

git管理しているファイルに変更をした場合、変更したファイルがどれ確認できる
git status

diffを使うことでより詳細に変更箇所を確認することができる
git diff

```
