# 海外アフィリエイト運用チーム

Pinterest経由で海外向けアフィリエイトサイト・ブログを運用するための4人体制チームのフォルダ構成。
各メンバーの役割・使用プロンプト・連携フローを定義する。

## チーム体制

| # | 役割 | フォルダ | 主な成果物 |
|---|------|----------|------------|
| 1 | リサーチャー | [`01_researcher/`](01_researcher/role.md) | トレンド・キーワード・商品調査レポート |
| 2 | 英語ライター | [`02_english_writer/`](02_english_writer/role.md) | SEO記事、CTA、メール文 |
| 3 | Pinterestデザイナー | [`03_pinterest_designer/`](03_pinterest_designer/role.md) | Pin画像、ボード戦略、Pinコピー |
| 4 | 改善分析官 | [`04_improvement_analyst/`](04_improvement_analyst/role.md) | 分析レポート、改善施策、KPIダッシュボード |

共通ドキュメントは [`00_shared/`](00_shared/) にまとめている。

- [`00_shared/workflow.md`](00_shared/workflow.md) — 4人の連携フロー（週次サイクル図つき）
- [`00_shared/brand_guidelines.md`](00_shared/brand_guidelines.md) — トーン・NGワード・ブランド基準
- [`00_shared/kpi_definitions.md`](00_shared/kpi_definitions.md) — 共通KPIの定義
- [`00_shared/handoff_checklist.md`](00_shared/handoff_checklist.md) — 役割間の受け渡しチェックリスト

## フォルダ構成

```
overseas-affiliate-team/
├── README.md
├── 00_shared/
│   ├── workflow.md
│   ├── brand_guidelines.md
│   ├── kpi_definitions.md
│   └── handoff_checklist.md
├── 01_researcher/
│   ├── role.md
│   ├── prompts/
│   │   ├── trend_research.md
│   │   ├── keyword_research.md
│   │   ├── competitor_analysis.md
│   │   └── product_selection.md
│   └── templates/
│       └── research_report_template.md
├── 02_english_writer/
│   ├── role.md
│   ├── prompts/
│   │   ├── article_writing.md
│   │   ├── seo_optimization.md
│   │   ├── cta_writing.md
│   │   └── email_sequence.md
│   └── templates/
│       └── article_template.md
├── 03_pinterest_designer/
│   ├── role.md
│   ├── prompts/
│   │   ├── pin_design_brief.md
│   │   ├── pin_copy.md
│   │   ├── board_strategy.md
│   │   └── seasonal_campaign.md
│   └── templates/
│       └── pin_spec_sheet.md
└── 04_improvement_analyst/
    ├── role.md
    ├── prompts/
    │   ├── performance_analysis.md
    │   ├── ab_test_design.md
    │   ├── funnel_diagnosis.md
    │   └── weekly_report.md
    └── templates/
        └── kpi_dashboard_template.md
```

## 使い方

1. 各役割フォルダの `role.md` で担当範囲とアウトプット基準を確認する。
2. `prompts/` 内のプロンプトをそのままAI（Claude等）に投げて、成果物のドラフトを作る。
3. `00_shared/handoff_checklist.md` に沿って次の担当者へ受け渡す。
4. 週次サイクルは `00_shared/workflow.md` を参照。
