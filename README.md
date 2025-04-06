# wordpress_sandbox

WordPressのシステムを触るためのサンドボックスです

## 使い方

* リポジトリをクローン

```
git clone https://github.com/Hietan/wordpress_sandbox/
```

* Dockerをビルド＆起動

```
docker compose up --build
```

* ページにアクセス

http://localhost:8000

> [!NOTE]
> アクセス時に，`Error establishing a database connection` が出る場合は，データベースがまだ起動中のため，
> 時間を置いてからブラウザをリロードしてください．
