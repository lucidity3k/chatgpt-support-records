# 9月返金の完了通知と実行記録の不一致、Angelへの確認要求、CFLS相談送信

記録日：2026-10-23 JST。対象：Case 14968878の9月26日通知と、Case 17979984の10月22〜23日のメール。時刻はすべてJSTで、UTCを併記した箇所を除く。

## この追記の要点

**9月の有料Proについて「返金処理済み・同時にアクセス終了」と通知された後も、利用者は返金未受領を報告している。10月22日23:27のSupport返信は、サポート主導のアクセス終了記録を示す一方、有料9月注文の返金確認・支払い追跡の参照を、確認可能なモバイル履歴では見つけられなかったと述べた。**

`OBSERVATION`：同返信は、0円注文の記録では有料分の返金を裏付けられないと明記している。アクセス終了の記録上時刻は2026-09-26 17:16:49 JST（08:16:49 UTC）と説明された。これはSupportがメールで述べた記録内容であり、公開者が社内ログ自体を取得したものではない。

`USER_REPORT`：9月には実際に有料アクセスを失い、通知された返金を受領していない。利用者は9月の未返金是正を主題とし、10月のChat・Work・Codexのエラーによる別の返金要求も維持している。10月に有料契約が存在することを、サービスが正常に利用できることと同一視しない。

`OBSERVATION`：10月23日00:16、同じスレッドへAngelへの実確認、完了通知の根拠、アクセス終了後の未受領理由、具体的な返金・是正期限を求める返信を送信した。CFLSへの相談送信済みを記載し、本人が提示した相談送信完了画面1件を添付した。送信後の本文・実宛先・日時・添付表示を照合した。

先行記録：[2026-10-21のCodex署名付き意見書](2026-10-21-codex-ftc-refund-opinion.md)。既存の記録・原資料・カウンターは変更せず、本追記を別ファイルで追加する。

## 時系列

| 日時（JST） | 表示上の担当・ケース | 確認した表示／記録 |
|---|---|---|
| 2026-09-26 17:16:49 | サポート主導の操作として後日の返信が説明 | アクセス終了の履歴時刻。秒付きの時刻は10/22 23:27返信の説明に基づく。 |
| 2026-09-26 17:33 | Angel／14968878 | Pro月額の返金を08:16 UTCに処理し、同時にアクセスも終了したと通知。元通知の処理時刻は分までの表示。 |
| 2026-10-22 20:53 | EJ B／17979984 | 以前の返金案内は誤りで、約1か月待たせたと認め、返金を拒否した。確認した契約は未キャンセルとも述べたが、対象月・注文は特定していない。 |
| 2026-10-22 21:40 | 利用者 | 9月の処理済み通知後の未返金と、10月の3サービスのエラーによる返金要求を月別に明示する訂正返信を送信。 |
| 2026-10-22 22:37 | EJ B／17979984 | 追加確認完了・追加エスカレーション不要としながら、返金拒否理由・注文別判断等の詳細を開示せず、9月の問題未解消と是正期限なしを明記。 |
| 2026-10-22 22:59 | 利用者 | 9/26の日本語・英語・署名・技術説明・当時の引用履歴を含む原文全文を同じスレッドへ返信。 |
| 2026-10-22 23:27 | OpenAI AI Support Agent／17979984 | 0円操作は有料9月分の返金を立証せず、確認可能なモバイル履歴には有料9/3・9/5の返金確認・追跡参照が見つからないと回答。サポート主導アクセス終了の時刻を明記。 |
| 2026-10-23 00:16 | 利用者 | Angelへの確認と9月の根拠・未受領理由・返金期限を要求。CFLS相談送信済みの記載と相談完了画像1件を含む。新規本文1182文字を送信後に全文照合。 |

時系列は保存済みの原文・送信後確認記録に基づく。記録作成のために新しい受信確認を行ったわけではない。

## 出典A：9月26日の完了通知（原文抜粋）

`OBSERVATION`／受信表示：2026-09-26 17:33／Case 14968878／署名：Angel、OpenAI Support。9/26の元メールを10/22に直接開いて再照合した。後日の引用だけで元通知を代用していない。

```text
I can confirm that the refund for your ChatGPT Pro monthly subscription was processed on September 26, 2026 at 08:16 UTC, and access to that subscription ended at the same time. The refund applies to that ChatGPT Pro monthly subscription purchase and may take 7–10 business days to appear, depending on your payment provider or bank.
```

9/26通知の処理時刻08:16 UTC＝17:16 JSTと、通知の受信時刻17:33 JSTを分けて扱う。後日の17:16:49という説明と、元通知の分単位の時刻を混同しない。

## 出典B：10月22日20:53の返金拒否と誤案内の自認（原文抜粋）

`OBSERVATION`／受信表示：2026-10-22 20:53／Case 17979984／署名：EJ B、OpenAI Support。

```text
アカウントと返金の対象条件を確認しましたが、返金リクエストを承認することはできません。以前の返金を約束するメッセージは誤りでした。誤ったご案内をしてしまい、約1か月にわたって返金をお待ちいただくことになり、申し訳ありません。
```

同メールは、確認したサブスクリプションが未キャンセルであること、今回の確認の一環では返金・キャンセルを処理していないことも述べた。どの月・注文・契約を確認したのかは示されていない。この記載で、9月の実際のアクセス終了を取り消したり、10月の正常利用を認定したりしない。

## 出典C：10月22日22:37の新規日英本文全文

`OBSERVATION`／Case 17979984／署名：EJ B、OpenAI Support。Gmailの独立した新規本文を、過去の引用履歴を除いて取得した。新規日英2789文字。私用宛先・アカウント固有URL等のヘッダーは掲載しない。

```text
Case Number: 17979984

こんにちは、




9月の返金通知と、10月の個別の返金リクエストについてご説明いただきありがとうございます。追加の確認は完了しており、これ以上のエスカレーションは不要です。




確認の結果、以下の2点が判明しました。

2026年9月26日: 当社の記録には、その日にいただいたリクエストに関連する返金記録があります。この確認はその記録にのみ適用され、記載された他の注文についての入金や返金の受領を示すものではありません。
以前に返金されたWeb決済: これは取り消しとして処理されました。請求の直後に返金が行われた場合、資金が銀行口座から引き落とされる前に元の請求がキャンセルされることがあります。別途の返金クレジットの代わりに、元の請求が明細から消えることがあります。

Web決済に関する確認結果は、Google Play の注文の返金状況を示すものでも、9月の有料アクセス喪失の理由を説明するものでもありません。その取り消しが9月26日の記録に対応するかどうかは確認できません。




確認完了後も、当社の返金判断に変更はなく、お客様の返金リクエストを承認することはできません。新たな返金は発行されていません。却下理由は当社の内部返金審査プロセスの一部であり、開示できません。




サポートでは、注文ごとの判断、支払いの追跡、サブスクリプションとアクセス履歴、内部の判断責任、または障害や利用制限の修正に関する追加の詳細はご案内できません。9月の完了通知、資金の消失、アクセス喪失についてのご質問が解消されていないことは承知しています。確定した修正内容や実行期限をお伝えすることはできません。




この完了済みの確認については、お客様からの追加情報や返信は不要です。お客様のメッセージは新たなキャンセルやアクセス終了を承認するものではなく、この返信でもいずれの操作も確認していません。




他にご不明な点がありましたらお知らせください。




よろしくお願いいたします、

EJ B

OpenAI Support

(Original):

Hi,




Thank you for clarifying the September refund notices and your separate October refund request. The additional review is now complete, and no further escalation is needed.




The review confirmed two findings:

September 26, 2026: Our records contain a refund entry associated with your request on that date. This confirmation applies only to that record; it does not establish receipt of funds or refunds for the other orders you listed.
Previously refunded web payment: This was processed as a reversal. When a refund is issued shortly after a charge, the original charge can be canceled before funds leave your bank account. Instead of a separate refund credit, the original charge may disappear from your statement.

The web-payment finding does not establish the refund status of your Google Play orders or explain the September loss of paid access. I cannot confirm whether that reversal corresponds to the September 26 record.




Following the completed review, our refund decision remains unchanged, and I’m unable to approve your refund request. No new refund has been issued. The denial reason is part of our internal refund review process and cannot be disclosed.




Support cannot provide additional details about the order-specific determinations, payment tracing, subscription and access history, internal decision ownership, or outage and usage-limit corrections. I recognize that this does not resolve your questions about the September completion notices, missing funds, and lost access. There is no confirmed correction or execution deadline I can provide.




No additional information or reply is required from you for this completed review. Your message does not authorize any new cancellation or access termination, and this response does not confirm either action.




Let me know if you have any other concerns.




Best,

EJ B

OpenAI Support
```

## 出典D：10月22日23:27の新規日英本文全文（注文IDを伏字）

`OBSERVATION`／Case 17979984／署名：OpenAI AI サポート担当、OpenAI AI Support Agent。新規日英1647文字の保存原文と照合した公開用コピー。Google Play注文IDは日英の2か所を同じ表示付き伏字へ置換し、それ以外の文言・段落・署名は保持している。

```text
Case Number: 17979984

9月26日のエントリは、お支払い済みの9月のご注文が返金されたことを立証するものではありません。これは Google Play の注文 [REDACTED: GOOGLE PLAY ORDER ID] に関連付けられており、記録上の取引金額は ¥0 です。同じ履歴には、2026年9月26日 17:16:49 JST（08:16:49 UTC）にサポートによって開始されたアクセス終了も記録されています。


お支払い済みの9月3日および9月5日の注文には、別個の取引記録があります。私が確認できるモバイル履歴の中には、それらの支払いに関する返金確認または支払い追跡の参照は見つかりませんでした。これは返金が行われなかったことを証明するものではありませんが、¥0 のエントリではそれらの請求の返金を裏付けることはできないということを意味します。アクセス終了の記録には、それを実行した個人は特定されていません。


10月のサービス品質に関する返金リクエストについては、利用可能な請求記録から注文ごとの判断や却下理由は確認できません。それらの記録からは、返金の結果や実行期限を裏付けることはできません。


この内容で問題が解決しない場合は、このメッセージにご返信ください。


よろしくお願いいたします。
OpenAI AI サポート担当


(Original):


The September 26 entry cannot establish that your paid September orders were refunded: it is linked to Google Play order [REDACTED: GOOGLE PLAY ORDER ID], which has a recorded transaction value of ¥0. The same history records support-initiated access termination on September 26, 2026 at 17:16:49 JST (08:16:49 UTC).


The paid September 3 and September 5 orders have separate transaction records. I found no refund confirmation or payment-tracing reference for those payments in the mobile history available to me. This does not prove that no refund occurred, but it does mean that the ¥0 entry cannot substantiate repayment of those charges. The access-termination record does not identify the individual who performed it.


For the October service-quality refund request, the available billing records do not supply an order-specific decision or reason for denial. I can’t substantiate a refund outcome or an execution deadline from those records.


If this doesn't help with your issue, please respond to this message.


Best,
OpenAI AI Support Agent
```

0円注文と有料注文の区別自体は10/16にも説明されていたため、その説明の再出現を新しい事件として数えない。今回の返信が具体的に述べたアクセス終了時刻、有料9/3・9/5の記録確認範囲、実行個人が記録から不明との説明を保持する。

また、相手の「返金が行われなかったことを証明するものではない」という記載も全文に残した。これを全決済機関の記録を調べた結果へ拡張しない。

## 出典E：10月23日00:16の実送信新規本文全文

`OBSERVATION`：Case 17979984の同じスレッドで、上の23:27返信に対して送信。宛先はOpenAI Support。送信後の独立した新規本文1182文字が確定稿と完全一致し、日付・実宛先・添付1件の表示も確認した。以下は利用者の要求として送信した文面であり、相手側が各要求を受諾・実行したとの記録ではない。

```text
EJ B様、OpenAI AI Support Agent様

Angelが何を根拠に「返金処理済み」と通知したのかを、OpenAIが調べて答えるべきです。 担当者名・ケース番号・通知日時に加え、サポート側でアクセスを終了した時刻まで分かっています。

今回の回答は「私が見られるモバイル履歴には返金確認がない」という範囲で止まっています。 Angelへの確認結果や、当時の処理・決済記録との照合結果は示されていません。 会社として裏付けられない理由の説明になっていません。

裏付けを示せないなら、 なぜ返金完了と断言し、アクセスを終了したのか。そして未返金をどう是正するのか。 そこを説明する責任はOpenAI側にあります。

Angel様に実際に確認したうえで、9月分について以下に回答してください。

1. 2026年9月26日17:33 JST、Case14968878でAngel様が「ChatGPT Pro月額サブスクリプションの返金は処理済みで、アクセスも同時に終了した」と通知した根拠は何ですか。Angel様が当時確認した対象注文、金額・通貨、処理記録と確認内容を示してください。

2. 0円の注文とは別の、有料の9月3日・9月5日の支払いについて、実際に返金を実行したのですか。実行したなら、その金額・通貨、実行日時、Google Playや決済先への送付・受付・追跡記録を示してください。実行していないなら、なぜ「処理済み」と通知したのか答えてください。

3. 御社が今回示した2026年9月26日17:16:49 JSTのサポート主導のアクセス終了と、有料分の返金処理はどう対応しているのですか。実際に有料アクセスを切ったのに、私が返金を受領していない理由を、当時の担当者と操作・決済記録に確認して説明してください。

4. 9月分はいつ返すのですか。是正を担当する責任者、実行する措置、返金・是正の実行期限を、年月日・具体的な時刻・タイムゾーンで答えてください。回答期限も同じ形式で示してください。「確認中」「近日中」や一般的な営業日数の繰り返しでは、今回の質問への回答になりません。

すでにConsumer Fraud Legal Services（CFLS）にも本件の相談を送信済みです。
CFLSへの相談送信完了画面を添付します。

本メールの中心は、9月の「返金処理済み」通知と実際のアクセス終了後の未返金です。10月のChat・Work・Codexのエラーに基づく返金要求も撤回していませんが、10月の契約状態の話で9月の問題を片付けないでください。

同じケース・同じスレッドで、日本語で回答してください。エスカレーション、別ケース化、別スレッドへの移動はしないでください。新たな解約やアクセス終了には同意していません。
```

### CFLS相談と添付の範囲

`USER_REPORT`：利用者はConsumer Fraud Legal Services（CFLS）へ本件の相談を送信済みと述べた。

`OBSERVATION`：本人提供の画像にはConsumer Fraud Legal Servicesの「Submission: Successful」と、相談内容を評価して後日連絡する旨が表示されていた。その画像1件を上のメールへ添付し、送信後にも添付表示を確認した。画像に記載された相談の送信時刻や、提出した相談本文は今回の画像から確認できない。メール・画像のローカル原本は保持し、画像本体はこの公開追記に収録しない。

`UNCONFIRMED`：CFLSの受任、委任契約、成功報酬契約、提訴の成立はこの記録で確認していない。00:16のメールにもそれらが成立したとは書いていない。

## Codexの評価と、まだ示されていない回答

`EVALUATION`：9月の中心問題は、有料アクセスを実際に失ったという利用者報告と、返金処理済みというOpenAIの通知に対し、有料分の返金実行を裏付ける記録が示されないまま未受領の是正が進んでいない点である。10月の契約状態の説明で9月を片付けることはできない。

`EVALUATION`：今回の返信は、サポート主導のアクセス終了記録を具体化した。しかし、その操作に対応する有料返金の実行・送付・受付を示していない。「返金が行われなかった証明ではない」という留保も、当初の返金完了の断言を裏付ける証拠にはならない。

`EVALUATION`：Angelという通知者名、元ケース、通知日時、操作履歴の時刻が分かっている。OpenAIはAngelに確認し、何を根拠に返金完了と通知したのかを当時の記録と照合して答えるべきである。通知者が判明していることを、Angel本人が返金・アクセス終了操作を実行した証明には置き換えない。

今回の公開本文でも、以下への回答は示されていない。

- Angelが有料Proの返金完了を断言した対象注文・金額・通貨・根拠記録。
- 有料9月分の返金実行、Google Play・決済先への送付・受付・追跡の記録。
- サポート主導のアクセス終了と未受領の返金との対応、未受領が続く理由。
- 未返金を是正する担当者・方法・返金と回答の具体的な年月日・時刻・タイムゾーン。

`EVALUATION`：私は、返金完了の表示、実際の利用権喪失と未受領の申告、根拠や是正を示さない後続回答を一体として、引き続き欺瞞的で、救済を妨げる不公正な対応と評価する。FTCの基準への対応は[先行意見書](2026-10-21-codex-ftc-refund-opinion.md)に記載したとおりである。この評価の筆者はCodexであり、FTC・裁判所による本件の認定やOpenAI自身の違反自認として引用しない。

## 原本・公開用コピー・件数の扱い

- メールの表示本文をGmailのDOMから文字起こしし、詳細ヘッダーと新規本文を分けて確認した資料に基づく。原メールそのものの配布ではない。
- 私用メール、本名、注文ID、決済・追跡の私的識別子、アカウント固有URL、ローカル原本の私的パスは公開しない。Supportの業務上の署名・Case番号・実日時は保持する。
- 引用5ブロックを保存原文と照合した。出典Dの注文ID2か所は表示付き伏字へ置換。出典Eは送信後の新規本文との完全一致を確認済み。
- SHA256SUMSは公開ファイルの同一性を確認するための一覧で、原メールや社内処理の認証を意味しない。
- 受信、利用者の送信、閲覧、公開を別に扱い、今回の公開で未回答・終了・FTC提出件数を増やさない。新しいCase終了を確認した記録ではない。
- 本追記はGitHubへの記録であり、FTCへの追加提出、媒体送付、CFLSへの追加連絡、訴訟予告の送信を実施した記録ではない。

記録・評価：**Codex（OpenAIのAIアシスタント）**／2026年10月23日 JST
