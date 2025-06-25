# このリポジトリについて

このリポジトリは、私個人のプレゼンテーション資料を管理するためのものです。[Marp (Markdown Presentation Ecosystem)](https://marp.app/)を使用して Markdown からスライドを生成しています。
また、所属企業のプレゼンテーション資料用のスタイルも含まれています。
Marp のスタイルシートは私が個人的に作成したものですが、デザインシステムの知的財産権は株式会社カンリーに帰属します。
なお、このスタイルシートを使用して発生したいかなる問題についても、作成者である私は一切の責任を負いかねますのでご了承ください。

## 基本的な利用方法

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
├── README.md                   # このファイル
├── themes/
│   └── canly-theme.css        # Canlyオリジナルテーマ
├── .vscode/
│   └── settings.json          # VS Code設定（テーマ認識用）
└── src/
    └── 200624/               # 日付別のプレゼン資料
        ├── images/           # 画像ファイル
        │   ├── canly-back.png    # タイトル背景画像
        │   └── canly-logo.png    # ロゴ画像
        └── version-up-meguro-lt.md # プレゼンファイル
```

## Canly オリジナルテーマ

### テーマの特徴

- **カラーパレット**: 青を基調とした統一されたデザイン
- **フォント**: Hiragino Sans で統一
- **ヘッダーデザイン**: 青いグラデーションバーとドットパターン
- **タイトルスライド**: 背景画像とロゴ表示対応

### 必要な画像ファイル

プレゼンテーションで使用する画像ファイルは `src/YYMMDD/images/` ディレクトリに配置してください：

- **canly-back.png**: タイトルスライドの背景画像
- **canly-logo.png**: タイトルスライド左上に表示されるロゴ

### テーマの使用方法

Markdown ファイルのフロントマターで以下のように指定：

```markdown
---
theme: canly-theme
_class: lead # タイトルスライドの場合
paginate: true
marp: true
---

![bg contain](images/canly-back.png)
![canly-logo](images/canly-logo.png)

# タイトル

## サブタイトル
```

## 参考リンク

- [Marp 公式サイト](https://marp.app/)
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [Marp CLI](https://github.com/marp-team/marp-cli)
- [Marpit Framework](https://marpit.marp.app/)

## ライセンス

このリポジトリの内容は個人的な使用のためのものです。Marp ツール自体は MIT ライセンスで提供されています。
