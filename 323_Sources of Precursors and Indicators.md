### 3.2.3 Sources of Precursors and Indicators 
### 3.2.3 前兆と兆候のソース

Precursors and indicators are identified using many different sources, with the most common being computer security software alerts, logs, publicly available information, and people.  
前兆と兆候は、多くの異なるソースを使用して特定されますが、最も一般的なものは、コンピュータセキュリティソフトウェアの警告、ログ、公開されている情報及び人です。 

Table 3-2 lists common sources of precursors and indicators for each category.  
表 3-2 に、各カテゴリの前兆と兆候の一般的なソースを示します。  

Alerts  
アラート  

|Source ソース     | Description 説　明   |  
|----------- |----------------|
|IDPSs<br/>侵入検知・防止システム|IDPS products identify suspicious events and record pertinent data regarding them, including the date and time the attack was detected, the type of attack, the source and destination IP addresses, and the username (if applicable and known).<br/>IDPS 製品は不審なイベントを識別し、攻撃が検出された日時、攻撃の種類、送信元と送信先の IP アドレス、ユーザー名（該当する場合は既知のもの）など、不審なイベントに関する関連データを記録します。<br/>Most IDPS products use attack signatures to identify malicious activity;<br/>ほとんどのIDPS製品では、攻撃シグネチャを使用して悪意のある活動を識別しています。<br/>the signatures must be kept up to date so that the newest attacks can be detected.<br/>最新の攻撃を検出できるように、シグネチャを常に最新の状態に保つ必要があります。<br/>IDPS software often produces false positives—alerts that indicate malicious activity is occurring, when in fact there has been none.<br/>IDPSソフトウェアは、悪意のある活動が発生していることを示す偽のポジティブアラートを生成しますが、実際には何も発生していないことがしばしばあります。<br/>Analysts should manually validate IDPS alerts either by closely reviewing the recorded supporting data or by getting related data from other sources.3<br/>アナリストは、記録されたサポートデータを精査するか、他のソースから関連データを入手してIDPSアラートを手動で検証する必要があります。|
|SIEMs<br/>シーム| Security Information and Event Management (SIEM) products are similar to IDPS products, but they generate alerts based on analysis of log data (see below).<br/>セキュリティ情報・イベント管理（SIEM）製品はIDPS製品と似ていますが、ログデータの解析に基づいてアラートを生成します（後述）。 |
|Antivirus and antispam software<br/>ウイルス対策およびアンチスパムソフトウェア|Antivirus software detects various forms of malware, generates alerts, and prevents the malware from infecting hosts.<br/>ウイルス対策ソフトは、様々な形態のマルウェアを検出し、アラートを生成し、マルウェアがホストに感染するのを防ぎます。<br/>Current antivirus products are effective at stopping many instances of malware if their signatures are kept up to date.<br/>現在のウイルス対策製品は、マルウェアのシグネチャが最新の状態に保たれていれば、多くのマルウェアのインスタンスを停止させる効果があります。<br/>Antispam software is used to detect spam and prevent it from reaching users’ mailboxes.<br/>スパム対策ソフトは、スパムを検出し、ユーザーのメールボックスに届かないようにします。<br/>Spam may contain malware, phishing attacks, and other malicious content, so alerts from antispam software may indicate attack attempts. <br/>スパムにはマルウェアやフィッシング攻撃、その他の悪質なコンテンツが含まれている可能性があるため、スパム対策ソフトからの警告は攻撃の企図を示している可能性があります。|
|File integrity checking software<br/>ファイル完全性チェックソフトウェア|File integrity checking software can detect changes made to important files during incidents.<br/> ファイル完全性チェックソフトウェアは、インシデント時に重要なファイルに加えられた変更を検出することができます。<br/>It uses a hashing algorithm to obtain a cryptographic checksum for each designated file.<br/>ハッシュアルゴリズムを使用して、指定された各ファイルの暗号チェックサムを取得します。<br/>If the file is altered and the checksum is recalculated, an extremely high probability exists that the new checksum will not match the old checksum.<br/>ファイルが変更され、チェックサムが再計算された場合、新しいチェックサムが古いチェックサムと一致しない可能性が非常に高くなります。<br/>By regularly recalculating checksums and comparing them with previous values, changes to files can be detected.<br/>定期的にチェックサムを再計算し、以前の値と比較することで、ファイルの変更を検出することができます。|
Third-party monitoring services<br/>サードパーティによるモニタリングサービス|Third parties offer a variety of subscription-based and free monitoring services.<br/>サードパーティは、サブスクリプションベースの様々な無料モニタリングサービスを提供しています。<br/>An example is fraud detection services that will notify an organization if its IP addresses, domain names, etc.are associated with current incident activity involving other organizations.<br/>例えば、IPアドレスやドメイン名などが他の組織が関与する現在のインシデント活動に関連している時に、組織に通知する不正検知サービスがあります。<br/>There are also free real-time blacklists with similar information.<br/>似たような情報を持つ無料のリアルタイムブラックリストもあります。<br/>Another example of a third-party monitoring service is a CSIRC notification list;<br/>サードパーティ監視サービスのもう一つの例として、CSIRCの通知リストがあります。<br/> these lists are often available only to other incident response teams.<br/>これらのリストは、他のインシデント対応チームのみが利用できることが多いです。|


Logs ログ
