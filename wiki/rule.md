# 運用ルール
気づいた頃に以下項目を適用していく。

- [CHANGELOG.md](https://github.com/lalitkapoor/github-changes)
- [README_ja.md](https://one-it-thing.com/4610/)

## README_en.mdの作り方
`cat README.md | trans ja:en -b -no-autocorrect` で作成。
<br>→これをやるとAPI制限に引っかかって二時間ぐらいは出力が空白になるので、`translate.sh`を実行することで問題を回避する。

`git commit`にフックさせてもいいかもしれない。

## CHANGELOG
運用が決まっていないのでコミットメッセージも任意。`README.md`以外は、Webから更新することを想定。
