---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
headingDivider: 2
transition: fade
lang: ja
style: |
  @import url(https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css);
  
  section {
    font-family: 'Segoe UI', 'Hiragino Sans', 'Noto Sans CJK JP', sans-serif;
  }
  .lead {
    text-align: center;
  }
  .highlight {
    background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-weight: bold;
  }
  .feature-box {
    background: rgba(255, 255, 255, 0.9);
    border-radius: 15px;
    padding: 20px;
    margin: 10px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .feature-box:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
  }
  .keyboard-showcase {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 400px;
  }
  
  /* キーボードキーのアニメーション */
  @keyframes key-press {
    0% { transform: scale(1); }
    50% { transform: scale(0.95); background-color: #667eea; }
    100% { transform: scale(1); }
  }
  
  @keyframes rgb-glow {
    0% { box-shadow: 0 0 20px #ff6b6b; }
    25% { box-shadow: 0 0 20px #4ecdc4; }
    50% { box-shadow: 0 0 20px #ffd93d; }
    75% { box-shadow: 0 0 20px #6c5ce7; }
    100% { box-shadow: 0 0 20px #ff6b6b; }
  }
  
  @keyframes slide-in-left {
    from {
      opacity: 0;
      transform: translateX(-100px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }
  
  @keyframes slide-in-right {
    from {
      opacity: 0;
      transform: translateX(100px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }
  
  @keyframes bounce-in {
    0% {
      opacity: 0;
      transform: scale(0.3);
    }
    50% {
      opacity: 1;
      transform: scale(1.05);
    }
    70% {
      transform: scale(0.9);
    }
    100% {
      opacity: 1;
      transform: scale(1);
    }
  }
  
  @keyframes typing-effect {
    from { width: 0; }
    to { width: 100%; }
  }
  
  .typing-text {
    overflow: hidden;
    white-space: nowrap;
    border-right: 3px solid #667eea;
    animation: typing-effect 3s steps(30, end), blink-caret 0.5s step-end infinite alternate;
  }
  
  @keyframes blink-caret {
    50% { border-color: transparent; }
  }
  
  .rgb-animation {
    animation: rgb-glow 3s ease-in-out infinite;
    border-radius: 10px;
    padding: 10px;
  }
  
  .key-demo {
    display: inline-block;
    background: #f8f9fa;
    border: 1px solid #ddd;
    border-radius: 4px;
    padding: 8px 12px;
    margin: 2px;
    font-family: monospace;
    animation: key-press 2s ease-in-out infinite;
  }
---

<!-- _class: lead -->
<!-- _backgroundColor: linear-gradient(135deg, #667eea 0%, #764ba2 100%) -->
<!-- _color: white -->

![bg blur:2px opacity:0.7](https://images.unsplash.com/photo-1587829741301-dc798b83add3?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80)

<div class="animate__animated animate__fadeInDown animate__slow">

# <!--fit--> 🎹 **RobaKeyboard**

</div>

<div class="animate__animated animate__fadeInUp animate__delay-1s">

## <span class="typing-text">究極のタイピング体験への扉</span>

</div>

<div class="animate__animated animate__zoomIn animate__delay-2s">

### プレミアム機械式キーボードの新時代

</div>

---

<!-- _header: 'RobaKeyboard プレゼンテーション' -->
<!-- _footer: '© 2024 RobaKeyboard | 革新的なタイピング体験' -->

![bg left:40%](https://images.unsplash.com/photo-1541140532154-b024d705b90a?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80)

<div class="animate__animated animate__slideInLeft">

# 🚀 **なぜRobaKeyboardなのか？**

</div>

<div class="feature-box animate__animated animate__bounceIn animate__delay-1s">

## ✨ **革新的な特徴**

<div class="animate__animated animate__fadeInUp animate__delay-2s">

- 🔧 **カスタマイズ性**: 完全プログラマブル
- ⚡ **高速応答**: 0.1ms遅延

</div>

<div class="animate__animated animate__fadeInUp animate__delay-3s">

- 🎨 **RGB照明**: 1680万色対応
- 🔋 **長時間駆動**: 最大200時間

</div>

</div>

---

# 🎯 **ターゲットユーザー**

![bg right:30%](https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

## 👨‍💻 **プログラマー**
- 長時間のコーディングに最適
- ショートカット機能が豊富

## 🎮 **ゲーマー**
- 高速レスポンス
- アンチゴースト機能

## ✍️ **ライター**
- 快適なタイピング感
- 静音設計オプション

---

<!-- _class: invert -->
<!-- _transition: slide -->

![bg](https://images.unsplash.com/photo-1588508065123-287b28e013da?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)

<div class="animate__animated animate__pulse animate__infinite">

# <!--fit--> 🔥 **主要機能**

</div>

---

![bg left:50% contain](https://images.unsplash.com/photo-1587829741301-dc798b83add3?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80)

<div class="animate__animated animate__fadeInRight">

## 🎛️ **完全カスタマイズ可能**

</div>

<div class="animate__animated animate__slideInRight animate__delay-1s">

### **ハードウェア**
- ホットスワップ対応スイッチ
- 交換可能なキーキャップ
- 調整可能な角度設定

</div>

<div class="animate__animated animate__slideInRight animate__delay-2s">

### **ソフトウェア**
- 専用カスタマイズアプリ
- マクロ機能
- レイヤー設定

</div>

---

<!-- _transition: cover -->

<div class="animate__animated animate__bounceIn">

# 🖥️ **キーボード体験デモ**

</div>

<div style="text-align: center; margin: 50px 0;">

<div class="animate__animated animate__fadeInUp animate__delay-1s">

### **実際のタイピング感覚を体験してみてください**

</div>

<div class="animate__animated animate__zoomIn animate__delay-2s" style="margin: 30px 0; font-size: 1.2em;">

<span class="key-demo">Q</span>
<span class="key-demo">W</span>
<span class="key-demo">E</span>
<span class="key-demo">R</span>
<span class="key-demo">T</span>
<span class="key-demo">Y</span>

</div>

<div class="animate__animated animate__zoomIn animate__delay-3s" style="margin: 30px 0; font-size: 1.2em;">

<span class="key-demo">A</span>
<span class="key-demo">S</span>
<span class="key-demo">D</span>
<span class="key-demo">F</span>
<span class="key-demo">G</span>
<span class="key-demo">H</span>

</div>

<div class="animate__animated animate__bounceIn animate__delay-4s rgb-animation" style="margin-top: 40px;">

**各キーが個別にRGB照明で光ります！**

</div>

</div>

---

<div class="animate__animated animate__slideInDown">

## 🌈 **RGB ライティングシステム**

</div>

![bg right:40%](https://images.unsplash.com/photo-1518642499999-1e45d6c5de6c?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

<div class="rgb-animation">

### **多彩なエフェクト**

<div class="animate__animated animate__fadeInLeft animate__delay-1s">

- 🌊 **ウェーブ**: 波のように流れる光
- 🌟 **スター**: キラキラ光るエフェクト

</div>

<div class="animate__animated animate__fadeInLeft animate__delay-2s">

- 🔥 **ファイア**: 炎のような動的照明
- 🌀 **スパイラル**: 渦巻き状の光の動き

</div>

</div>

<div class="animate__animated animate__bounceInRight animate__delay-3s">

### **シーン別設定**
- 🌅 **朝**: 暖色系で目に優しく
- 🌙 **夜**: 青系で集中力アップ
- 🎮 **ゲーム**: 激しいアニメーション

</div>

---

<!-- _backgroundColor: #f8f9fa -->

![bg vertical right:30%](https://images.unsplash.com/photo-1606618808829-82fe2c60ad1d?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80)
![bg](https://images.unsplash.com/photo-1517077304055-6e89abbf09b0?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80)

# ⚡ **パフォーマンス仕様**

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">

<div class="feature-box">

## 🔢 **技術仕様**
- **応答速度**: < 0.1ms
- **キー配列**: 104キー（日本語配列）
- **接続**: USB-C / Bluetooth 5.0
- **バッテリー**: 4000mAh

</div>

<div class="feature-box">

## 🏆 **品質保証**
- **耐久性**: 5000万回キーストローク
- **保証期間**: 3年間
- **防水規格**: IPX4対応
- **認証**: CE, FCC, IC適合

</div>

</div>

---

<!-- _transition: zoom -->

<div class="animate__animated animate__slideInDown">

# 💰 **価格とパッケージ**

</div>

![bg blur:3px opacity:0.3](https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 30px; margin-top: 50px;">

<div class="feature-box animate__animated animate__bounceInLeft animate__delay-1s" style="text-align: center;">

## 🥉 **スタンダード**
### ¥19,800
- 基本RGB照明
- USB接続のみ
- 1年保証

</div>

<div class="feature-box animate__animated animate__bounceInUp animate__delay-2s" style="text-align: center; background: linear-gradient(45deg, #ff9a9e, #fecfef);">

<div class="rgb-animation">

## 🥈 **プロ** *おすすめ!*
### ¥29,800
- フル機能RGB
- USB + Bluetooth
- 2年保証

</div>

</div>

<div class="feature-box animate__animated animate__bounceInRight animate__delay-3s" style="text-align: center;">

## 🥇 **プレミアム**
### ¥39,800
- 全機能 + 限定色
- 専用ケース付属
- 3年保証

</div>

</div>

---

<!-- _class: invert -->

![bg](https://images.unsplash.com/photo-1515879218367-8466d910aaa4?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)

# 📝 **ユーザーレビュー**

---

![bg left:30%](https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80)

## 🌟 **満足度 4.8/5.0**

### **プログラマー Aさん**
> 「1日10時間以上使用していますが、手首が疲れません。カスタマイズ性も抜群で、作業効率が30%向上しました！」

### **ゲーマー Bさん**  
> 「レスポンスが本当に早くて、ゲームでのパフォーマンスが劇的に改善。RGB照明も美しくて、配信映えします。」

### **ライター Cさん**
> 「タイピング音が心地よく、長時間の執筆作業が楽しくなりました。静音モードも完璧です。」

---

# 🛒 **今すぐ購入**

![bg right:40%](https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80)

<div class="feature-box" style="text-align: center; background: linear-gradient(45deg, #667eea, #764ba2); color: white;">

## 🎁 **限定キャンペーン**
### 今なら**20% OFF**

**期間限定**: 2024年8月31日まで

**特典**: 
- 送料無料
- 専用クリーニングキット付属
- 30日間返品保証

</div>

### 📞 **お問い合わせ**
- 🌐 **Website**: robakeyboard.com
- 📧 **Email**: info@robakeyboard.com
- 📱 **TEL**: 0120-123-456

---

<!-- _class: lead -->
<!-- _backgroundColor: linear-gradient(135deg, #667eea 0%, #764ba2 100%) -->
<!-- _color: white -->

![bg blur:2px opacity:0.6](https://images.unsplash.com/photo-1587829741301-dc798b83add3?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)

<div class="animate__animated animate__bounceInDown animate__slow">

# <!--fit--> 🎉 **ありがとうございました**

</div>

<div class="animate__animated animate__fadeInUp animate__delay-1s">

## <span class="highlight rgb-animation">RobaKeyboard</span>

</div>

<div class="animate__animated animate__zoomIn animate__delay-2s">

### <span class="typing-text">あなたのタイピング体験を革新します</span>

</div>

<div class="animate__animated animate__pulse animate__delay-3s animate__infinite">

**質問・デモのご依頼はお気軽に！**

</div>

---

<!-- _class: lead -->
<!-- _paginate: false -->

# 📋 **付録: 技術仕様詳細**

<div style="font-size: 0.8em; text-align: left;">

### **ハードウェア仕様**
- **寸法**: 440 × 135 × 35 mm
- **重量**: 1.2 kg
- **材質**: アルミニウム合金フレーム
- **キースイッチ**: Cherry MX Compatible
- **キーキャップ**: PBT製、サブリメーション印刷

### **ソフトウェア機能**
- **対応OS**: Windows 10/11, macOS 10.15+, Linux
- **カスタマイズソフト**: RobaConfig (無料)
- **ファームウェア**: アップデート対応
- **プロファイル**: 最大10個保存可能

</div>
