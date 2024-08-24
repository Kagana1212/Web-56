# Web-56

ローカルにクローン
```bash
git clone https://github.com/Kagana1212/Web-56.git
```

Dockerfileを使用して環境構築
```bash
docker compose up
```

SQL
```bash
docker compose exec mysql mysql kyototech
```

テーブル作成
```bash
CREATE TABLE `posts`(
    `text` TEXT NOT NULL,
    `created_at` DATETIME DEFAULT CURRENT_TIMESTAMP
);
```

localhost/formtodbtest.php　にアクセス

