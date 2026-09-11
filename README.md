# UI Theme Studio (UIテーマシミュレーター) 🎨✨

ブラウザ単体で即座に動作する、高機能UIデザイントークン＆コンポーネント・シミュレーターです。  
外部サーバーやビルド環境不要で、配色・角丸・余白・シャドウのリアルタイム検証からCSS/JSONの書き出しまで完結します。iPhoneのホーム画面に追加してPWAとしても利用可能です。

---

## 🚀 主な機能

- **デザイントークン即時カスタマイズ**: プライマリ・サーフェス・テキストカラー、角丸、パディング、ボーダー幅、シャドウの調整
- **リアルタイム・コンポーネントプレビュー**: ボタン各種、入力フォーム、セレクトボックス、ステータスバッジ、インタラクティブカード
- **アクセシビリティ自動診断**: 背景と文字色のWCAGコントラスト比（AA / AAA基準）をリアルタイム判定
- **プリセット機能**: Modern / Cyber / Warm / Mono の4種をワンクリック切り替え
- **自動保存 (localStorage)**: ブラウザを閉じても設定したトークンを自動で保持
- **ワンクリック書き出し**:
  - CSSカスタムプロパティ (`:root`) のクリップボードコピー
  - `design-tokens.json` のダウンロード
- **PWA / モバイル対応**: iOS Safari の「ホーム画面に追加」でアドレスバーなしの全画面起動

---

## 🛠 技術スタック

- **Markup & Styling**: HTML5 / [Tailwind CSS (CDN)](https://tailwindcss.com/)
- **Interactivity**: [Alpine.js (CDN)](https://alpinejs.dev/)
- **Icons**: [Lucide Icons](https://lucide.dev/)
- **Persistence**: Web Storage API (`localStorage`)

---

## 📱 iPhoneでの利用方法 (PWA化)

1. iPhoneの **Safari** で本リポジトリのGitHub Pages公開URLを開きます。
2. 画面下部中央の **共有アイコン（四角から矢印）** をタップします。
3. リストから **「ホーム画面に追加」** を選択します。
4. ホーム画面に専用アイコンが生成され、ネイティブアプリ感覚でフルスクリーン起動できます。

---

## 📄 ライセンス

MIT License
