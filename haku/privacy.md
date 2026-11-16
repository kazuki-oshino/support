# プライバシーポリシー

最終更新日: 2026年11月16日

## はじめに

HAKU（はく）（以下「本アプリ」）は、ユーザーのプライバシーを尊重し、個人情報の保護に努めています。本プライバシーポリシーでは、本アプリがどのような情報を収集し、どのように使用するかについて説明します。

## 収集する情報

### 実践データ

本アプリで保存した実践記録、状態チェックインの値、平均呼気秒数、安静時呼吸数チェックの結果などは、お使いのデバイス内にのみ保存されます。保存した記録そのものや呼吸の生データを、開発者や外部サービスのサーバーへ送信することはありません。記録は設定画面からエクスポート・削除できます。エクスポートしたファイルの保存先や共有先は、ユーザーが選択します。

本アプリにアカウント登録はありません。Firebase FirestoreおよびFirebase Authenticationは使用せず、実践データのクラウド同期も行いません。開発者が独自のサーバーでユーザーデータを収集・保存することはなく、アプリの利用に伴う情報収集は、以下のAdMobとFirebaseのSDKを通じて行われます。端末内の記録とは別に、実践時間や呼吸回数などの要約を含む利用イベントをFirebase Analyticsへ送信します。詳細は「利用状況および分析情報」をご確認ください。

### 広告に関する情報

本アプリでは、Google AdMobを使用して広告を表示しています。AdMobは、広告の配信・効果測定、分析、品質改善のために以下の情報を収集する場合があります：

- デバイス識別子（広告識別子IDFAなど）
- IPアドレス、およびそこから推定されるおおよその地域
- 広告の表示・クリックなどの利用状況
- クラッシュログやパフォーマンスなどの診断情報

IDFAの取得および広告目的のトラッキングは、App Tracking Transparency（ATT）で許可された場合に限ります。詳細については、[Googleのプライバシーポリシー](https://policies.google.com/privacy)および[AdMobのデータ収集に関する説明](https://developers.google.com/admob/ios/privacy/data-disclosure)をご確認ください。

### App Tracking Transparency

広告のパーソナライズのために、最初の実践を完了した後、事前説明に続いてトラッキングの許可をお願いする場合があります。この許可は任意です。拒否した場合はIDFAを使用せず、非パーソナライズ広告を表示します。すべての機能を引き続きご利用いただけます。

ATTの拒否は、広告配信に必要な情報や、以下に説明するFirebaseの利用状況・診断情報の収集をすべて停止するものではありません。トラッキングの許可はiOSの「設定」→「プライバシーとセキュリティ」→「トラッキング」から変更できます。広告に関する同意は、本アプリの設定画面からも見直せます。ATTの詳細は[Appleの案内](https://support.apple.com/102420)をご確認ください。

### 利用状況および分析情報

本アプリでは、継続して利用されているか、広告表示が実践の継続を妨げていないかを把握するために、Firebase Analyticsを使用します。以下のような行動イベントと、それに付随する情報を収集します：

- 初回起動、実践の開始・完了・中断
- 選択した呼吸法・段階、予定時間・実践時間、完了率、呼吸回数などの利用の要約
- 状態チェックインを使用したことと実践前後の区分（入力した値は含みません）、連続実践日数の節目
- 広告の表示・終了・表示見送り、広告削除の購入・復元、ATTへの回答状況、リマインダーの設定状況・時刻
- IDFAとは別の匿名のインストールID、およびアプリのバージョン、デバイスの種類、OSなどの技術情報

状態チェックインの値、呼吸の生データ、平均呼気秒数、安静時呼吸数チェックの結果は、Firebase Analyticsへ送信しません。収集した利用イベントは継続率や使い方の分析に使用し、他社のアプリ・ウェブサイトを横断するトラッキングや広告のパーソナライズには使用しません。

### クラッシュ・診断情報

本アプリでは、不具合の把握と品質改善のためにFirebase Crashlyticsを使用します。クラッシュ情報、アプリ・OS・デバイスに関する情報、インストールを識別する情報などの診断データを収集します。状態チェックインの値や呼吸の生データを診断情報として送信することはありません。

### アプリ設定の配信

本アプリでは、Firebase Remote Configを使用して、対応バージョン・推奨バージョンや広告頻度の設定を取得します。このサービスは設定を配信するためにFirebaseのインストール識別子などを使用します。実践記録を保存・同期するためのものではありません。Firebaseによる情報の取り扱いについては、[Firebaseのプライバシーとセキュリティ](https://firebase.google.com/support/privacy)をご確認ください。

## 情報の利用目的

収集した情報は、以下の目的で利用されます：

- 広告の表示・効果測定および最適化（パーソナライズは許可された場合のみ）
- アプリの継続率・利用状況や、広告表示による影響の分析
- クラッシュや不具合の調査、および機能・品質の改善
- バージョンに応じた更新案内や広告頻度などの設定の配信

## 第三者への提供

本アプリは、上記の目的のためにGoogle AdMob、Firebase Analytics、Firebase Crashlytics、Firebase Remote Configを利用しています。これらのサービスは、各サービスのプライバシーポリシーに従って情報を処理します。本アプリはユーザーの個人情報を販売しません。法令に基づく場合を除き、上記の目的以外で第三者へ提供することはありません。

## アプリ内課金

本アプリの機能はすべて無料で利用でき、課金は広告を削除するための買い切り型のアプリ内課金1件のみです。サブスクリプションはありません。決済はAppleが処理し、クレジットカード情報などの支払情報を本アプリが直接収集することはありません。広告削除の購入状態は端末上で確認します。購入・復元が行われたことは、上記の利用イベントに含まれます。

**広告削除の購入後は広告リクエストを行わず、広告SDK経由の新たな情報収集は停止します。一方、Firebase Analyticsによる利用状況の計測は継続します。** 広告が表示されなくなるため、広告表示に関するイベントは発生しなくなります。Firebase Crashlyticsによる診断情報の収集とRemote Configによる設定取得も、広告削除とは別に継続します。

## 健康・安全に関する免責事項

本アプリは医療アプリ・医療機器ではなく、医療行為、診断、治療、医療的助言を提供するものではありません。呼吸法の効果や健康状態の改善を保証しません。表示されるメトリクスを医療上の判断に使用しないでください。

妊娠中、てんかん・けいれんの既往、コントロールされていない高血圧、心血管疾患・脳卒中の既往、網膜剥離、最近の手術などに該当する場合は、利用前に医師へ相談し、過換気を伴う呼吸法や長い息止めは行わないでください。

運転中、入浴中、水中や水の近くでは行わないでください。強い呼吸法は座るか横になった姿勢でのみ行い、無理に力んだり息を止めたりしないでください。めまい・しびれ・気分不良を感じたら直ちに中止し、通常の呼吸に戻してください。症状が続く場合は医師に相談してください。

## お子様のプライバシー

本アプリの利用対象は13歳以上です。13歳未満のお子様から意図的に個人情報を収集することはありません。

## プライバシーポリシーの変更

本プライバシーポリシーは、必要に応じて更新されることがあります。重要な変更がある場合は、本ページにて通知します。

## お問い合わせ

プライバシーに関するご質問やご懸念がございましたら、[サポートページ](support.md)または以下のメールアドレスよりお問い合わせください。

📧 **techgamelife.net@gmail.com**

---

# Privacy Policy

Last updated: November 16, 2026

## Introduction

HAKU ("the App") respects your privacy and is committed to protecting your personal information. This Privacy Policy explains what information we collect and how we use it.

## Information We Collect

### Practice Data

Saved practice records, state check-in values, average exhale duration, and resting respiratory rate check results are stored only on your device. We do not transmit the saved records themselves or raw breathing data to developer-operated or external service servers. You can export or delete records from Settings. You choose where to save or share exported files.

The App does not require an account. It does not use Firebase Firestore or Firebase Authentication, or synchronize practice data to the cloud. The developer does not independently collect or store user data on its own servers. Information collection during app use takes place through the AdMob and Firebase SDKs described below. Separately from your locally stored records, usage events sent to Firebase Analytics include summaries such as practice duration and breath count. See "Usage and Analytics Information" for details.

### Advertising Information

The App uses Google AdMob to display advertisements. AdMob may collect the following information for ad delivery, measurement, analytics, and quality improvements:

- Device identifiers, such as the advertising identifier (IDFA)
- IP address and the approximate region inferred from it
- Usage information, such as ad impressions and clicks
- Diagnostic information, such as crash logs and performance data

Access to the IDFA and tracking for advertising purposes require your permission through App Tracking Transparency (ATT). For details, please review [Google's Privacy Policy](https://policies.google.com/privacy) and [AdMob's data collection disclosure](https://developers.google.com/admob/ios/privacy/data-disclosure).

### App Tracking Transparency

After your first completed practice session, we may show an explanation and request permission to track activity for ad personalization. Permission is optional. If you decline, the App does not use the IDFA and displays non-personalized ads. All features remain available.

Declining ATT does not stop all collection of information needed to deliver ads or the Firebase usage and diagnostic information described below. You can change tracking permission in iOS Settings → Privacy & Security → Tracking. You can also review advertising consent in the App's Settings. For more about ATT, see [Apple's guidance](https://support.apple.com/102420).

### Usage and Analytics Information

The App uses Firebase Analytics to understand continued use and whether advertising interferes with maintaining a practice habit. We collect interaction events and related information such as:

- First launch, and practice session starts, completions, and interruptions
- Usage summaries including the selected breathing form and stage, planned and actual duration, completion rate, and breath count
- Whether check-ins are used and whether they occur before or after practice (without the entered values), and practice streak milestones
- Ads shown, dismissed, or skipped; ad-removal purchases and restorations; ATT permission status; and reminder settings and time
- An anonymous installation ID separate from the IDFA, and technical information such as app version, device type, and operating system

We do not send state check-in values, raw breathing data, average exhale duration, or resting respiratory rate check results to Firebase Analytics. Usage events are used to analyze retention and app usage, not for tracking across other companies' apps or websites or for ad personalization.

### Crash and Diagnostic Information

The App uses Firebase Crashlytics to identify problems and improve quality. It collects diagnostic data such as crash information, app, operating system and device information, and installation identifiers. We do not send state check-in values or raw breathing data as diagnostic information.

### App Configuration

The App uses Firebase Remote Config to obtain supported and recommended app versions and settings such as ad frequency. This service uses information such as Firebase installation identifiers to deliver configuration values. It does not store or synchronize practice records. For details on Firebase's handling of information, see [Privacy and Security in Firebase](https://firebase.google.com/support/privacy).

## How We Use Information

The information collected is used for the following purposes:

- Delivering, measuring, and optimizing ads (with personalization only when permitted)
- Analyzing retention, app usage, and the impact of advertising
- Investigating crashes and other problems, and improving features and quality
- Delivering configuration settings such as update guidance and ad frequency

## Disclosure to Third Parties

The App uses Google AdMob, Firebase Analytics, Firebase Crashlytics, and Firebase Remote Config for the purposes described above. These services process information according to their respective privacy policies. The App does not sell your personal information or disclose it to third parties for purposes other than those described above, except as required by law.

## In-App Purchases

All app features are free. The only in-app purchase is a single one-time purchase to remove ads. There are no subscriptions. Apple processes payments; the App does not directly collect payment details such as credit card information. Ad-removal purchase status is checked on your device. Purchase and restoration events are included in the usage events described above.

**After you purchase ad removal, the App stops making ad requests and stops new information collection through the advertising SDK. Firebase Analytics usage measurement continues.** Ad-impression events no longer occur because ads are no longer displayed. Firebase Crashlytics diagnostic collection and Remote Config configuration retrieval also continue independently of ad removal.

## Health and Safety Disclaimer

The App is not a medical app or medical device and does not provide medical care, diagnosis, treatment, or medical advice. It does not guarantee benefits from breathing exercises or improvements in health. Do not use its metrics to make medical decisions.

If you are pregnant, have a history of epilepsy or seizures, uncontrolled high blood pressure, cardiovascular disease or stroke, retinal detachment, or recent surgery, consult a physician before use and do not perform hyperventilation-based exercises or prolonged breath holds.

Do not practice while driving, bathing, underwater, or near water. Perform intense breathing exercises only while seated or lying down, and do not strain or force breath holds. If you feel dizzy, numb, or unwell, stop immediately and return to normal breathing. Consult a physician if symptoms persist.

## Children's Privacy

The App is intended for people aged 13 and older. It does not knowingly collect personal information from children under 13.

## Changes to This Policy

This Privacy Policy may be updated as needed. Significant changes will be announced on this page.

## Contact Us

If you have any questions or concerns about privacy, please contact us through the [support page](support.md) or at the email address below.

📧 **techgamelife.net@gmail.com**
