# スプレッドシート10行試行用の架空入力

データ版：0.1-draft。実施結果ではありません。[元のfixtures.json](fixtures.json)と同じ2ケースを、A2へコピーできるタブ区切りで掲載しています。人名・承認・日付・回答はすべて架空です。「照合済」「承認済」「人間確定」は計算試験の入力であり、会社の承認を示しません。

実行者・環境・参照版・停止・復旧は[担当者の実施手順](../../docs/operator-handoff.md)を参照してください。新規の非公開検証ファイルにだけ貼り付けます。既存記録と混ぜず、入力列だけを上書きし、右側の数式は保持します。各ブロックは見出しなしでA2から貼り付け、指定の末尾セルに収まることを確認します。この資料にはTEST-TとTEST-Gの両方を含むため、学習用も実在社員のファイルではなく、担当者だけの検証専用ファイルに貼り付けます。

元データのGit blob SHA：`5c8e95b036be4fc60a88cf96cb28502b1d5261e3`。日付の数値は元データと同じ日付シリアル値です。数字を書き換えて現在の実施日・承認日に見せません。実際の試験日は別の非公開実施記録に記載します。

## 対象者：A2:D3

```text
TEST-T	PROFILE-T	技術	有効
TEST-G	PROFILE-G	総務	有効
```

## 参照版：A2:E2

```text
a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	照合済	TEST-REVIEWER	46388	全て架空の試験入力
```

## 要求：A2:U3

```text
PROFILE-T	技術	担当者	架空業務	A3	対象	2	指定された行動を別課題で確認	通常資料可	下書きと確認のみ	DX02	別日・別場面を人間が確認	TEST-REVIEWER	承認済	TEST-APPROVER	46388	46752	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/framework/role-requirements-template.csv	REQ-T	2
PROFILE-G	総務	担当者	架空業務	C2	対象	2	指定された行動を別課題で確認	通常資料可	下書きと確認のみ	DX04	別日・別場面を人間が確認	TEST-REVIEWER	承認済	TEST-APPROVER	46388	46752	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/framework/role-requirements-template.csv	REQ-G	2
```

## 評価：A2:S5

```text
EV-T-0	TEST-T	A3	0.1-draft	育成試行	46397	2	U	架空コメント	1	E-T-0a	通常資料可	TEST-REVIEWER	人間確定	46425	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evaluations.csv	REQ-T	
EV-T-1	TEST-T	A3	0.1-draft	育成試行	46411	2	U	架空コメント	2	E-T-1a	通常資料可	TEST-REVIEWER	人間確定	46425	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evaluations.csv	REQ-T	EV-T-0
EV-G-0	TEST-G	C2	0.1-draft	育成試行	46397	2	U	架空コメント	0	E-G-0a	通常資料可	TEST-REVIEWER	人間確定	46425	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evaluations.csv	REQ-G	
EV-G-1	TEST-G	C2	0.1-draft	育成試行	46411	2	U	架空コメント	2	E-G-1a	通常資料可	TEST-REVIEWER	人間確定	46425	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evaluations.csv	REQ-G	EV-G-0
```

## 根拠：A2:P9

```text
E-T-0a	TEST-T	A3	EV-T-0	SCENE-T-0-a	46397	DX02	0.1-draft	架空原回答:E-T-0a	通常資料	架空の観察結果	長期の実務適用は未確認	照合済	TEST-REVIEWER	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evidence.csv
E-T-0b	TEST-T	A3	EV-T-0	SCENE-T-0-b	46397	DX02	0.1-draft	架空原回答:E-T-0b	通常資料	架空の観察結果	長期の実務適用は未確認	照合済	TEST-REVIEWER	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evidence.csv
E-T-1a	TEST-T	A3	EV-T-1	SCENE-T-1-a	46411	DX02	0.1-draft	架空原回答:E-T-1a	通常資料	架空の観察結果	長期の実務適用は未確認	照合済	TEST-REVIEWER	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evidence.csv
E-T-1b	TEST-T	A3	EV-T-1	SCENE-T-1-b	46411	DX02	0.1-draft	架空原回答:E-T-1b	通常資料	架空の観察結果	長期の実務適用は未確認	照合済	TEST-REVIEWER	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evidence.csv
E-G-0a	TEST-G	C2	EV-G-0	SCENE-G-0-a	46397	DX04	0.1-draft	架空原回答:E-G-0a	通常資料	架空の観察結果	長期の実務適用は未確認	照合済	TEST-REVIEWER	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evidence.csv
E-G-0b	TEST-G	C2	EV-G-0	SCENE-G-0-b	46397	DX04	0.1-draft	架空原回答:E-G-0b	通常資料	架空の観察結果	長期の実務適用は未確認	照合済	TEST-REVIEWER	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evidence.csv
E-G-1a	TEST-G	C2	EV-G-1	SCENE-G-1-a	46411	DX04	0.1-draft	架空原回答:E-G-1a	通常資料	架空の観察結果	長期の実務適用は未確認	照合済	TEST-REVIEWER	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evidence.csv
E-G-1b	TEST-G	C2	EV-G-1	SCENE-G-1-b	46411	DX04	0.1-draft	架空原回答:E-G-1b	通常資料	架空の観察結果	長期の実務適用は未確認	照合済	TEST-REVIEWER	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/evidence.csv
```

## 評価根拠：A2:B9

```text
EV-T-0	E-T-0a
EV-T-0	E-T-0b
EV-T-1	E-T-1a
EV-T-1	E-T-1b
EV-G-0	E-G-0a
EV-G-0	E-G-0b
EV-G-1	E-G-1a
EV-G-1	E-G-1b
```

## 育成：A2:U3

```text
PLAN-T	TEST-T	A3	E-T-0a	架空の目標行動	W-A3	0.1-draft	必要なヒント	TEST-COACH	46399	46411	架空の別場面2件	原回答と新規再評価を人間が照合	完了	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/development-plans.csv	EV-T-0	架空学習記録:SESSION-T	EV-T-1	確認済	TEST-REVIEWER
PLAN-G	TEST-G	C2	E-G-0a	架空の目標行動	W-C2	0.1-draft	必要なヒント	TEST-COACH	46399	46411	架空の別場面2件	原回答と新規再評価を人間が照合	完了	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/development-plans.csv	EV-G-0	架空学習記録:SESSION-G	EV-G-1	確認済	TEST-REVIEWER
```

## 学習：A2:R7

```text
SESSION-T	W-A3	0.1-draft	46399	通常チャット（架空）	架空モデル	初回答	Q1	架空原回答参照	なし				実務保持は未確認		確認済	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/learning-records.csv
SESSION-T	W-A3	0.1-draft	46399	通常チャット（架空）	架空モデル	支援後修正	Q1	架空原回答参照	H1	架空修正参照	架空の修正理由		実務保持は未確認		確認済	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/learning-records.csv
SESSION-T	W-A3	0.1-draft	46399	通常チャット（架空）	架空モデル	別場面	X-Q1	架空原回答参照	なし			架空別課題結果	実務保持は未確認		確認済	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/learning-records.csv
SESSION-G	W-C2	0.1-draft	46399	通常チャット（架空）	架空モデル	初回答	Q1	架空原回答参照	なし				実務保持は未確認		確認済	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/learning-records.csv
SESSION-G	W-C2	0.1-draft	46399	通常チャット（架空）	架空モデル	支援後修正	Q1	架空原回答参照	H1	架空修正参照	架空の修正理由		実務保持は未確認		確認済	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/learning-records.csv
SESSION-G	W-C2	0.1-draft	46399	通常チャット（架空）	架空モデル	別場面	X-Q1	架空原回答参照	なし			架空別課題結果	実務保持は未確認		確認済	a59545025fe339d0f85b0ce7e2aff4ca0b2c4217	https://github.com/itdojp/workplace-competency-framework/blob/a59545025fe339d0f85b0ce7e2aff4ca0b2c4217/templates/spreadsheets/learning-records.csv
```

## 貼付け後

正常時の表示、前回評価IDを使う異常系、復旧は[担当者の実施手順](../../docs/operator-handoff.md)の期待結果と照合します。列ずれや計算エラーがあれば入力を止め、元の非公開コピーを残して作り直します。この入力で正常表示になっても、実務上の能力評価やGoogle上の権限制限を確認したことにはなりません。
