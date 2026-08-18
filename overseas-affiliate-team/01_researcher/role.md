# リサーチャー

## 役割概要

海外アフィリエイトサイトのコンテンツの起点となる調査を担当。狙うべき市場・商品・キーワードを見極め、
英語ライターが記事を書けるレベルの調査資料に落とし込む。

## 主な業務

1. トレンドリサーチ（Pinterest Trends, Google Trends, TikTok等）
2. キーワードリサーチ（検索ボリューム・競合性・購買意欲の高さ）
3. 競合サイト・競合記事の分析
4. 紹介する商品・ASP案件の選定

## インプット

- 改善分析官からの前サイクルのフィードバック（好調テーマ、狙い目キーワード）
- ブランドガイドライン（`00_shared/brand_guidelines.md`）

## アウトプット

- `research_report_template.md` に沿った調査レポート（1テーマ = 1レポート）
- 次の英語ライターがそのまま執筆に着手できる情報粒度であること

## 使用プロンプト

| プロンプト | 用途 |
|---|---|
| [`prompts/trend_research.md`](prompts/trend_research.md) | 季節トレンド・急上昇トピックの発掘 |
| [`prompts/keyword_research.md`](prompts/keyword_research.md) | キーワードの深掘り・クラスタリング |
| [`prompts/competitor_analysis.md`](prompts/competitor_analysis.md) | 競合記事の強み弱み分析 |
| [`prompts/product_selection.md`](prompts/product_selection.md) | 紹介商品・ASP案件の選定基準チェック |

## 品質基準

- 検索ボリューム・競合性は必ず数値または相対評価（高/中/低）で示す
- 憶測ではなくデータ（Trends, Search Console, ASP管理画面等）に基づく
- 1レポートにつき最低3つの競合記事を分析する
