# Github Actions お試し用リポジトリ

## 必要なアクション整理

- feature/hogeブランチがdevにmergeされた時、stg、 main(prd)へのPRを作成する
- main(prd)にmergeされた時(mainが更新された時)、mainをdev, stgにmergeするためのPRを作成する
- test
