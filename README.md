# 売上管理アプリ
前年比との比較を行いながら売り上げを管理できるアプリです。

## アプリ概要
例：Next.jsとSupabaseを用いた売上管理アプリです。  


## サイトイメージ


![トップ画面](https://github.com/user-attachments/assets/98c17db6-663d-4015-b437-e0168f594548?raw=true)
)

## サイトURL

 
https://sale-date.vercel.app/


## 使用技術
- フロントエンド：Next.js 15、TypeScript、CSS、React
- データベース：Supabase
- デプロイ：Vercel
- バージョン管理：Git、GitHub
- テスト・デバッグ：DevTools（Chrome）
- CI/CD：GitHub Actions（ESLint）

※箇条書きは「-」のあとに空白を入れて本文を始めることで可能です。

## 設計ドキュメント
[要件定義・基本設計・詳細設計の一覧_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1CoIp7VZV6jDrFn8dmfXSO_Z-D9Jl9h1MHFOEamUtgF0/edit?gid=74722085#gid=74722085)

詳細設計時のワイヤーフレーム、ER図、ワークフロー図の画像はdocsディレクトリに格納しています。（[こちらからアクセス](./docs)）

※[]の中に表示文を書き、その後ろで()の中にURLを入れればハイパーリンク化できます。

## 機能一覧
- AI分析機能
- スプレッドシート連携
- スプレッドシートをもとにグラフ表示
  

※空白を2つ開けて「-」から始めることで、箇条書きが2段目になります。三段目は空白を4つ開ければ可能です。

## テスト・修正の設計及び実施書
[テスト・修正の設計及び実施書_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1rWvaOrAMTWzrE417upAoPYwHKzlZRcXQB5-JvqQnXgE/edit?gid=799863560#gid=799863560)

## アプリの改善案
[アプリの改善案_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1fgynpBKhx8zaNkMweeYVQl52bP6Z8dJZOmmY8MHXjQM/edit?usp=sharing)

## 備考
[ESLintの実行結果_GitHub Actions](https://github.com/aihat9161/PortfolioExample_Next.js_BlogAppWorX_ENGINEER-CLASS/actions/runs/14956271682/job/42012343864)

- 活用した生成AIとその用途
  - ChatGPT,claude：要件定義、設計、各種リサーチ
  - v0：アプリのモック作成
  - GitHub Copilot Chat：ローカル環境でのコードの修正相談

- リファクタリングの規則
  - 2つ以上のファイルで使う、行数が10以上のUIコンポーネントはcomponentsフォルダに移行
  - 2つ以上のファイルで使う、行数が10以上の関数はlibフォルダに移行
  - 変数名で2つ以上の単語が入る場合は、「isPublished」のように二つ目以降の単語の頭を大文字とする
