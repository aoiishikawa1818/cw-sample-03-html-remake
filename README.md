# cw-sample-03-html-remake

既存LP（HTML/CSS）をベースに、**テイスト変更＋構成調整（改修）**を行ったサンプルです。  
**Before / After を比較**できるように構成しています。

---

## Demo
- GitHub Pages：https://aoiishikawa1818.github.io/cw-sample-03-html-remake/
- Before：https://aoiishikawa1818.github.io/cw-sample-03-html-remake/before/
- After：https://aoiishikawa1818.github.io/cw-sample-03-html-remake/after/

---

## What I Improved（改修内容）
- Pricingセクションを **段階的に豪華**なカードデザインに改善（Starter → Standard → Pro）
- Proプランを最上位として強調（バッジ/装飾/CTA）
- タイポグラフィと余白の基準を統一し、読みやすさを改善
- コンポーネント（カード/ボタン/リスト）を共通化して保守性を向上
- レスポンシブ対応（PC / Tablet / SP）

---

## Folder Structure
```text
.
├── index.html          # 入口（Before/Afterへのリンク）
├── styles.css          # 入口用スタイル（任意）
├── before/
│   ├── index.html
│   └── styles.css
└── after/
    ├── index.html
    └── styles.css
```

---

## How to Run（ローカルでの確認）
### いちばん簡単
- `index.html` をブラウザで開くだけでOKです。

### 任意：簡易サーバーで開く
- Node.js がある場合：
```bash
npx serve .
```

---

## Notes
- `/before` は改修前の状態、`/after` は改修後の状態です。
- 入口ページ（ルート index.html）から比較できるようにしています。

---

## Tech Stack
- HTML
- CSS（バニラ）
- JavaScript（必要最小限 / ない場合もあり）
- VS Code / OpenAI Codex / GitHub Pages

---

## License
本プロジェクトは MIT ライセンスの下で公開されています。
