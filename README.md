# raughmemo-lp

iPad向け創作ラフ整理アプリ「ラフめも」(RaughMemo)のWebサイト。

- 公開URL: https://raughmemo.zoelab.jp/
- ホスティング: GitHub Pages(mainブランチ / ルート)+ カスタムドメイン(`CNAME`ファイル)
- アプリ本体のリポジトリ: [kz-sue/rough_memo-swift](https://github.com/kz-sue/rough_memo-swift)(プライベート)

## 構成

| パス | 内容 |
|------|------|
| `/` | アプリLP(現在は開発中の告知のみ。デザインは今後作成) |
| `/privacy/` | プライバシーポリシー(準備中。App Store Connect提出用URL) |
| `/support/` | お問い合わせ(準備中) |

素のHTML+共通`style.css`のみ(ジェネレータ不使用)。テーマカラーはアプリと同じ `#2F706A`。

## デプロイ

mainブランチにpushすると自動で公開される。DNSは `raughmemo.zoelab.jp` → `kz-sue.github.io` のCNAMEレコード。
