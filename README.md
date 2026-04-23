# OKI BOWL 店長ツール

OKI BOWL 店長用の業務支援ツール（静的HTML）。

## 公開ページ
- 入口: https://[ユーザー名].github.io/okibowl-tools/
- 週次P/Lシート: https://[ユーザー名].github.io/okibowl-tools/pl.html
- 廃棄記録シート: https://[ユーザー名].github.io/okibowl-tools/waste.html

## 中身
| ファイル | 用途 |
|---|---|
| index.html | 入口ページ（2ツールへのリンク） |
| pl.html | 週次P/Lシート（売上・原価・人件費を入力してFL比率を自動計算） |
| waste.html | 廃棄記録シート（日次廃棄記録・月次ロス率自動計算） |

## データ保存
各ツールはブラウザの localStorage に保存。端末ごとに独立。
