高機能FX取引分析ツール - あなたの取引を可視化し、改善点を発見
🌟 特徴

✅ 完全ブラウザベース - インストール不要
✅ プライバシー重視 - データはローカル処理
✅ MT4/MT5対応 - 標準的な取引履歴フォーマットをサポート
✅ リアルタイム分析 - 即座に統計とチャートを生成
✅ レスポンシブデザイン - PC/タブレット/スマホ対応

🚀 デモ
ライブデモを見る
📦 使い方

取引プラットフォームから履歴をエクスポート（HTML/CSV）
ファイルをドラッグ&ドロップまたは選択
自動的に分析結果が表示

🛠️ 技術スタック

Frontend: Vanilla JavaScript (フレームワーク非依存)
Charts: Chart.js 3.9+
Styling: Custom CSS with CSS Variables
Hosting: GitHub Pages

📁 プロジェクト構造
fx-trading-analyzer/
├── index.html          # メインアプリケーション
├── app.js             # コアロジック
├── modules/           # 機能モジュール
│   ├── parser.js      # データパーサー
│   ├── analyzer.js    # 分析エンジン
│   ├── visualizer.js  # 可視化モジュール
│   └── exporter.js    # エクスポート機能
├── styles/            # スタイルシート
│   └── main.css      # メインスタイル
├── data/             # サンプルデータ
│   └── sample.json   # デモ用データ
└── docs/             # ドキュメント
    └── API.md        # 開発者向けAPI文書
🔧 開発環境セットアップ
bash# リポジトリをクローン
git clone https://github.com/LENS1208/fx-trading-analyzer.git
cd fx-trading-analyzer

# ローカルサーバー起動（Python）
python -m http.server 8000

# または Node.js
npx http-server

# ブラウザで開く
open http://localhost:8000
📈 現在の開発状況
✅ 実装済み機能

 ファイルアップロード（ドラッグ&ドロップ対応）
 基本統計（勝率、損益、PF）
 損益推移チャート
 取引履歴テーブル
 レスポンシブデザイン
 ローカルストレージ対応

🚧 開発中

 MT4/MT5 HTMLパーサー実装
 CSVパーサー実装
 時間帯別分析
 通貨ペア別分析
 曜日別分析

📋 今後の予定

 高度なフィルタリング機能
 カスタムインジケーター
 PDFレポート出力
 多言語対応（英語対応）
 ダークモード/ライトモード切替
 AI分析機能（実験的）

🤝 コントリビューション
プルリクエスト歓迎！

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request

📝 開発メモ
最新の更新（2024-01-20）

初期バージョンリリース
基本UI実装完了
サンプルデータ機能追加

次回の作業
javascript// TODO: MT4 HTMLパーサー実装
function parseMT4HTML(content) {
    // 実装予定
}
既知の問題

 Safari でのファイル読み込みが遅い
 大量データ（10000件以上）でパフォーマンス低下

📄 ライセンス
MIT License - 詳細は LICENSE を参照
🙏 謝辞

Chart.js チーム
MDN Web Docs
FXトレーダーコミュニティ

📞 お問い合わせ

GitHub Issues: 問題報告
Discussions: ディスカッション
