---
theme: canly-theme
_class: lead
paginate: true
marp: true
---

![bg contain](images/canly-back.png)

![canly-logo](images/canly-logo.png)

# 複数リポジトリ環境下の<br>バージョン管理システム<br>構築と運用

## めぐろ LT #28 <br>株式会社カンリー 角谷維

---

## 自己紹介

<style scoped>
.profile-section {
  position: relative;
}
.profile-image {
  position: absolute;
  right: 80px;
  top: 50%;
  transform: translateY(-50%);
}
</style>

<div class="profile-section">

### 🙋‍♂️ About Me

- **Name**: 角谷 維(すみや たもつ) / motsuo
- **Company**: 株式会社カンリー
- **Role**: web エンジニア / 一応フロントエンド
- **Hobbies**: 音楽 / ポーカー / 古着屋行く
- **Other**: switch2当たりました

<img src="images/motsuo.jpg" class="profile-image" style="height: 300px; border-radius: 10px;">

</div>

---

<!-- _class: subsection -->
<!-- paginate: false -->

# 弊社サービスの概要と背景

---

## 所属プロダクトの概要

### 🏠 カンリーホームページとは

- HP 来訪者の実店舗への来訪動線を**最適化するホームページ**
- クライアントは CMS としてページを管理
- header,footer を変更し、**サブドメイン**として運用

### 😭　対応しないといけないこと
- クライアントのホームページのheader,footerにデザインを合わせる必要がある
- その為、**複数のデザイン**を管理する必要があった

<!-- 画像を追加する　-->

## 困ったこと

### 個別対応が多すぎる！！！！
新しい機能を作りたくても、会社単位で全てのニーズに応えられず、
その会社専用の独自機能を増やすことに…

その会社だけバージョンが昔のコミットで止まってしまっていて、最新版に
追従できてないなどの問題も発生…

---

## 取り組んだことその1

### 👈 Case 1: コアリポジトリ化

- コアリポジトリとクライアントリポジトリを作成
- コアリポジトリへ新機能を追加する
- 各クライアントリポジトリはモジュール化された最新のコアリポジトリを取得する

- 全社共通の機能→コアリポジトリ
- header,footerなどの異なるデザイン、その会社のみの機能→クライアントリポジトリ

- **結果**: それぞれバージョン管理ができるようになった！

---

## しかし…

### クライアントリポジトリが20を超えてきたあたりで、リリース作業1日を要するように…

---

## 取り組んだこと

### 🔥 Case 2: 全リポジトリ自動デプロイ

- 

---

## 現在取り組んでいること

### Case 3: AIツールとの協業開発

- devin 
- cursor multi modal


---

<!-- _class: lead -->

# ご清聴ありがとう<br>ございました！

## 質問・相談はお気軽に 🙋‍♂️

**X**: @canly_motsuo
**GitHub**: github.com/motsuo373
