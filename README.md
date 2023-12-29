# セットアップ手順
- `git clone git@github.com:kumaryoya/movie_app.git`
- `cd movie_app`
- `git submodule update --init --recursive`
- `docker-compose up -d --build`
- `docker-compose exec back rails db:prepare`

# 使用技術
| カテゴリ | 技術 |
| :- | :- |
| バックエンド | Ruby 3.2.2 / Ruby on Rails 7.0.8 |
| フロントエンド | TypeScript 4.9.5 / React 18.2.0 |
| データベース | PostgreSQL |
| 環境構築 | Docker |
| インフラ | Render / Vercel |
| API | TMDB API |
