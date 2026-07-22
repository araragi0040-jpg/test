# GitHub Pages 公開手順

## 1. リポジトリを作成する

GitHubで新しいリポジトリを作成します。

推奨例：

```text
is-course-a
```

公開サイトとして使用する場合は、リポジトリをPublicにすると確認しやすくなります。

## 2. ファイルをアップロードする

このフォルダ内のファイルを、リポジトリの最上位へアップロードします。

重要：

```text
index.htmlがリポジトリ直下にある状態
```

フォルダごと一段深く入れないようにしてください。

正しい例：

```text
リポジトリ
├ index.html
├ course-basic.html
├ course-intermediate.html
└ course-advanced.html
```

避けたい例：

```text
リポジトリ
└ コースA_GitHub_Pages公開用
   └ index.html
```

## 3. GitHub Pagesを有効化する

リポジトリのSettingsからPagesを開き、次の構成で公開します。

```text
Branch：main
Folder：/ (root)
```

保存後、公開URLが表示されるまで少し待ちます。

## 4. 公開後の確認

次を確認してください。

- コース一覧が表示される
- 初級・中級・上級へ移動できる
- 左メニューが動く
- 検索・絞り込みが動く
- スマートフォンでも表示できる
- 解答例の表示・非表示が動く

## 更新方法

HTMLを変更した後、同じファイル名でGitHubへ上書きします。

主な更新対象：

```text
index.html
course-basic.html
course-intermediate.html
course-advanced.html
```

GitHub Pages側で更新が反映されるまで、少し時間がかかる場合があります。
