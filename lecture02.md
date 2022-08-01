# 第2回 バージョン管理システムについて

## 種類
1. Git gitHub

2. SVN



## 特色
1. git
- メリット<br>
リモートリポジトリとローカルリポジトリに分かれており、複数の履歴保持の場所を持つ点がチーム開発に向いております。
- デメリット<br> 
分散型ではないため、バージョン管理するリポジトリ(データの貯蔵庫)は単一です、リポジトリが破損すると今までのデータが消えます。
しかし、スナップショットでバックアップを容易に取得できる為、復元は容易です。




2. SVN
- メリット<br>
リモートリポジトリとローカルリポジトリに分かれており、複数の履歴保持の場所を持つ点がチーム開発に向いております。
- デメリット<br> 
Gitと違って分散型ではなく、チーム開発に向いていない為、最近では使用されていない。



## Markdown
・HTML(Webページを表示させる言語)が使用できなくても、簡単な記号の修飾で同じような見た目を実現できる。

・書き方
見出しは、#、番号リストが1、番号なしリストは*または-で書きます。



## 3. コマンド説明
- (Gitコマンド１)<br>
・git init (gitリポジトリーの作成　最初だけ)　<br>
・git remote add origin (GitHubのURLを登録)<br>
・git switch -c <ブランチ名>　(ブランチを作成して切り替える)<br>
※リポジトリーとは、フォルダーやファイルなどの記録する場所<br>


- (Gitコマンド２)<br>
・git add . (変更内容をステージングに追加)<br>
・git commit -M (git commit -m "メッセージ")<br>
・git push origin <ブランチ名> (GitHubにプッシュ)<br>


- (Gitコマンド３)<br>
・git switch <ブランチ名> (ブランチを切り替える)<br>
・git pull origin <ブランチ名> (GitHubの変更内容を取り込む)<br>


- github メールアドレス ユーザーネーム<br>
・git config —global user.name "設定"<br>
・git config —global user.email "設定"<br>
・git config —global merge.ff false<br>
・git config —global pull.rebase merges<br>
・git config —list (確認する)<br>
