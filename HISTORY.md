# これまでの経緯と公開記録の所在

確認日：2026-09-14 JST。

この記録は、数か月前から続くSupportへの照会を引き継ぐための案内です。過去の公開記録は [openai-trust-audit](https://github.com/lucidity3k/openai-trust-audit) にあります。ここでは、既に公開された資料と、索引だけが公開されている事項を区別します。

## 時系列

| 日時・期間 | これまでの内容 | 公開資料と掲載範囲 |
|---|---|---|
| 2026年5月〜6月 | Agent Modeの有料アクセス、利用枠の計上、Support Specialistへのエスカレーションと後続回答に関するCase群。旧索引は5月24日を開始候補、5月29日・6月10日・6月30日をエスカレーション候補として記録している。 | [旧時系列](https://github.com/lucidity3k/openai-trust-audit/blob/1788a9469834136804514a306752c3e4982d2312/TIMELINE.md)、[旧Case索引](https://github.com/lucidity3k/openai-trust-audit/blob/1788a9469834136804514a306752c3e4982d2312/CASES.md)。当該日時は旧索引のレビュー待ち情報で、各会話の全原文は公開されていない。 |
| 2026年7月〜8月の調査対象 | 利用枠・返金や救済、保存済み記録の確認、画像編集の仕様と購入前の説明、障害説明の根拠と訂正が論点となっている。 | [旧Case索引](https://github.com/lucidity3k/openai-trust-audit/blob/7bfdada27e1c8c30e0cbe6f5b1fb4d211443d5c4/CASES.md)。Case 10047260、10546615、10730658、10737880、10849106、12115787等の掲載範囲を個別に確認できる。索引の掲載を全経過の立証と扱わない。 |
| 2026-08-12 07:04 | Case 10737395で、近日中に返信がなければ数日以内にチケットを閉じるという通知。 | [公開証拠記録](https://github.com/lucidity3k/openai-trust-audit/blob/7bfdada27e1c8c30e0cbe6f5b1fb4d211443d5c4/evidence/support/2026-08-13/case-10737395-closure-warning-refund-followup.md) と同記録から辿れる公開用PDF。PDF自体にタイムゾーンの印字はない。 |
| 2026-08-12 08:59 | 利用者が「は?」と返信。 | 同上。 |
| 2026-08-13 06:22 | Aira / OpenAI SupportがCase 10737395の返信で、Case 10047260の返金審査継続を明記。Google Play Order IDを要求し、既提出の懸念・補足情報は再送不要と記載。 | 同上。Order IDの先行提出については同PDF単独では確認されず、旧記録でも利用者報告として区別されている。 |
| 2026-08-21のCommunity返信／9月6日取得記録 | 画像編集が選択範囲の外へ及ぶことがあり、ピクセル単位の保持は常に保証されないとの返信と、トピックを閉じる旨が記録されている。 | [既存のCommunity返信記録](https://github.com/lucidity3k/openai-trust-audit/blob/1788a9469834136804514a306752c3e4982d2312/evidence/support/2026-08-21-openai-community-image-edit-response.md)。既存資料は画面の文字起こしで、ページ原本のスナップショットは含まない。 |
| 2026-09-13の記録 | Case番号を示してもAI窓口が個別Case記録を参照できないと説明。質問の再掲要求、参照できる担当への引継ぎ要求、エスカレーション案内、新規Case作成を促すUI表示、再度の引継ぎ要求と案内が記録された。 | [既存の経緯記録](https://github.com/lucidity3k/openai-trust-audit/blob/7bfdada27e1c8c30e0cbe6f5b1fb4d211443d5c4/evidence/support/2026-09-13/ai-support-case-record-access-escalation-loop.md)。旧資料の分類は USER_REPORTED / REVIEW_PENDING。UIの新規Case案内だけで正式な終了とは判定していない。 |

## 既存リポジトリの状態

- mainの確認済みcommit：`1788a9469834136804514a306752c3e4982d2312`。方法論、出典方針、Case索引、時系列、Community返信記録が掲載されている。
- [PR #2](https://github.com/lucidity3k/openai-trust-audit/pull/2) は2026-09-14確認時点で公開・未マージ。headは `7bfdada27e1c8c30e0cbe6f5b1fb4d211443d5c4`。
- PR #2にはCase 10737395の公開用PDF、Case 10047260への参照、9月13日の経緯記録がある。上のリンクは既存commitを固定して参照する。

## まだ全件公開されていないもの

2026-09-13のローカル監査では、Support一覧25件のうち本文が表示された24件を確認した。1件（監査ID S24）は本文が表示されなかった。画面側で省略された続きや添付原本も未確認の部分がある。これは監査の実施範囲の記録であり、25件すべての全文を読了・公開したという意味ではない。

取得本文、原文対応表、考察、考察の訂正記録は現時点では非公開で保存されている。今回の公開範囲に、それらの全原文や非公開の決済資料・アカウント情報は含めない。個別の資料を公開する際に、原文と個人情報の照合結果を付ける。

過去からの未回答継続回数、正式終了の件数、Case分岐数などの累計は、既存記録との照合が終わっていない。未確定の累計を0として開始し直さない。
