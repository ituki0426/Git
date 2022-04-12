# Gitおよび、Githubの使い方

前提

githubアカウントの作成

sshkeyの追加　
## (1)用語

### クローン:リモートリポジトリをローカル側に複製

### プッシュ:ローカルでのコミット内容をリモート側に同期

### プル:リモートでのリポジトリの内容をローカル側に同期

### マージ：ほかのブランチやコミット内容を現在のブランチに取り込む

## (2)Githubに新規リポジトリを追加

ローカルで作成したソースコードをGithubにアップロードする手順を説明します。

### ➀git initでセットアップ

### ➁git add -Aでインデックスファイルを追加

### ➂git commit -m "message"で変更を反映

### ➃github上で新規リポジトリを作成

### ➄githubのモードリポジトリをローカルリポジトリに追加する

```git remote add origin [リモートリポジトリ情報]````

例

```git remote add origin　https://github.com/sodaihirai/sample_app.git```

#### git pushでローカルリポジトリの変更をリモートリポジトリに反映する。

```git push origin main```

## (3)カレントブランチを切り替える

```git checkout ブランチ名```

## (4)ブランチをまーじする
マージ先のブランチに切り替える

```git checkout マージ先のブランチ名(mainなど)```

マージするブランチを指定する

```git merge ブランチ名(kadai1など)```



