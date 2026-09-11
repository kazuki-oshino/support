# プライバシーポリシー

最終更新日: 2026年9月11日

## はじめに

のこりび（以下「本アプリ」）は、ユーザーのプライバシーを尊重し、個人情報の保護に努めています。本プライバシーポリシーでは、本アプリがどのような情報を収集し、どのように使用するかについて説明します。

## 収集する情報

### プロフィールデータ
本アプリでは、以下のプロフィール情報を登録いただきます：

- ニックネーム
- 生年月日
- 性別
- カスタム目標日（設定した場合）

これらのプロフィールデータは、お使いのデバイス内とFirebase Firestoreに保存されます。ソロモードでもオンライン保存を行い、パートナー連携中は共有用のプロフィールも保存します。

### Firebase Anonymous Authentication
本アプリでは、Firebase Anonymous Authenticationを使用し、メールアドレスやパスワードの登録は求めません。匿名の利用者IDが生成され、本人のプロフィール・本文・設定・記念日の保存・取得と、パートナー連携中のデータ共有に使用されます。保存・復旧の対象は、以下に記載するアプリのバージョンと条件によって異なります。Appleでのサインインは提供していません。

### 利用状況および分析情報
本アプリでは、利用状況を把握して機能や品質を改善するためにFirebase Analyticsを使用しています。Firebase Analyticsでは、以下の情報を収集します：

- アプリの起動、オンボーディング完了、各機能の利用、購入フローの結果などの操作イベント
- アプリのバージョン、デバイスの種類、OSなどの技術情報
- アプリのインストール単位で生成される匿名の識別子
- IPアドレスから推定されるおおよその地域

ニックネーム、生年月日、性別、Firebase UID、カップルID、パートナーUID、招待コード、バケットリストや共有やることの本文、コメント、記念日のタイトル・日付、写真、その他の自由入力内容は、Firebase Analyticsへ送信しません。Firebase Analyticsで収集した情報は、広告のパーソナライズには使用しません。

アカウントを削除した場合、本アプリはデバイス上のAnalytics識別子をリセットします。すでに送信された情報は、Googleのデータ保持方針に従って保持される場合があります。詳細については、[Googleのプライバシーポリシー](https://policies.google.com/privacy)をご確認ください。

### バケットリストデータ
v1.12以降では、本アプリで作成されたバケットリスト（やりたいことリスト）と達成記録の本文を、デバイス内とFirebase Firestoreに保存します。本文には、タイトル、期限、カテゴリ、達成日、コメントなどが含まれます。ソロモードでは本人の個人領域に保存します。パートナー連携中は共有領域に保存し、現在のパートナーと共有します。Memory Lineは達成済みの本文から表示します。端末内の達成写真は、この本文のオンライン保存には含めません。

v1.11以前のソロモードには、本文を個人領域へオンライン保存する機能はありません。パートナー連携中は、Firebase Firestoreで本文を共有します。

### 利用者設定
v1.12以降では、選択したテーマ、残り時間の表示単位、記念日の表示範囲を、デバイス内とFirebase Firestoreの本人専用領域に保存します。v1.11以前では、これらの設定を本人専用領域へオンライン保存する機能はありません。Proの購入資格はAppleで確認します。

### 共有TODO
共有TODOのタイトル、完了状態、並び順などは、現在のパートナーと使うリストとしてFirebase Firestoreに保存します。個人用のバックアップは作りません。

### 記念日データ
本アプリで作成された記念日のタイトル、日付、カバー画像に関する情報は、個人用・共有用ともにFirebase FirestoreおよびFirebase Storageへ保存されます。個人用の記念日は作成したユーザー本人だけが利用でき、共有用の記念日は現在連携しているパートナーと共有されます。これらの情報は、記念日の表示・編集・保存、およびパートナーとの共同編集に使用されます。

### 写真データ
達成記録に添付された写真は、通常お使いのデバイス内にのみ保存されます。オンライン写真共有を有効にした場合、ユーザーが共有を選んだ達成写真のみFirebase Storageに保存され、共有状態などのメタデータはFirebase Firestoreに保存されます。記念日のカバー画像は、個人用・共有用ともにFirebase Storageへ保存されます。共有写真および共有用記念日のカバー画像は、現在のパートナーがオンライン閲覧できます。

### 写真共有の報告情報
パートナーから共有された写真を報告した場合、報告対象の写真ID、バケットリスト項目ID、匿名ユーザーID、報告日時、報告状態などの情報をFirebase Firestoreに保存します。これらの情報は、報告した写真をあなたの画面で非表示にすること、不適切な共有写真の確認、および安全なサービス運営のために使用されます。

### 広告に関する情報
本アプリでは、Google AdMobを使用して広告を表示しています。AdMobは、広告のパーソナライズのために以下の情報を収集する場合があります：

- デバイス識別子
- IPアドレス
- 広告の表示・クリックに関する情報

詳細については、[Googleのプライバシーポリシー](https://policies.google.com/privacy)をご確認ください。

### App Tracking Transparency
iOS 14.5以降では、広告のパーソナライズのためにトラッキングの許可をお願いする場合があります。この許可は任意であり、許可しなくてもアプリは正常に動作します。

## 情報の利用目的

収集した情報は、以下の目的で利用されます：

- 本人のプロフィール・本文・設定の保存と、同じ匿名識別子で認証できる場合の保存済みデータの取得
- カップルモードでのパートナーとのデータ共有
- 記念日の表示・編集・保存、およびパートナーとの共同編集
- オンライン写真共有の提供、報告対応、不適切な共有写真の確認
- アプリの利用状況の分析および機能・品質の改善
- 広告の表示および最適化

## 第三者への提供

本アプリは、認証、記念日を含むデータの保存・同期、オンライン写真共有、利用状況の分析、広告表示のために、Firebase、Google Analytics、Google AdMobなどの第三者サービスを利用しています。これらのサービスは、各サービスのプライバシーポリシーに従って情報を処理する場合があります。本アプリはユーザーの個人情報を販売しません。法令に基づく場合を除き、上記の目的以外で第三者へ提供することはありません。

## アプリ内課金

本アプリでは、Pro機能をご利用いただくためのサブスクリプションおよび買い切り課金を提供しています。課金情報はAppleによって処理され、本アプリが直接収集することはありません。

## 復旧、連携解除、アカウント削除

以下は、v1.12以降で行う保存済み本文・設定の復旧、本文の引継ぎ、削除処理についての説明です。

オンラインからの復旧には、同じ匿名識別子で認証され、対象データがサーバーに保存済みである必要があります。新しい端末でデータを復旧するためのログイン機能は未提供です。未送信の変更や端末内だけの達成写真は、データのない端末へオンライン復旧できません。OSの移行で写真ファイルと対応する参照が揃って残った場合は保持しますが、OS移行や認証の回復を保証するものではありません。

連携解除時は、共有していたバケットリストと達成記録の本文を変更できない状態で残し、それぞれが接続したときに本人の個人領域へ引き継ぎます。共有TODO・共有記念日・共有カバーは削除処理の対象となり、共有写真の閲覧は停止します。個人の記念日・カバーと端末内の達成写真は連携解除だけでは削除しません。

アカウント削除時は、本人のプロフィール・個人本文・設定・移行用の記録・個人記念日・カバーなどのクラウドデータ、認証アカウント、端末内の本人データを順に削除します。共有本文は元パートナーが引き継ぐ記録として、元の追加者の匿名識別子を含めて残ります。

削除したアカウントへのデータ再作成を防ぐため、匿名識別子に対応する削除済みの記録を保持します。削除処理中は再開に必要な共有先などを保持しますが、削除完了後に残す最小の記録には本文・設定・共有先を含めません。

削除途中の失敗時は処理を再試行し、端末の片付けまで成功してから完了とします。共有データの削除処理の失敗により、オンラインにデータが残る場合があります。共有の閲覧停止と、すべての保存領域からの物理的な消去は同じ意味ではありません。

## お子様のプライバシー

本アプリは、13歳未満のお子様から意図的に個人情報を収集することはありません。

## プライバシーポリシーの変更

本プライバシーポリシーは、必要に応じて更新されることがあります。重要な変更がある場合は、本ページにて通知します。

## お問い合わせ

プライバシーに関するご質問やご懸念がございましたら、以下のメールアドレスまでお問い合わせください。

📧 **techgamelife.net@gmail.com**

---

# Privacy Policy

Last updated: September 11, 2026

## Introduction

Nokoribi ("the App") respects your privacy and is committed to protecting your personal information. This Privacy Policy explains what information we collect and how we use it.

## Information We Collect

### Profile Data
The App requires the following profile information:

- Nickname
- Date of birth
- Gender
- Custom target date (if you set one)

This profile data is stored on your device and in Firebase Firestore, including in Solo Mode. A shared profile is also stored while you are linked with a partner.

### Firebase Anonymous Authentication
The App uses Firebase Anonymous Authentication and does not require you to register an email address or password. An anonymous user identifier is generated and used to store and retrieve your profile, text records, preferences and anniversaries, and to share data while linked with a partner. Storage and recovery depend on the app version and conditions described below. Sign in with Apple is not provided.

### Usage and Analytics Information
The App uses Firebase Analytics to understand usage and improve its features and quality. Firebase Analytics collects the following information:

- Interaction events such as app launches, onboarding completion, feature usage, and purchase-flow results
- Technical information such as the app version, device type, and operating system
- An anonymous identifier generated for each app installation
- Approximate region inferred from the IP address

We do not send nicknames, dates of birth, gender, Firebase UIDs, couple IDs, partner UIDs, invite codes, bucket-list or shared-to-do text, comments, anniversary titles or dates, photos, or any other free-form content to Firebase Analytics. Information collected through Firebase Analytics is not used for ad personalization.

When you delete your account, the App resets the Analytics identifier stored on your device. Previously transmitted information may be retained in accordance with Google's data-retention practices. For more details, please review [Google's Privacy Policy](https://policies.google.com/privacy).

### Bucket List Data
In v1.12 and later, bucket-list and achievement text created in the App is stored on your device and in Firebase Firestore. These records include titles, deadlines, categories, completion dates and comments. In Solo Mode, records are stored in your personal area. While linked with a partner, records are stored in the shared area and shared with your current partner. Memory Line displays completed records from this text. This online text storage does not include achievement photos stored on your device.

In v1.11 and earlier, Solo Mode does not provide online storage of text records in a personal area. While linked with a partner, text records are shared through Firebase Firestore.

### User Preferences
In v1.12 and later, your chosen theme, countdown unit and anniversary-view selection are stored on your device and in your private area in Firebase Firestore. In v1.11 and earlier, these preferences are not saved online in a private area. Pro entitlement is checked with Apple.

### Shared To-Dos
Shared to-do titles, completion status and ordering are stored in Firebase Firestore as a list for your current partnership. A personal backup is not created.

### Anniversary Data
Anniversary titles, dates, and cover-image information created in the App are stored in Firebase Firestore and Firebase Storage for both personal and shared anniversaries. Personal anniversaries are available only to the user who created them, while shared anniversaries are shared with the currently linked partner. This information is used to display, edit, and store anniversaries and to support collaborative editing with a partner.

### Photo Data
Photos attached to achievement records are usually stored only on your device. If you enable online photo sharing, only the achievement photos you choose to share are stored in Firebase Storage, and metadata such as sharing status is stored in Firebase Firestore. Anniversary cover images are stored in Firebase Storage for both personal and shared anniversaries. Shared photos and cover images for shared anniversaries can be viewed online by your current partner.

### Shared Photo Reports
If you report a photo shared by your partner, we store information such as the reported photo ID, bucket list item ID, anonymous user IDs, report date, and report status in Firebase Firestore. This information is used to hide the reported photo from your screen, review inappropriate shared photos, and operate the service safely.

### Advertising Information
The App uses Google AdMob to display advertisements. AdMob may collect the following information for ad personalization:

- Device identifiers
- IP address
- Information about ad impressions and clicks

For more details, please review [Google's Privacy Policy](https://policies.google.com/privacy).

### App Tracking Transparency
On iOS 14.5 and later, we may request permission for tracking to personalize ads. This permission is optional, and the App will function normally even if you decline.

## How We Use Information

The information collected is used for the following purposes:

- Storing your profile, text records and preferences, and retrieving saved data when authenticated with the same anonymous identifier
- Sharing data with your partner in Couple Mode
- Displaying, editing, and storing anniversaries and supporting collaborative editing with a partner
- Providing online photo sharing, handling reports, and reviewing inappropriate shared photos
- Analyzing app usage and improving features and quality
- Displaying and optimizing advertisements

## Disclosure to Third Parties

The App uses third-party services such as Firebase, Google Analytics, and Google AdMob for authentication, storage and synchronization of data including anniversaries, online photo sharing, usage analytics, and advertising. These services may process information according to their respective privacy policies. The App does not sell your personal information or disclose it to third parties for purposes other than those described above, except as required by law.

## In-App Purchases

The App offers subscriptions and a one-time purchase to access Pro features. Payment information is processed by Apple and is not collected directly by the App.

## Recovery, Unlinking and Account Deletion

The following describes recovery of saved text records and preferences, transfer of text records, and deletion in v1.12 and later.

Online recovery requires authentication with the same anonymous identifier and data already saved to the server. A login for recovering data on a new device is not provided. Unsent changes and achievement photos stored only on your device cannot be recovered online onto an empty device. If an OS transfer preserves both photo files and their matching references, the App retains them; this does not guarantee OS transfer or recovery of authentication.

Unlinking preserves shared bucket-list and achievement text in a read-only state. When each person connects, the App transfers this text to their personal area. Shared to-dos, shared anniversaries and shared covers are subject to deletion, and viewing shared photos stops. Unlinking alone does not delete personal anniversaries, personal covers or achievement photos stored on your device.

Account deletion removes your cloud profile, personal text, preferences, transfer records, personal anniversaries and covers, followed by your authentication account and personal data on the device. Shared text remains for your former partner to inherit, including the original contributor’s anonymous identifier.

A deleted-account record associated with your anonymous identifier is retained to prevent data from being recreated for that account. During deletion, information such as the former sharing destination is retained to allow the process to resume. The minimal record retained after deletion is complete contains no text, preferences or sharing destination.

Interrupted deletion can be retried and is completed only after device cleanup succeeds. Failures while deleting shared data may leave data online. Stopping shared access does not mean physical erasure from every storage location.

## Children's Privacy

The App does not knowingly collect personal information from children under 13.

## Changes to This Policy

This Privacy Policy may be updated as needed. Significant changes will be announced on this page.

## Contact Us

If you have any questions or concerns about privacy, please contact us at the email address below.

📧 **techgamelife.net@gmail.com**
