# セルフワーク

| ワーク | 対象能力 | 版 | 状態 |
|---|---|---|---|
| [W-A1](W-A1/start.txt) | 読解・説明理解 | 0.2-draft | 固定教材・実機未検証 |
| [W-B1](W-B1/start.txt) | 目的・課題・要件の定義 | 0.2-draft | 固定教材・実機未検証 |
| [W-A3](W-A3/README.md) | 数量・データ理解 | 0.1-draft | 固定教材・実機未検証 |
| [W-C3](W-C3/README.md) | 品質基準・結果検証 | 0.1-draft | 固定教材・実機未検証 |
| [W-A4](W-A4/README.md) | 情報探索・情報源評価 | 0.1-draft | 固定教材・実機未検証 |
| [W-D1](W-D1/README.md) | 理解・限界の自己認識 | 0.1-draft | 固定教材・実機未検証 |
| [W-C1](W-C1/README.md) | 計画・段取り・優先順位 | 0.1-draft | 固定教材・実機未検証 |
| [W-C2](W-C2/README.md) | 進捗管理・相談 | 0.1-draft | 固定教材・実機未検証 |
| [W-H1](W-H1/README.md) | ルール・権限境界の判断 | 0.1-draft | 固定教材・実機未検証 |
| [W-H2](W-H2/README.md) | 安全・情報・権利の保護 | 0.1-draft | 固定教材・実機未検証 |
| [W-I4](W-I4/README.md) | 委任・自動化・監督 | 0.1-draft | 固定教材・実機未検証 |

各`start.txt`は、原資料・設問・支援指示を含む独立実行用の固定原本です。過去の配布物は必要ありません。[導入ガイド](../docs/getting-started.md)に従い、GitHub上でコミットを固定してRawから全文をコピーします。日付・人数は架空です。現在時刻に合わせて自動更新しません。W-A1の後にW-B1へ進み、各ワークで新規チャットを使用します。

[work-designs.csv](work-designs.csv)は36件の設計台帳であり、36教材の完成一覧ではありません。台帳の制作状態と上表を併読してください。開始文の自動生成はまだありません。[共通指導仕様](../coaches/common/instructions.md)を改訂する場合は影響する各開始文への反映・版更新・再試験を同じPRで扱います。

W-A3・W-C3・DX02・W-A4・W-D1・DX03・W-I4・D-I4・DX06・W-C1・W-C2・DX04・W-H1・W-H2・DX05の台帳参照先は、[設計台帳と公開教材のリンク一覧](../assessment/design/README.md)から開けます。CSV内では教材初回登録版のGitHub固定URLを記録し、リンク一覧では同じbranch・コミットの教材への相対リンクも提供します。

通常チャット、Gems、Skills等の実行基盤は能力定義から分離します。初期版は会社アカウントのGemini通常チャットでの試行を想定し、必要な会社側の許可を確認してから使います。

## W-I4の追加

[W-I4固定資料](W-I4/materials.md)は、[W-I4開始文](W-I4/start.txt)の固定資料区画にも同一内容を収録する。変更時は両方を同じPRで更新し、区画の一致を検査する。生成処理はリポジトリには未実装。W-A1/W-B1の先行受入は維持し、W-I4の利用方法と8件の専用受入は[W-I4案内](W-I4/README.md)を参照する。

診断練習は[D-I4](../assessment/practice/D-I4.md)と[DX06](../assessment/practice/DX06.md)に分離した。生成AIなしの初回答、固定助言、修正、別課題を区別する。公開教材を見た人に同じ素材を提示して未見能力の証拠にしない。

## 数量理解と結果検証

[W-A3](W-A3/README.md)は単位・対象期間・明細、[W-C3](W-C3/README.md)は指定版・点検根拠・未確認の区別を練習する。別々の固定主資料と別場面を用いる。公開確認フォーム[DX02](../assessment/practice/DX02.md)は生成AIなしの初回答を記録する。D-A3・D-C3の単独フォームを制作済みにはしない。

[人間の確認ガイド](../assessment/practice/numeric-reviewer-guide.md)と[専用受入12ケース](../tests/coach-behavior/acceptance-numeric.md)を併読する。新教材は試作であり、W-A1/W-B1の先行受入、W-I4の既存受入計画を変更しない。本人の評価・会社設定・実機結果は未確認のまま別工程として扱う。

## 根拠評価と不確実性

[W-A4](W-A4/README.md)は新旧資料の適用条件と情報源の独立性、[W-D1](W-D1/README.md)は本人の説明可能範囲・不足と、追加資料による判断更新を練習します。固定資料と開始文は各ワークで同一内容を維持します。主資料は別々で、W-D1では追加資料の提示前後を分けて記録します。

[DX03](../assessment/practice/DX03.md)は生成AIなしの初回答用の公開フォームA/Bです。[確認ガイド](../assessment/practice/source-reviewer-guide.md)と[専用受入12ケース](../tests/coach-behavior/acceptance-source.md)を併読してください。単独診断D-A4・D-D1は未制作。全教材は実機・複数評価者・学習効果が未確認で、既存教材の先行受入を置換しません。

## 段取りと期限前の相談

[W-C1](W-C1/README.md)は依存関係・待ち・余裕を含む計画、[W-C2](W-C2/README.md)は残作業・阻害要因と期限前相談を扱います。各開始文と固定資料は全文同一。途中の変更資料は初回答を記録してから提示し、固定の提示状態を本人が実行した実績にしません。

[DX04](../assessment/practice/DX04.md)は生成AIなしの初回計画→統一時点の変更→再計画・相談の公開フォームです。[確認ガイド](../assessment/practice/planning-reviewer-guide.md)と[専用受入12ケース](../tests/coach-behavior/acceptance-planning.md)を参照してください。D-C1・D-C2の単独診断は未制作。会社の環境確認、既存教材の先行受入、複数評価者確認は省略しません。

## 権限・情報保護と対象能力の選択

[W-H1](W-H1/README.md)は承認者・対象・操作の照合、[W-H2](W-H2/README.md)は情報最小化・共有先・素材条件を扱います。[DX05](../assessment/practice/DX05.md)は別資料での公開確認フォームです。[確認ガイド](../assessment/practice/protection-reviewer-guide.md)と[専用受入12ケース](../tests/coach-behavior/acceptance-protection.md)を参照します。すべて試作・未検証で、H2の身体安全・公平性などは未測定です。

[36能力の診断・育成対応](../assessment/design/coverage-guide.md)から、職務に必要な行動と未測定範囲を確認して1〜2能力を選びます。要求水準・評価の確定は人間の承認後です。第1期の開始文は11/12件、W-E2とDX01は未制作です。D-H1・D-H2単独診断を完成済みと扱わず、公開確認の同一場面を重複計上しません。
