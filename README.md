# 製品比較表プロジェクト

このプロジェクトは、Dockerを使用して実装された製品比較表のHTMLページです。

## 使用方法

1. Dockerをインストールしてください。
2. このリポジトリをクローンします。
3. プロジェクトのルートディレクトリで以下のコマンドを実行します：

docker build -t product-comparison-table .
docker run -p 8080:80 product-comparison-table

4. ブラウザで `http://localhost:8080` にアクセスして比較表を表示します。