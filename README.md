# seto-blend-coffee-site


#　ディレクトリ構成
seto-blend-coffee-site/
├── app/
│   ├── about/
│   │   └── page.tsx
│   ├── brewing/
│   │   └── page.tsx
│   ├── faq/
│   │   └── page.tsx
│   ├── profile/
│   │   └── page.tsx
│   ├── purchase/
│   │   └── page.tsx
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   └── ui/
│       ├── accordion.tsx
│       ├── button.tsx
│       ├── card.tsx
│       ├── checkbox.tsx
│       ├── input.tsx
│       ├── label.tsx
│       ├── radio-group.tsx
│       ├── select.tsx
│       ├── tabs.tsx
│       └── textarea.tsx
├── public/
│   └── images/
│       ├── about-image-1.jpg
│       ├── about-image-2.jpg
│       ├── about-image-3.jpg
│       ├── brewing-drip-bag.jpg
│       ├── brewing-dripper.jpg
│       ├── brewing-grinder.jpg
│       ├── coffee-beans-closeup.jpg
│       ├── coffee-beans.jpg
│       ├── coffee-cup.jpg
│       ├── hero-background.jpg
│       ├── seto-brewing.jpg
│       ├── seto-blend-package.jpg
│       └── seto-profile.jpg
├── next.config.mjs
├── package.json
├── tailwind.config.js
└── tsconfig.json



# 技術スタック

### 使用言語とフレームワーク

- **言語**: TypeScript/JavaScript
- **フレームワーク**: Next.js (App Router)
- **スタイリング**: Tailwind CSS
- **UIコンポーネント**: shadcn/ui (Radixベースのコンポーネントライブラリ)


### 現在の設計進捗状況

#### フロントエンド設計の完了部分:

1. **ページ構造**: 以下の全ページのUI設計が完了しています

1. ホームページ (`app/page.tsx`)
2. 購入ページ (`app/purchase/page.tsx`)
3. コーヒーについてのページ (`app/about/page.tsx`)
4. 淹れ方ページ (`app/brewing/page.tsx`)
5. プロフィールページ (`app/profile/page.tsx`)
6. FAQページ (`app/faq/page.tsx`)



2. **レスポンシブデザイン**: モバイル、タブレット、デスクトップに対応したレスポンシブなレイアウト設計
3. **UI/UXコンポーネント**:

1. ナビゲーションヘッダー
2. フッター
3. 商品表示カード
4. フォーム要素（購入ページ、FAQ問い合わせフォーム）
5. タブインターフェース
6. アコーディオン（FAQ）
7. 画像ギャラリー



4. **スタイリング**:

1. カラーテーマ設定 (tailwind.config.js)
2. タイポグラフィ
3. アニメーション
4. レイアウト





#### 未実装/今後必要な部分:

1. **バックエンド連携**:

1. データベース接続 (MySQL等)
2. 商品データの動的取得
3. 注文処理のロジック



2. **決済システム**:

1. PayPay等の決済API連携
2. 決済フロー
3. 注文確認・完了画面



3. **認証システム**:

1. ユーザーログイン/登録機能
2. マイページ



4. **その他機能**:

1. 在庫管理
2. 注文履歴
3. 配送状況追跡


