## こんにちは、ウッタムです

清掃会社で品質管理を担当しながら、現場業務を改善するためのWebアプリ・自動化ツールを開発しています。

紙・Excel・手作業・属人化した連絡を、少しずつ「確認しやすい」「抜け漏れに気づける」「現場で使える」仕組みに置き換えています。将来的には、業務理解を強みにしたフルスタックエンジニアとして、完全リモートで働くことを目指しています。

---

## 現在取り組んでいること

- 清掃会社向けの予定通知・巡回管理・スケジュール管理システムの開発
- Python / Google Apps Script を使った日次・週次業務の自動化
- Next.js / TypeScript / Supabase を使った業務アプリ開発
- FastAPI / Docker / DB設計を含むバックエンド学習と実装
- 実務で使われるデータ構造を整理し、保守しやすいシステムへ移行すること

---

## 主なプロジェクト

### notifier

清掃現場の予定表をもとに、担当者へ前日に予定メールを自動送信するPythonツールです。

- Dropbox上の週間予定表Excelを読み込み
- 翌日の担当者・代行担当者を抽出
- GitHub Actions / Cloud Functions で定期実行できる構成へ移行
- 誤送信防止、dry-run、テスト送信、本番送信ガードを整備

実務で使うことを前提に、安定性・安全性・運用しやすさを重視して開発しています。

### schedule-manager

`notifier` の次世代版として開発している、清掃会社向けの予定管理システムです。

- Excel / Dropbox 依存から段階的に脱却するための設計
- Web UI から予定を編集できる構成を検討
- notifier と連携しやすいデータモデルを整理
- FastAPI / Next.js / Docker / SQLite からスタートし、将来的なPostgreSQL移行も想定

現場運用を壊さず、少しずつシステム化するための中心プロジェクトです。

### patrol-app

物件巡回の記録・管理をスマートフォンで行うためのWebアプリです。

- 担当者がスマホから巡回記録を入力
- 管理者が未巡回物件や担当者別状況を確認
- Googleログイン、Supabase、Vercelを使った構成
- Next.js / TypeScript でMVPを開発

「巡回したか分からない」「記録が残らない」という現場課題を解決するために作っています。

### cleaning-scheduler-demo

定期清掃の月間予定作成を支援するデモアプリです。

- 売上表・昨年実績・担当者情報をもとに月間予定を可視化
- 未配置物件、担当者変更、売上目標との差分を確認
- Next.js / TypeScript / Tailwind CSS / shadcn/ui でUIを構築
- 上司や予定作成担当者に共有しやすいデモとして作成

業務フローを画面に落とし込み、現場と管理側の判断を助けることを目的にしています。

---

## 技術スタック

### よく使う技術

- Frontend: HTML, CSS, JavaScript, TypeScript, React, Next.js
- Backend: Python, FastAPI, PHP
- Database / BaaS: SQLite, Supabase, PostgreSQL learning
- Automation: Google Apps Script, GitHub Actions, Cloud Functions
- Tools: Git, GitHub, Docker, VS Code, Vercel

### 学習・強化中

- 認証・権限管理
- REST API設計
- DB設計・マイグレーション
- テストとCI
- 本番運用を意識したログ・エラーハンドリング

---

## 公開リポジトリの方向性

現在のGitHubには、初期学習で作ったJavaScript / PHPの小さなアプリと、最近の業務改善システム開発が混在しています。

今後は、以下のように整理していきます。

- 実務課題をもとにした業務改善アプリを中心に見せる
- READMEに目的、課題、機能、技術構成、今後の改善点を書く
- デモURLやスクリーンショットを追加する
- 小さな学習リポジトリは、必要に応じて整理・非表示化する

---

## GitHubで見せたい強み

- 現場の課題を自分で見つけ、業務に合わせてツール化できること
- 清掃会社の品質管理・巡回・予定作成など、実務ドメインを理解していること
- Python自動化からWebアプリ開発まで、段階的にフルスタックへ広げていること
- 完璧なシステムを一気に作るのではなく、現場運用を止めずに改善できること

---

## これからやること

- `notifier` の運用安定化とドキュメント整備
- `schedule-manager` のMVP実装
- `patrol-app` の入力体験と管理画面の改善
- `cleaning-scheduler-demo` のデモ品質向上
- GitHubプロフィールと各READMEをポートフォリオとして整える

---

## Links

- GitHub: [PWuttam](https://github.com/PWuttam)
- Resume: [resume.id/uttam](https://www.resume.id/uttam)
- X: [@PWuttam](https://twitter.com/PWuttam)
