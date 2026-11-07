# 私は人間？ (Am I Human?) 🤖🖐️

> **「私って人間かな？」**
> カーソルの手ぶれ、操作速度の揺らぎ、反射時間をリアルタイム解析し、自分がAIやBotではなく「人間であること」を証明・確認するWebアプリケーションです。

---

## ✨ 特徴 (Features)

- **リアルタイム行動バイオメトリクス解析**: マウスカーソルやタッチの微小な「手ぶれ」「加速度」「反応速度」を即座にスコア化。
- **インタラクティブな人間性確認ステップ**:
  - **Step 1:** 直感でタイルを選ぶ心理選択テスト
  - **Step 2:** 心拍のリズムを感じるハートタップ測定
- **人間証明書の交付**: 判定完了後、ユニークIDとスコアが記載されたグラフィカルな証明書を発行。
- **SNSシェア機能**: 結果をワンタップでX（旧Twitter）や各種SNS・アプリへスマートに共有。
- **モダンなUI/UX**: Tailwind CSS による洗練されたデザイン（ダークモード標準対応 / PWA対応）。

---

## 🚀 デモ (Demo)

実際にこちらからお試しいただけます：
👉 [https://human-check.sakudayo.com/](https://human-check.sakudayo.com/)

---

## 🛠️ 技術スタック (Tech Stack)

- **Frontend**: HTML5, JavaScript (ES6+), Tailwind CSS
- **Icons & Fonts**: FontAwesome 6, Google Fonts (M PLUS Rounded 1c)
- **Effects**: Canvas Confetti
- **PWA**: Web App Manifest, Service Worker (Offline Ready)

---

## 💻 使い方・開発手順 (Getting Started)

### 1. リポジトリのクローン
```bash
git clone https://github.com/YOUR_USERNAME/am-i-human.git
cd am-i-human
```

### 2. ファイル構成
```text
.
私は人間？/
├── Images/
│   ├── favicon.png       # アプリ・ファビコンアイコン
│   └── ogp.png           # OGP画像（SNSシェア用）
├── index.html            # メインアプリケーションファイル
├── manifest.json         # PWAマニフェストファイル
├── sw.js                 # サービスワーカー（オフライン・キャッシュ対応）
├── LICENSE               # ライセンスファイル (MIT)
└── README.md             # プロジェクト説明ドキュメント
```

### 3. ローカルでの実行
特殊なビルドツール（Node.js等）は不要です。
VS Codeの「Live Server」拡張機能などを使用するか、そのままブラウザで `index.html` を開いて動作確認を行ってください。

---

## 📄 ライセンス (License)

このプロジェクトは [MIT License](./LICENSE) のもとで公開されています。商用・非商用問わず、ご自由にご利用・改変いただけます。

---

## 👤 クレジット (Credits)

- **Powered by**: [Saku](https://link.sakudayo.com)
