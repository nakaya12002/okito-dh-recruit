# おきとう歯科クリニック｜歯科衛生士 採用ガイド（スマホ版）

`https://okitodental.com/recruit` に iframe で全画面埋め込みするための静的サイト。

- 公開URL: https://nakaya12002.github.io/okito-dh-recruit/
- 入口は okitodental.com/recruit のみ。このURLは `noindex` で検索に載せない。

## 更新のしかた

正本は private リポジトリ `nakaya12002/okito-automation` の
`src/squarespace/dh-recruit/`。そちらを直してから、このリポジトリに
`index.html` と `assets/` をコピーして push する。

写真は長辺1600px・JPEG品質82に圧縮済み（合計約2MB）。
元の高解像度は okito-automation 側の履歴にある。

## なぜ別リポジトリなのか

`okito-automation` は private で、GitHub Free プランでは private リポジトリの
GitHub Pages が使えない（API が `422 Your current plan does not support
GitHub Pages for this repository` を返す）。院内自動化コードを public にする
わけにはいかないので、公開して問題ない採用ページだけを切り出した。
