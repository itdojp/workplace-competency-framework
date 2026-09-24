# 初回試行と復旧

## 前提・対象

実行者は教材確認担当者。会社管理Windows 11 PCのブラウザと、会社Google Workspaceアカウントを使用します。管理者がGemini利用可否を確認した後、架空資料だけで試行します。個人アカウントへの切替、追加課金、Beta一括有効化は行いません。

対象リポジトリ：itdojp/workplace-competency-framework。初期登録branch：chore/bootstrap-public-framework。対象PRはGitHubの同branchのPR画面で実在する番号を確認してください。mainへマージ済みの場合は、利用するコミットを記録してから開始します。

W-A1のリポジトリルート相対パスはlearning/W-A1/start.txt、W-B1はlearning/W-B1/start.txtです。GitHubのファイル画面をRawで開き、全文をコピーします。ZIPを利用する場合は、未使用の作業場所としてC:\work\itdo-capability\public-bootstrap\workplace-competency-frameworkを用意します。このフォルダーは提案パスであり自動作成しません。

完全なWindows参照パス：
- C:\work\itdo-capability\public-bootstrap\workplace-competency-framework\learning\W-A1\start.txt
- C:\work\itdo-capability\public-bootstrap\workplace-competency-framework\learning\W-B1\start.txt
- C:\work\itdo-capability\public-bootstrap\workplace-competency-framework\tests\coach-behavior\acceptance.md

変更対象は新規の架空試行チャットと、管理者が承認した個人用の試行記録だけです。原資料、会社設定、実際のメール・Driveファイル、社員名簿、正式評価、既存v0.1ブックは変更しません。正式なDrive保存先と確認担当者は試行前に決定し、公開Issueへ記載しません。

## W-A1

1. 会社アカウントでGeminiの通常の新規チャットを開きます。利用できなければ管理者へ確認し、個人アカウントへ迂回しません。
2. learning/W-A1/start.txtの全文を最初のメッセージへ貼り付けます。ファイル添付、Gems、Skills、外部連携は使用しません。
3. 期待する初回表示はW-A1、0.2-draft、原資料[1]～[7]、Q1だけです。正解や全設問の回答が先に出たら受入不適合として記録します。
4. 初回答、根拠確認、必要な支援、修正理由、別場面へ進みます。20分は目安です。支援を使ったことや中断だけで能力を低く評価しません。
5. 終了時は「記録を出して終了」と伝え、記録案を会話と照合します。初回答、支援、未実施を改変していないことを確認し、templates/learning-record.mdを個人用保存先で記入します。AIの保存済みという発言だけで保存を完了扱いにしません。

## W-B1

W-A1の受入結果を確認した後、別の新規チャットでlearning/W-B1/start.txtを実行します。主資料はW-A1と同じです。既見資料を未知課題の独立証拠として数えません。

## エラー時・復旧

初回解答の先出し、条件改変、実操作の要求、架空の保存報告、初回答の書換えがあれば、その試行を能力確認に使わず停止します。教材ID・版・問題箇所を確認担当者へ伝えます。公開報告には架空の再現入力だけを使い、実際の社員の会話を貼りません。

教材の誤編集は、記録したコミットの原本から別フォルダーへ再取得して復元します。失われた本人回答は推測復元しません。途中のチャットを再開した場合は初回独力評価と区別します。既承認の実機適合版がない間は全社員配付へ進みません。

今回の一時方式は通常チャットです。恒久方針は教材・指導仕様・記録・実行基盤の分離。Gems/Skills対応、実機受入、全社員配付、Google自動記録は別作業です。
