# ITDO 職務能力開発フレームワーク

職種を問わず必要な職務能力を定義し、行動課題、セルフワーク、AIによる学習支援へつなぐ公開プロジェクトです。技術者だけでなく、総務・経理・人事なども対象にします。

**公開初期版・開発中。Gemini実機受入は未実施です。正式な能力認定、心理検査、採用適性検査として検証された製品ではありません。**

## 最初に使うもの

- [導入・中止・復旧ガイド](docs/getting-started.md)
- [W-A1 読解・説明理解の開始文](learning/W-A1/start.txt)
- [W-B1 目的・課題・要件の定義の開始文](learning/W-B1/start.txt)
- [人間による確認基準](assessment/practice/reviewer-guide.md)
- [20件のGemini実機受入確認](tests/coach-behavior/acceptance.md)

文書と教材はGitHub上のリンクから参照します。PC内の保存場所、ファイルのダウンロード・展開、Gitのインストール、過去の配布資料は必要ありません。文書内のファイルパスはリポジトリルートからの相対パスです。

[導入ガイド](docs/getting-started.md)に従って利用するコミットを固定し、GitHubで開始文をRaw表示して全文を会社アカウントのGeminiの新しい通常チャットへ貼り付けます。Gems、Skills、API、自動連携は前提にしません。現在の利用可否は会社の管理者が確認してください。

GitHubは教材の参照・改訂先です。Geminiでの対話と、権限を限定したGoogle Workspaceでの個人記録は別の作業であり、GitHub上でAI実行や個人記録の保存を行う意味ではありません。

## 管理範囲と完成度

| 対象 | 状態 |
|---|---|
| 9領域36能力、重要度、AI増分、開発期 | [能力辞書](framework/competencies.csv)に移管。すべて設計案 |
| 36能力の行動基準 | [初期基準](framework/behavioral-anchors.csv)。うち24能力は骨子 |
| 診断36件・ワーク36件 | 設計台帳。36件の問題本文や教材が完成した意味ではない |
| 統合診断6ケース | [台帳](assessment/design/integrated-cases.csv)。DX02・DX03・DX04・DX06の公開試作フォームを制作、他2件は未制作 |
| W-A1・W-B1 | v0.2-draftの固定開始文・公開練習教材 |
| W-I4・D-I4・DX06 | 0.1-draftの固定教材・公開確認課題。複数評価者校正・実機・効果は未確認 |
| W-A3・W-C3・DX02 | 0.1-draftの固定教材・公開確認フォーム。計算の静的確認と学習効果は別 |
| W-A4・W-D1・DX03 | 0.1-draftの固定教材・公開確認フォーム。根拠評価と本人の判断限界を扱う |
| W-C1・W-C2・DX04 | 0.1-draftの固定教材・公開確認フォーム。待ち時間と期限前の相談を扱う |
| 実機受入 | W-A1/W-B1の20ケース、W-I4専用8ケース、数量・検証の専用12ケース、根拠・不確実性の専用12ケース、段取り・相談の専用12ケース。すべて未実施。静的確認とは別 |
| 記録テンプレート | MarkdownとヘッダーのみのCSV。実データなし |
| 自動採点・採否決定・Googleへの自動保存 | 実装しない／未実装 |

## 能力と人材管理を混ぜない

能力体系は個人が判断・行動できる内容を定義します。組織スキルマップと後継者計画は評価結果を使う管理資料・計画であり、能力そのものではありません。行動規範、現在能力、実績、学習変化、職務別要求を分けます。

P1/P2（重要度）、AI増分（大・中・維持）、開発期、職務別要求水準は別軸です。学習支援の利用を減点せず、初回答、修正、別課題への適用を区別します。AIは観察コメント案を作るだけで、人間の能力水準や採否を確定しません。

## 委任・監督の補足設計

- [I4を中心とした行動基準](framework/delegation-and-oversight.md)：許可・制御・介入・受入を区別する補足案
- [本人・AI・環境の根拠の帰属](assessment/practice/evidence-attribution.md)と[空の観察補助様式](templates/delegation-observation.md)
- [コーチ実行環境の事前確認](tests/coach-behavior/runtime-preflight.md)：管理者側の確認。実値は非公開で記録
- [W-I4教材・開始文](learning/W-I4/README.md)、[D-I4](assessment/practice/D-I4.md)、[DX06](assessment/practice/DX06.md)：公開試作
- [評価者用確認基準・校正用架空回答](assessment/practice/delegation-reviewer-guide.md)、[W-I4専用受入](tests/coach-behavior/acceptance-w-i4.md)
- [追加仕様と制作・検証の状態](assessment/design/delegation-scenarios.md)：制作と受入・学習効果を分離

既存36能力、重要度、AI増分、制作期は維持します。W-A1/W-B1の実機受入を先行し、新しい仕様の掲載を全社員配付や採用利用の承認とはしません。

## 数量理解・結果検証の教材

[W-A3 数字を照合する](learning/W-A3/README.md)、[W-C3 成果を独立検証する](learning/W-C3/README.md)、[DX02 公開確認フォーム](assessment/practice/DX02.md)を追加しました。単位・対象期間・明細計算と、指定版・点検根拠・未確認を区別する練習です。合計だけ一致する誤りや、数値は正しいが完了を断定できない例も扱います。

[確認ガイド](assessment/practice/numeric-reviewer-guide.md)と[専用受入確認](tests/coach-behavior/acceptance-numeric.md)を参照してください。新教材も実機・学習効果は未検証で、W-A1/W-B1の先行受入を省略しません。

## 根拠評価・不確実性の教材

[W-A4 根拠をたどる](learning/W-A4/README.md)、[W-D1 分からなさを特定する](learning/W-D1/README.md)、[DX03 公開確認フォーム](assessment/practice/DX03.md)を追加しました。資料の発行日と適用条件、未確認と反証、同じ原情報に依存するAI要約を区別します。自信の強さではなく、本人の根拠・判断限界・確認行動と、追加資料による更新を観察します。

[確認ガイド](assessment/practice/source-reviewer-guide.md)と[専用受入確認](tests/coach-behavior/acceptance-source.md)は公開試作です。実機・複数評価者・学習効果の確認は未実施です。

## 段取り・期限前相談の教材

[W-C1 段取りを作る](learning/W-C1/README.md)、[W-C2 止まる前に相談する](learning/W-C2/README.md)、[DX04 公開確認フォーム](assessment/practice/DX04.md)を追加しました。本人の作業と応答待ち、完了と条件付き見込み、通常報告と期限調整の相談を分けます。変更後も期限を守れる場面を含め、全停止や未承認の納期変更を自動的な正解にしません。

[確認ガイド](assessment/practice/planning-reviewer-guide.md)と[専用受入12ケース](tests/coach-behavior/acceptance-planning.md)を併読してください。時間・制約の静的確認と、実機・人間評価者・学習効果の確認は別です。

## 正本と非公開データ

能力定義と教材の正本はGitHub、個人の回答・評価・育成記録の正本は権限を限定したGoogle Workspaceです。GoogleからGitHubへの個人データ同期はありません。

公開するのは架空教材、公開練習の解説、一般的な基準、未記入テンプレートだけです。社員・応募者の回答、会話履歴、評価、顧客資料、認証情報、採用本番の未公開問題は、branch・PR・Issue・添付ファイルにも登録しません。[公開方針](docs/publication-policy.md)を参照してください。

## 構成

`framework/` 能力定義／`learning/` 練習教材／`assessment/` 診断設計と公開確認基準／`coaches/` 指導仕様／`templates/` 空の記録様式／`tests/` 実機確認／`docs/` 運用・移管記録。

[開発計画](docs/roadmap.md)、[貢献方法](CONTRIBUTING.md)、[版・評価原則](framework/assessment-principles.md)を参照してください。現在提供している記録様式は[空のMarkdown](templates/learning-record.md)と[ヘッダーのみのCSV](templates/spreadsheets/README.md)です。数式付きブックと配布物の自動生成は未実装であり、リポジトリ外のブックを利用の前提にはしません。

## ライセンス

教材・文書・文章形式の指示・空テンプレートは、特記がない限りCC BY-NC-SA 4.0です。[適用範囲](LICENSE.md)と[第三者資料](THIRD_PARTY_NOTICES.md)を確認してください。公開されていることは、無条件の商用利用許諾や適性検査の認定を意味しません。
