# プレゼンテーション資料

このリポジトリは、私個人のプレゼンテーション資料を管理するためのものです。[Marp (Markdown Presentation Ecosystem)](https://marp.app/)を使用して Markdown からスライドを作成しています。

## Marp について

Marp（Markdown Presentation Ecosystem）は、Markdown を使って美しいスライドデッキを作成するためのツールセットです。直感的な Markdown 記述でプレゼンテーション資料を作成でき、ストーリーの執筆に集中できます。

### 主な特徴

- **CommonMark ベース**: 既存の Markdown 知識をそのまま活用
- **シンプルな構文**: `---` でページを区切るだけ
- **豊富なテーマ**: default、gaia、uncover の 3 つのビルトインテーマ
- **多様な出力形式**: HTML、PDF、PowerPoint に対応
- **拡張性**: ディレクティブや拡張構文をサポート
- **CSS カスタマイズ**: 独自のテーマ作成が可能

## 基本的な使い方

### 1. 基本構文

```markdown
---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---

# スライドタイトル

内容をここに記述

---

# 次のスライド

別の内容

---
```

### 2. ツールの使用

#### VS Code 拡張機能

- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)をインストール
- Markdown ファイルをリアルタイムプレビュー

#### CLI ツール

```bash
# インストール
npm install -g @marp-team/marp-cli

# HTML出力
marp presentation.md

# PDF出力
marp presentation.md --pdf

# PowerPoint出力
marp presentation.md --pptx
```

## ディレクトリ構造

```
presentation-marp/
├── README.md           # このファイル
└── src/
    └── 200624/        # 日付別のプレゼン資料
```

## 参考リンク

- [Marp 公式サイト](https://marp.app/)
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [Marp CLI](https://github.com/marp-team/marp-cli)
- [Marpit Framework](https://marpit.marp.app/)

## ライセンス

このリポジトリの内容は個人的な使用のためのものです。Marp ツール自体は MIT ライセンスで提供されています。
