# AI Orchestration｜複数AIを活用したデリバリー

[English](../en/ai-orchestration.md) | [日本語](./ai-orchestration.md) ・ [ポートフォリオTOP](../../README.ja.md)

## 開発プロセスの設計

**AIの価値は、生成したコードの量だけでなく、実装・レビュー・改善を効率的に組み合わせられることにある。**

「えきよみ」では、Claude CodeとCodexを異なる役割に配置し、GitHubを変更管理のハブとして使用しました。

## 役割分担

| 役割 | 担当 | 実務上の価値 |
| --- | --- | --- |
| Product Direction | Human / Product Lead | ニーズと仕様、優先順位、UX方針を決定 |
| Implementation | Claude Code | コード実装、修正、ドキュメント整備 |
| Independent Review | Codex | 別視点から品質とUXの改善事項を抽出 |
| Change Management | GitHub | Pull Request、変更差分、確認結果を管理 |
| Final Decision | Human / Product Lead | 提案の採否、デザイントレードオフ、リリース判断 |

## レビューから改修へ

Codexによるレビューで抽出した10項目の改善事項を、Claude Codeによる修正へ接続しました。

- 保護者向け共有導線の制御
- アクセシビリティ、キーボード操作、視認性
- 路線情報・収録区間の正確性
- iOSのReleaseビルドに関する確認

重要なのは、**AIの指摘を実装可能な作業として整理し、改修・確認・変更管理まで一連のプロセスにすること**です。

[品質改善のケーススタディ](./quality-management.md)

## Human-in-the-loop

AIからの提案をそのまま採用するのではなく、対象ユーザー、UX、ブランド表現との整合性で評価しました。例えば文字の視認性と絵本らしい表現が競合する際には、対象箇所ごとに改善の範囲を判断する必要があります。

## この事例で示す能力

**Multi-AI Orchestration / Project & Delivery Management / Quality Governance / Product Judgment / Requirements Translation**

AIを単発の便利ツールとして利用するだけでなく、**人間が方向性を定め、複数AIの成果物を統合してプロダクトを完成させる**ための実行モデルです。

[ポートフォリオTOPへ](../../README.ja.md)
