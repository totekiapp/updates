# updates

と的のソフトが「新しい版があるか」を確認するときに読むファイルを置いています。
ソフトごとに1つのファイルがあります。

| ファイル | ソフト |
|---|---|
| tsuzuring-studio.json | Tsuzuring Studio |
| manga-organizer.json | MangaOrganizer |

## ファイルの中身

```json
{
  "version": "1.0.0",
  "url": "https://（BOOTHの商品ページ）",
  "notes": "この版の短い説明"
}
```

- `version`：最新の版番号（数字3つ）
- `url`：ダウンロードできるページ。BOOTH のページだけが開けます。
- `notes`：お知らせに出す短い説明（300文字まで）

ソフトはこのファイルを読むだけで、利用者の情報は何も送りません。
