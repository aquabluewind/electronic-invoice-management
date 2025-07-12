# 電子帳簿保存法対応請求書管理システム

AI OCR技術を活用した次世代型請求書管理システム

## 🚀 主な機能

- **AI OCR文書解析** - OpenAI Vision APIによる高精度テキスト抽出
- **電子帳簿保存法完全準拠** - 法的要件を満たした安全な文書保存
- **分類管理** - 経費、仕入、売上、その他の自動分類
- **監査証跡** - 完全な操作履歴とハッシュ値による完全性チェック
- **検索機能** - 請求書番号、会社名、日付による高速検索

## 📋 システム要件

- Node.js 18以上
- PostgreSQL 14以上
- OpenAI API キー（各自で取得が必要）

## 🔧 インストール

```bash
# リポジトリをクローン
git clone https://github.com/aquabluewind/electronic-invoice-management.git
cd electronic-invoice-management

# 依存関係をインストール
npm install

# 環境変数を設定
cp .env.example .env
# .envファイルを編集してAPIキーを設定

# データベースを設定
npm run db:push

# アプリケーションを開始
npm run dev
