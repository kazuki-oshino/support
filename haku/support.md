# サポート / Support

## HAKU（はく） / HAKU

数息観と丹田呼吸 ― 日本の呼吸法を実践するブレスワークアプリ

Japanese breathwork — susokukan and tanden breathing

---

## よくある質問 / FAQ

### Q: データはどこに保存されますか？

A: 保存した実践記録、状態チェックインの値、平均呼気秒数や安静時呼吸数チェックの結果は、デバイス内にのみ保存されます。記録そのものや呼吸の生データを外部サーバーへ送信せず、アカウント登録やクラウド同期もありません。これとは別に、AdMobによる広告関連情報・診断情報と、Firebaseによる利用イベント・診断情報などの収集があります。利用イベントには実践時間や呼吸回数などの要約が含まれますが、チェックインの値や呼吸の生データは含まれません。詳細は[プライバシーポリシー](privacy.md)をご確認ください。

### Q: Where is my data stored?

A: Saved practice records, state check-in values, average exhale duration, and resting respiratory rate check results are stored only on your device. The records themselves and raw breathing data are not sent to external servers. There is no account registration or cloud sync. Separately, AdMob collects advertising and diagnostic information, and Firebase collects usage events, diagnostics, and related information. Usage events include summaries such as practice duration and breath count, but not check-in values or raw breathing data. See our [Privacy Policy](privacy.md) for details.

---

### Q: 無料で使える機能は何ですか？

A: 数息観・丹田呼吸・長息などのガイド付き実践、音と振動によるペーシング、草ヒートマップ・ストリーク、平均呼気秒数や安静時呼吸数チェックなど、すべての機能を無料で利用できます。広告が表示されますが、実践中には表示されません。有料なのは広告削除のみで、サブスクリプションはありません。

### Q: What features are available for free?

A: All features are free, including guided practice in susokukan, tanden breathing, long-exhale breathing, and other forms; audio and haptic pacing; practice heatmaps and streaks; average exhale duration; and resting respiratory rate checks. Ads are displayed, but never during practice. The only paid option is ad removal, and there are no subscriptions.

---

### Q: 広告を削除するには？

A: 設定画面の広告削除の項目から、買い切りのアプリ内課金を購入してください。一度の購入ですべての広告が非表示になります。継続的な支払いや自動更新はありません。

### Q: How do I remove ads?

A: Open the ad-removal option in Settings and make the one-time in-app purchase. All ads are removed after purchase. There are no recurring payments or automatic renewals.

---

### Q: 購入を復元するには？

A: 購入時と同じApple ID（Apple Account）でサインインし、設定画面の広告削除の項目から購入の復元を行ってください。広告削除の復元は、端末内の実践記録を復元・同期するものではありません。

### Q: How do I restore my purchase?

A: Sign in with the same Apple ID (Apple Account) used for the purchase, then use the restore option under ad removal in Settings. Restoring ad removal does not restore or synchronize locally stored practice records.

---

### Q: 広告を削除すると、情報の収集もすべて止まりますか？

A: 広告削除の購入後は広告リクエストを行わず、広告SDK経由の新たな情報収集は停止します。ただし、Firebase Analyticsによる利用状況の計測、Crashlyticsによる診断情報の収集、Remote Configによる設定取得は継続します。広告が表示されなくなるため、広告表示に関するイベントは発生しなくなります。

### Q: Does removing ads stop all data collection?

A: After purchase, the App stops making ad requests and stops new information collection through the advertising SDK. Firebase Analytics usage measurement, Crashlytics diagnostic collection, and Remote Config configuration retrieval continue. Ad-impression events no longer occur because ads are no longer displayed.

---

### Q: 実践記録をエクスポート・削除するには？

A: 設定画面のデータの項目から、記録をCSVまたはJSON形式でエクスポートしたり、端末内の記録をすべて削除したりできます。残しておきたい記録は、削除前にエクスポートしてください。端末内の記録の削除は、すでにSDKを通じて送信された情報の削除を意味するものではありません。

### Q: How do I export or delete practice records?

A: In the data section of Settings, you can export records as CSV or JSON, or delete all locally stored records. Export records you want to keep before deleting them. Deleting local records does not delete information already sent through the SDKs.

---

### Q: メトリクスで健康状態を判断できますか？

A: 平均呼気秒数や安静時呼吸数チェックは、実践を振り返るための目安です。診断や治療のための測定ではなく、健康状態や呼吸法の効果を保証するものでもありません。数値を伸ばすために無理をせず、健康上の懸念がある場合は医師に相談してください。

### Q: Can I use the metrics to assess my health?

A: Average exhale duration and resting respiratory rate checks are guides for reviewing your practice. They are not measurements for diagnosis or treatment and do not guarantee health status or benefits from breathing exercises. Do not push yourself to improve a number. Consult a physician if you have health concerns.

---

## 健康・安全に関する注意事項 / Health and Safety Notice

本アプリは医療アプリ・医療機器ではなく、医療行為、診断、治療、医療的助言を提供するものではありません。呼吸法の効果や健康状態の改善を保証しません。

- 妊娠中、てんかん・けいれんの既往、コントロールされていない高血圧、心血管疾患・脳卒中の既往、網膜剥離、最近の手術などに該当する場合は、利用前に医師へ相談してください。これらに該当する場合、過換気を伴う呼吸法や長い息止めは行わないでください。
- 運転中、入浴中、水中や水の近くでは行わないでください。強い呼吸法は座るか横になった姿勢でのみ行い、無理に力んだり息を止めたりしないでください。
- めまい・しびれ・気分不良を感じたら直ちに中止し、通常の呼吸に戻してください。症状が続く場合は医師に相談してください。

The App is not a medical app or medical device and does not provide medical care, diagnosis, treatment, or medical advice. It does not guarantee benefits from breathing exercises or improvements in health.

- If you are pregnant, have a history of epilepsy or seizures, uncontrolled high blood pressure, cardiovascular disease or stroke, retinal detachment, or recent surgery, consult a physician before use. If any of these apply, do not perform hyperventilation-based exercises or prolonged breath holds.
- Do not practice while driving, bathing, underwater, or near water. Perform intense breathing exercises only while seated or lying down, and do not strain or force breath holds.
- If you feel dizzy, numb, or unwell, stop immediately and return to normal breathing. Consult a physician if symptoms persist.

---

## お問い合わせ / Contact

不具合の報告やご要望がございましたら、以下のメールアドレスまでお問い合わせください。

For bug reports or feature requests, please contact us at the email address below.

📧 **techgamelife.net@gmail.com**

---

## アプリ情報 / App Information

- **開発者 / Developer**: techgamelife
- **対象年齢 / Minimum age**: 13歳以上 / 13 and older
- **プライバシーポリシー / Privacy Policy**: [こちら / Click here](privacy.md)
- **利用規約 / Terms of Service**: [こちら / Click here](terms.md)
