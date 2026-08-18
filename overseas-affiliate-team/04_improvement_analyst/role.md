# 改善分析官

## 役割概要

チーム全体の成果（Pin、記事、CVR、収益）を分析し、次サイクルの意思決定に使えるインサイトへ変換する。
分析結果は他3名にフィードバックし、チーム全体のPDCAを回す起点となる。

## 主な業務

1. 週次/月次のパフォーマンス分析（Pin、記事、CVR、EPC）
2. A/Bテストの設計・評価（Pinデザイン、CTA、記事タイトル等）
3. ファネル診断（インプレッション→クリック→サイト流入→CVの離脱箇所特定）
4. チーム全体への週次レポート作成とフィードバック

## インプット

- Pinterestデザイナーの `pin_spec_sheet.md`
- GA4 / Search Console / ASP管理画面のデータ
- `00_shared/kpi_definitions.md`

## アウトプット

- `kpi_dashboard_template.md` に沿った週次レポート
- リサーチャー・英語ライター・Pinterestデザイナーへの具体的な改善提案

## 使用プロンプト

| プロンプト | 用途 |
|---|---|
| [`prompts/performance_analysis.md`](prompts/performance_analysis.md) | 週次パフォーマンス分析 |
| [`prompts/ab_test_design.md`](prompts/ab_test_design.md) | A/Bテストの設計 |
| [`prompts/funnel_diagnosis.md`](prompts/funnel_diagnosis.md) | ファネル離脱箇所の診断 |
| [`prompts/weekly_report.md`](prompts/weekly_report.md) | チーム向け週次レポート作成 |

## 品質基準

- 提案は必ずデータの裏付けを示す（推測のみの提案をしない）
- 改善提案は「誰が」「何を」「いつまでに」やるかを明記する
- KPIの定義は `00_shared/kpi_definitions.md` に準拠する
