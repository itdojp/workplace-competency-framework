# 初期移管の範囲と検査

移管日：2026-09-24。[初期登録PR #1](https://github.com/itdojp/workplace-competency-framework/pull/1)で移管し、[マージコミット](https://github.com/itdojp/workplace-competency-framework/commit/27b2edaf1255a8c07266e31a0c0733e3f353a1c2)に記録されています。公開用の個人データを含まないテキストだけを選択しました。

この文書は過去の移管の記録です。以下のv0.1/v0.2は公開前の試作資産の版を表し、利用者が入手する必要はありません。利用・改訂の正本は表のリンク先です。過去の会話添付、元ブック、配布パッケージは公開リポジトリに含まれず、教材の実行前提にしません。

| 元資産 | 公開先 | 処理 |
|---|---|---|
| v0.1 能力体系ブックの能力マスタ | [framework/competencies.csv](../../framework/competencies.csv) | A4:J40を値として移管 |
| v0.1 行動基準 | [framework/behavioral-anchors.csv](../../framework/behavioral-anchors.csv) | A4:I40を値として移管 |
| v0.1 診断・ワーク設計 | [assessment/design/diagnostics.csv](../../assessment/design/diagnostics.csv)、[learning/work-designs.csv](../../learning/work-designs.csv) | 設計台帳として移管 |
| v0.1 統合診断 | [assessment/design/integrated-cases.csv](../../assessment/design/integrated-cases.csv) | 6ケース。DX06のラベルを明確化 |
| v0.2 W-A1/W-B1開始文 | [learning/W-A1/start.txt](../../learning/W-A1/start.txt)、[learning/W-B1/start.txt](../../learning/W-B1/start.txt) | バイト内容を保持 |
| v0.2 指導・確認基準・記録様式 | [coaches/](../../coaches/)、[assessment/practice/](../../assessment/practice/)、[templates/](../../templates/) | 固定内容を移管 |
| v0.2 実機受入 | [tests/coach-behavior/acceptance.md](../../tests/coach-behavior/acceptance.md) | 参照ファイル名を移管先へ変更。16件とも未実施 |

W-A1開始文 SHA-256：35cad1b91021fbaf8cb8599d15acef0605c1cbba2d397f172e5e0444b878e6fe
W-B1開始文 SHA-256：f9effd6f328b7b907d0e3a5d453c323f5692ec4ae504c5a941f41e0fd25873e9

v0.2元パッケージの8ファイルについて、MANIFESTのバイト数・SHA-256と一致を確認しました。XLSX元ファイルや入力済み評価はアップロードしません。数式付きXLSXの公開用再生成は未実装です。開始文・固定資料には架空の人数・日付があります。

ライセンスの参照は会社の既存公開方針とCC公式資料を確認しました。第三者の全文・図版は含めず、外部標準による認定を主張しません。未公開の製品移行日を含む過去の調査記録、個人名に依存した導入案内、旧配布ZIPは移管しません。

静的検査とGitHub上の確認の結果は[PR #1の本文](https://github.com/itdojp/workplace-competency-framework/pull/1)に記録しています。元資産との照合は移管時点の記録であり、この文書の改訂で再実施したという意味ではありません。静的検査はGeminiの実際の応答や学習効果を検証するものではありません。
