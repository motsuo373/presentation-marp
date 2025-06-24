---
theme: blue-original
_class: lead
paginate: true
marp: true
---

# 複数リポジトリの<br>バージョン管理システムと<br>過去の失敗

## Meguro.lt - Lightning Talk

---

## 自己紹介

### 🙋‍♂️ About Me

- **Name**: [Your Name]
- **Role**: Software Engineer / Developer
- **Experience**: 複数プロジェクトでのバージョン管理に苦労中
- **Interest**: DevOps, CI/CD, Developer Experience

### 今日お話しすること

複数リポジトリを管理する際のバージョン管理の課題と、実際に遭遇した失敗事例について

---

## 問題の背景

### 🤔 なぜ複数リポジトリが必要？

- **マイクロサービス化**の進展
- **チーム分割**によるリポジトリ分離
- **言語・技術スタック**の違い
- **デプロイサイクル**の独立性

### よくある構成例

```
frontend/     → React App
backend-api/  → REST API
backend-job/  → Batch Jobs
infra/        → Terraform
```

---

## 実際に遭遇した失敗事例

### 😱 Case 1: 依存関係の地獄

- API のバージョンアップ時にフロントエンドが追従できず
- 本番環境で互換性のないバージョンの組み合わせをデプロイ
- **結果**: サービス停止 3 時間

### 🔥 Case 2: リリースタイミングのズレ

- 複数チームの調整不足
- 機能追加の片方だけがリリースされる
- **結果**: 不完全な機能が本番に露出

---

## まとめ

### 🎯 学んだこと

- **コミュニケーション**が最重要
- **自動化**できる部分は徹底的に自動化
- **モニタリング**と**ロールバック戦略**は必須
- **段階的リリース**の仕組み作り

### 次回予告

具体的な解決策とツールの選定について詳しくお話しします！

---

<!-- _class: lead -->

# ご清聴ありがとう<br>ございました！

## 質問・相談はお気軽に 🙋‍♂️

**Twitter**: @your_twitter  
**GitHub**: github.com/your_github  
**Email**: your.email@example.com
