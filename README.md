# コースA HTML閲覧版

初級・中級・上級の研修教材を、ブラウザで閲覧できる静的HTMLサイトです。

## 公開ページ

- `index.html`：コース一覧
- `course-basic.html`：初級
- `course-intermediate.html`：中級
- `course-advanced.html`：上級

上級コースには、第0章「研修環境へのログインとSharePoint基本操作」を含みます。

## GitHub Pagesでの公開方法

1. GitHubで新しいリポジトリを作成します。
2. このフォルダ内のファイルを、リポジトリの最上位へアップロードします。
3. リポジトリの **Settings** を開きます。
4. **Pages** を開きます。
5. 公開元をブランチからの公開に設定します。
6. ブランチを `main`、フォルダを `/ (root)` にして保存します。
7. 公開処理の完了後、表示されたURLを開きます。

## ローカルでの確認

`index.html`をダブルクリックすると、GitHubへ公開する前でも閲覧できます。

## 構成

```text
.
├─ index.html
├─ course-basic.html
├─ course-intermediate.html
├─ course-advanced.html
├─ 404.html
├─ .nojekyll
├─ README.md
└─ 構造チェック結果.md
```

## 主な機能

- 教材全文検索
- 単元・教材の折りたたみ
- 教材種別による絞り込み
- 解答例の表示・非表示
- 確認済みチェック
- ブラウザ内への進捗保存
- 印刷
- スマートフォン表示対応

## 注意

確認済みの進捗は、閲覧者のブラウザ内に保存されます。  
別端末や別ブラウザには引き継がれません。
