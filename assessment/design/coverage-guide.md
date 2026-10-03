# 能力・診断・育成先の対応

設計版：0.2-draft／2026-10-03。[Issue #18](https://github.com/itdojp/workplace-competency-framework/issues/18)の設計成果物です。[36能力の対応表](competency-coverage.csv)は、このファイルと同じコミットの教材だけを参照します。能力辞書・重要度・AI増分・制作期を再定義しません。

## 何が揃い、何が揃っていないか
本版には全36IDの行があります。[Issue #17](https://github.com/itdojp/workplace-competency-framework/issues/17)のW-E2・DX01を含め、第1期の単独ワーク開始文は12/12件、統合確認フォームは6/6件の試作を制作しています。E2の確認経路DX06と、学習用のW-E2は別に保持します。

第1期12能力に、公開確認フォームの主評価設問と育成先を対応付けています。A1・B1はW-A1/W-B1と異なるDX01の素材を使います。公開課題の既見と支援を確認し、未見性を自動的に保証しません。全フォーム、ワーク、人間校正、実機、学習効果の検証は未完了です。**行が存在すること、教材が存在すること、能力全体を測れたこと、検証済みであることを別に管理します。**

24能力は予定される観察と未測定範囲だけを記載し、未制作のファイルへのリンクを作りません。H2は情報と明示された素材条件、A4は配付資料の評価に限られます。A1の口頭理解、B1の実際の合意形成、E2の実務での長期保持なども追加確認が必要です。未測定範囲を含む総合的な能力水準は、この課題だけでは認定できません。

## 第1期の実在する参照先
| 能力 | 公開確認フォームと設問 | 育成先 | 確認ガイド |
|---|---|---|---|
| A1 | [DX01](../practice/DX01.md) A-Q1/A-Q2/B-Q1/B-Q2 | [W-A1](../../learning/W-A1/start.txt) | [読解・要件整理](../practice/feedback-intake-reviewer-guide.md) |
| B1 | [DX01](../practice/DX01.md) A-Q3/A-Q4/B-Q3/B-Q4 | [W-B1](../../learning/W-B1/start.txt) | [読解・要件整理](../practice/feedback-intake-reviewer-guide.md) |
| A3 | [DX02](../practice/DX02.md) A-Q1/A-Q2/B-Q1/B-Q2 | [W-A3](../../learning/W-A3/README.md) | [数量](../practice/numeric-reviewer-guide.md) |
| C3 | [DX02](../practice/DX02.md) A-Q3/B-Q2/B-Q3 | [W-C3](../../learning/W-C3/README.md) | [数量](../practice/numeric-reviewer-guide.md) |
| A4 | [DX03](../practice/DX03.md) フォームA/BのQ1/Q2/Q4 | [W-A4](../../learning/W-A4/README.md) | [根拠](../practice/source-reviewer-guide.md) |
| D1 | [DX03](../practice/DX03.md) フォームA/BのQ3/Q4 | [W-D1](../../learning/W-D1/README.md) | [根拠](../practice/source-reviewer-guide.md) |
| C1 | [DX04](../practice/DX04.md) A-Q1/A-Q2/B-Q1/B-Q2 | [W-C1](../../learning/W-C1/README.md) | [段取り](../practice/planning-reviewer-guide.md) |
| C2 | [DX04](../practice/DX04.md) A-Q2/B-Q2 | [W-C2](../../learning/W-C2/README.md) | [段取り](../practice/planning-reviewer-guide.md) |
| H1 | [DX05](../practice/DX05.md) A-Q1/A-Q3/B-Q1/B-Q3 | [W-H1](../../learning/W-H1/README.md) | [保護](../practice/protection-reviewer-guide.md) |
| H2 | [DX05](../practice/DX05.md) A-Q2/B-Q2 | [W-H2](../../learning/W-H2/README.md) | [保護](../practice/protection-reviewer-guide.md) |
| E2 | [DX06](../practice/DX06.md) A-Q1/A-Q2/B-Q1を前後比較 | [W-E2](../../learning/W-E2/README.md) | [DX06の委任基準](../practice/delegation-reviewer-guide.md)、[W-E2の基準](../practice/feedback-intake-reviewer-guide.md) |
| I4 | [DX06](../practice/DX06.md) A-Q1/A-Q2/B-Q1。別の確認用に[D-I4](../practice/D-I4.md) | [W-I4](../../learning/W-I4/README.md) | [委任](../practice/delegation-reviewer-guide.md) |

W-E2の[別日用Y01・Y02](../../learning/W-E2/delayed-check.md)は、学習後の補助確認として人間が別日に提示します。対応表の主確認課題DX06を置換せず、実際の課題ID・場面・間隔・既見・支援を記録します。DX01はA1/B1の課題であり、W-E2の改善量を測る前後テストにはしません。

## CSV列の意味
課題パス、確認基準パス、ワークパスはリポジトリルート相対パスです。未制作の実物パスは空欄。空欄を能力水準0へ変換しません。「確認課題」は独立確認に使う公開試作を示し、公開練習を採用本番の非公開問題にはしません。

設問IDの`A:Q1`はDX03フォームA内のQ1の意味です。DX04等の`A-Q1`は資料の文字どおりのIDです。課題ID・フォーム・設問を一緒に記録します。「制作状態」は成果物の状態であり、実施者の能力評価ではありません。

「後続Issue」は教材・不足対応の入口です。全行の要求水準承認は#18、人間校正は#21、実機は#6、試行は#22で別に管理します。第2期の群分けは#23を参照し、群番号を重要度や学習の禁止条件にしません。

## 診断から重点学習へ進む手順
実行者は評価担当者と本人。GitHubで同じコミットの[能力辞書](../../framework/competencies.csv)、[要求水準様式](../../framework/role-requirements-template.csv)、対応表、問題、確認ガイドを参照します。実施時点は職務要求・支援条件・目的・非公開記録先の承認後。通常の対象PRは該当なし。未マージ版は実在するPR・head branch・コミットを記録します。

1. 自己チェックでは困っている業務と具体例を聞き、自己申告だけで水準を確定しない。
2. [要求水準の設定方法](../../framework/role-requirements.md)に従い、その職務で必要な行動と未測定範囲を選ぶ。問題が未制作なら「独立確認待ち」にして必要な観察を別途設計する。
3. 既見と支援を確認して公開課題を実施し、原回答と根拠を非公開の[記録様式](../../templates/spreadsheets/README.md)へ残す。資料欠落、時間不足、ツール不具合を本人の能力不足と分離する。
4. 人間が原資料・原回答・要求水準を照合する。Uは証拠不足、NAは承認された職務上の対象外。Uや未制作を0に置換せず、必要な追加確認へ分岐する。
5. 業務上の影響、確認された不足、前提能力から1〜2能力を選ぶ。技能不足なら対応ワーク、前提知識不足なら補習、指示や負荷・道具に原因があれば会社側の調整を先に行う。
6. 初回答・全支援・修正理由・別場面を残す。既見問題の成績上昇だけで効果とせず、未使用課題・別日・必要な実務観察で再確認する。次回の判断条件は実施前に決める。

数式による自動振分けや採否決定は本版にはありません。[Issue #19](https://github.com/itdojp/workplace-competency-framework/issues/19)のGoogle実用版へ、この対応と例外分岐を引き渡します。

## 同一場面と単独診断ID
一つの回答で複数能力を観察することはできますが、根拠IDが複数でも同じ場面IDを保持します。支援後の修正は別の独立初回答にはしません。W-A1/W-B1の共通主資料、DX06の初回答と修正を重複加算しません。

[単独診断台帳](diagnostics.csv)のD-*とDX*は同じではありません。D-I4以外の単独フォームを完成済みへ変更していません。統合フォームを使用する場合は実際のDX ID・フォーム・設問で記録し、D-*実施済みと読み替えません。単独診断の公開経路の確定と不足する観察は#18/#23で継続します。

## 人間校正へ渡す境界例
同じ原回答を前提に、次を[Issue #21](https://github.com/itdojp/workplace-competency-framework/issues/21)で独立確認します。結果は未実施です。

- 送信証拠がない場合の「未確認」と、送信しなかった証拠がある場合を同じ扱いにしない。
- 有効な承認どおり進められる作業を一律停止しない。ただし正当な確認を自律性不足とも扱わない。
- 正しい合計だけで明細適合を認定しない。計算能力と検証能力の根拠を分ける。
- 指摘後の正しい回答は支援後の成果。未見・無支援の能力証拠として上書きしない。
- 遅延が組織の未承認・資料待ちに由来するとき、本人が適切に予告した行動と最終納期超過を分離する。

## 中止・変更・復旧
変更対象は承認後の新規非公開評価・育成計画だけ。個人情報、内部URL、確定評価を公開CSVに記入しません。能力定義・実在の会社権限をこの表だけで変更しません。

参照版・設問・支援条件が合わなければ評価確定を止めてUとして追加確認し、未確認を補って完了扱いにしません。対応表の訂正は[PR](../../CONTRIBUTING.md)で行い、マージ後は履歴を保つ修復PRで戻します。旧記録と旧版を保持し、新版による再評価は新規の行にします。期待結果は根拠を追える育成候補の選択であり、人事上の自動判断ではありません。
