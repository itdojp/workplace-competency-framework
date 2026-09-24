# 公開・非公開の境界

公開可：能力辞書、設計、架空教材、公開練習の解説、コーチ指示、未記入テンプレート、架空入力による不具合の再現方法。

登録禁止：実在の社員・応募者の回答、会話履歴、評価、採否、後継者候補、個別指導記録、顧客情報、非公開の契約・社内構成、認証情報、採用本番の未公開問題・解答キー。

禁止対象はbranch、Draft PR、Issue、レビュー、コミットメッセージ、添付、Actionsログ・artifact、Releaseにも持ち込まないでください。公開リポジトリにprivateというフォルダーを作っても非公開にはなりません。匿名IDへの置換だけで個人の学習履歴を公開可と扱いません。

個人記録は会社が承認した制限付きGoogle Workspaceへ保存し、GitHubへ同期しません。保存先URL・共有者・保存期間を管理者が確認します。ここには実際の内部URLや共有権限一覧を記載しません。

初回push前に、ファイル本文、CSV各行、表計算の非表示シート・コメント・外部リンク、画像、メタデータを確認します。PRでの確認は二段目であり、最初の公開を防ぐ仕組みではありません。.gitignoreは補助であり、機密保護の保証ではありません。

誤公開時：以後の公開・配布を止め、会社の情報管理担当者へ非公開の経路で報告します。Issueへ漏えい内容を再掲しません。認証情報は失効等を検討し、参照、履歴、配布物への影響を確認します。最新ファイルから消しただけで回収済みとしません。履歴書換え・強制push・全体設定変更は管理者承認後に行います。

参考：https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories 、 https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository
