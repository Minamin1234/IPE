# IPE(Image Processing Exercise)
## 概要
授業「画像処理演習」用の環境をまとめたプロジェクトのリポジトリ

## 環境構築
- 参考
https://qiita.com/toshi_machine/items/908e9be57e8afa629159

`$ brew install cmake`

`$ brew install opencv`

## プロジェクトの追加
本フォルダに移動しているのを確認後(`new_project.sh`があるフォルダ)以下のスクリプトを実行する。

`$ ./new_project.sh [プロジェクト名]`

- `Test1`というプロジェクト名で作成する例<br>
`$ ./new_project.sh Test1`

## ビルドと実行
実行したプロジェクトに移動してから、`run.sh`を実行する。

`$ cd Test1`

`$ ./run.sh`