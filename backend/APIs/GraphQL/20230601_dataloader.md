# Dataloader

## 概要

ある Data source へのアクセス回数を少なくするための技術。

- Batching : 取得処理をまとめる
- Caching : 取得結果を一時的に保存する

## 詳細

### Batching

Batching function を用意し、Caching するための Map を実装する。<br>
複数の値をまとめて取得することで、N+1 を避けることができる。Django の prefetch と同じ。

- ? load するタイミングでとるのか、それとも値を参照するタイミングでとるのか？

### Caching

簡単な Key-value を用意する。寿命はリクエスト単位が妥当だが、適当に変更することができる。<br>
キャッシングアルゴリズムも自分で実装することができる。

## Refs

- DataLoader – Source code walkthrough https://www.youtube.com/watch?v=OQTnXNCDywA
- 最適化されたデータの取得をしてくれるDataloaderの仕組みを調べてみた https://blog.potproject.net/2021/02/26/dataloader-architecture
