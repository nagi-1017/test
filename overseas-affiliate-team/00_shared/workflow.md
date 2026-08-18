# 連携フロー（週次運用サイクル）

4人が下記の順番でバトンを渡す形で運用する。1サイクル = 1週間を想定。

```
[月] リサーチャー
   │  トレンド/キーワード/商品調査 → research_report を作成
   ▼
[火-水] 英語ライター
   │  research_report を元に記事執筆（SEO記事 + CTA）
   ▼
[水-木] Pinterestデザイナー
   │  記事内容からPin画像・コピーを作成し、記事と紐付けて投稿
   ▼
[金] 改善分析官
   │  先週分の指標（クリック率、CVR、Pinterest流入）を分析
   │  → 改善提案をリサーチャー/ライター/デザイナーへフィードバック
   ▼
(翌週の月に戻る。改善提案が次サイクルのリサーチ方針に反映される)
```

## 各受け渡しポイント

| From → To | 受け渡す成果物 | 参照テンプレート |
|---|---|---|
| リサーチャー → 英語ライター | 商品情報、ターゲットキーワード、競合記事の要点、想定読者像 | `01_researcher/templates/research_report_template.md` |
| 英語ライター → Pinterestデザイナー | 記事タイトル、要約、CTA文言、記事URL/公開予定日 | `02_english_writer/templates/article_template.md` |
| Pinterestデザイナー → 改善分析官 | Pin画像、投稿日、使用ボード、Pinコピー | `03_pinterest_designer/templates/pin_spec_sheet.md` |
| 改善分析官 → リサーチャー（次サイクル） | 好調/不調キーワード、CVR改善余地、次に狙うべきテーマ | `04_improvement_analyst/templates/kpi_dashboard_template.md` |

## 運用ルール

- 各役割は成果物を必ず `00_shared/handoff_checklist.md` のチェック項目を満たしてから次工程へ渡す。
- ブランドトーンは全員 `00_shared/brand_guidelines.md` に準拠する。
- KPIの定義・目標値は `00_shared/kpi_definitions.md` を単一の正とする（各自で定義を作らない）。
- 改善分析官のフィードバックは次サイクルのリサーチ着手前に必ず共有する（フローが逆流しないよう金曜中に完了させる）。
