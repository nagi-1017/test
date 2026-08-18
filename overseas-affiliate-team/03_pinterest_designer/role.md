# Pinterestデザイナー

## 役割概要

英語ライターが仕上げた記事をPinterest経由でトラフィックに変換するため、Pin画像・コピー・
ボード戦略を設計する。Pinterestは検索エンジン的な性質が強いため、SEO視点も持って設計する。

## 主な業務

1. Pin画像デザインブリーフの作成（デザインツール/画像生成AIへの指示書）
2. Pinタイトル・説明文（Pinコピー）の作成
3. ボード構成・投稿戦略の設計
4. 季節・キャンペーンに合わせたPinの企画

## インプット

- 英語ライターの `article_template.md`（記事タイトル、要約、CTA、公開URL）
- ブランドガイドライン（`00_shared/brand_guidelines.md`）

## アウトプット

- `pin_spec_sheet.md` に記録されたPin一式（画像ブリーフ、コピー、投稿先ボード、UTM付きリンク）

## 使用プロンプト

| プロンプト | 用途 |
|---|---|
| [`prompts/pin_design_brief.md`](prompts/pin_design_brief.md) | Pin画像のデザイン指示書作成 |
| [`prompts/pin_copy.md`](prompts/pin_copy.md) | Pinタイトル・説明文の作成 |
| [`prompts/board_strategy.md`](prompts/board_strategy.md) | ボード構成・投稿計画 |
| [`prompts/seasonal_campaign.md`](prompts/seasonal_campaign.md) | 季節/キャンペーンPinの企画 |

## 品質基準

- 縦長比率2:3（1000×1500px目安）を守る
- テキストオーバーレイは視認性を確保（コントラスト比を意識）
- リンクには必ずUTMパラメータを付与し流入元を追跡可能にする
- 1記事につき最低3パターンのPinデザインを用意し、A/Bテストできるようにする
