# 浦川 和大 / Kazuo Urakawa

Webエンジニアを目指して学習・開発中です（テックキャンプ修了）。  
接客・飲食業での経験を経て、2024年からプログラミングを本格的に学習しています。

NaniKore (Rails) / laravel-memo-app (Laravel)｜学習・開発中

📍 Fukuoka, Japan

---

## Portfolio

### [NaniKore（ナニこれ？）](https://github.com/urakawakazuo0301/NaniKore)

家具・家電の付属品（ネジ・部品など）を写真で登録・検索できる管理Webアプリ。  
生活の課題を起点に、企画・設計・実装・本番デプロイまで一貫して開発しました。

| | |
|---|---|
| Demo | http://18.179.96.132 |
| GitHub | https://github.com/urakawakazuo0301/NaniKore |

**主な機能**
- 画像登録（最大3枚）・条件検索・使用済み／未使用管理
- ユーザー間アイテム共有（Pundit による権限制御）
- OpenAI GPT-4o Vision による AI 入力提案

**Tech Stack**

`Ruby on Rails 7` `MySQL` `JavaScript (Stimulus.js)` `Tailwind CSS`  
`Devise` `Pundit` `Active Storage` `AWS (EC2, S3)` `OpenAI API` `Capistrano`

※ デモ環境は Basic 認証あり

---

### [laravel-memo-app](https://github.com/urakawakazuo0301/laravel-memo-app)

Laravel で作成したメモ（Task）管理用の CRUD アプリケーションです。  
会員登録・ログイン後、自分のメモだけを作成・閲覧・編集・削除できます。

Rails での開発経験を活かし、Eloquent / Blade / 認証 / バリデーションなど、Laravel の基本構成を一通り実装し、AWS EC2 へデプロイしました。

| | |
|---|---|
| Demo | http://18.179.96.132:8080 |
| GitHub | https://github.com/urakawakazuo0301/laravel-memo-app |

**主な機能**
- ユーザー登録 / ログイン / ログアウト（Laravel Breeze）
- メモの一覧・作成・詳細・編集・削除（CRUD）
- ユーザーごとのデータ分離（`user_id` による紐づけ）
- バリデーションと日本語エラーメッセージ、フラッシュメッセージ

**Tech Stack**

`PHP 8.4` `Laravel` `SQLite` `Laravel Breeze` `Blade` `Tailwind CSS` `Vite`  
`AWS (EC2)` `Nginx` `PHP-FPM`

※ デモ用アカウントはアプリの README に記載しています

---

## Learning Projects（テックキャンプ）

| App | 内容 |
|-----|------|
| FirstApp | Rails MVC を意識したメモ投稿アプリ |
| PicTweet | CRUD + Gem を用いた写真投稿アプリ |
| ChatApp | 多対多 DB 設計 + Active Storage |
| AjaxApp | 非同期通信によるメモ投稿 |
| FURIMA | フリマアプリ（出品・購入など） |

---

## Contact

- GitHub: https://github.com/urakawakazuo0301
- X: https://x.com/UrAkAwAkAzUO
