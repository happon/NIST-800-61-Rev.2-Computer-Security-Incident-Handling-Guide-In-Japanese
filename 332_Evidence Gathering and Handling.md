### 3.3.2 Evidence Gathering and Handling
### 3.3.2 証拠の収集と処理

Although the primary reason for gathering evidence during an incident is to resolve the incident, it may also be needed for legal proceedings.42  
インシデント中に証拠を収集する主な理由は、インシデントを解決することですが、法的手続きのために必要な場合もあります。42  

In such cases, it is important to clearly document how all evidence, including compromised systems, has been preserved.43  
そのような場合には、漏洩したシステムを含むすべての証拠がどのように保存されたかを明確に文書化することが重要です。43

Evidence should be collected according to procedures that meet all applicable laws and regulations that have been developed from previous discussions with legal staff and appropriate law enforcement agencies so that any evidence can be admissible in court.44  

証拠は、あらゆる証拠が法廷で認められるように、法務担当者や適切な法執行機関との以前の話し合いで策定された、 適用されるすべての法規制を満たす手順にしたがって収集されるべきです。

In addition, evidence should be accounted for at all times; whenever evidence is transferred from person to person, chain of custody forms should detail the transfer and include each party’s signature.  
さらに、証拠は常に説明されるべきである。証拠が人から人へ移されるときはいつでも、書類・証拠受け渡し記録は移された内容を詳述し、 各当事者の署名を含めるべきです。  

A detailed log should be kept for all evidence, including the following:  
以下を含むすべての証拠について、詳細な記録を残すべきです。 

 Identifying information (e.g., the location, serial number, model number, hostname, media access control (MAC) addresses, and IP addresses of a computer)   
■ 識別情報（例：場所、シリアル番号、モデル番号、ホスト名、メディアアクセス制御（MAC）アドレス、コン ピュータのIPアドレスなど 

 Name, title, and phone number of each individual who collected or handled the evidence during the investigation  
■ 調査中に証拠を収集した、または取り扱った各個人の氏名、肩書き、電話番号

 Time and date (including time zone) of each occurrence of evidence handling  
■ 証拠処理の各発生日時（時間帯を含む  

 Locations where the evidence was stored.  
■ 証拠が保管されていた場所

Collecting evidence from computing resources presents some challenges.  
コンピューティングリソースから証拠を収集することには、いくつかの課題があります。

It is generally desirable to acquire evidence from a system of interest as soon as one suspects that an incident may have occurred.  
一般的には、インシデントが発生した可能性があると疑われたらすぐに、対象となるシステムから証拠を取得することが望ましいです。 

Many incidents cause a dynamic chain of events to occur;  
多くのインシデントは、動的なイベントの連鎖を引き起こします。  

an initial system snapshot may do more good in identifying the problem and its source than most other actions that can be taken at this stage.  
初期のシステムスナップショットは、問題とその原因を特定する上で、この段階で実行できる他のほとんどのアクションよりも効果があるかもしれません。 

From an evidentiary standpoint, it is much better to get a snapshot of the system as-is rather than doing so after incident handlers, system administrators, and others have inadvertently altered the state of the machine during the investigation.  
証拠の観点からは、インシデントハンドラーやシステム管理者などが調査中に不注意でマシンの状態を変更してしまった後に行うよりも、そのままの状態でシステムのスナップショットを取得する方がはるかに良いでしょう。

Users and system administrators should be made aware of the steps that they should take to preserve evidence.  
ユーザーとシステム管理者は、証拠を保存するために取るべき手順を認識しておく必要があります。 

See NIST SP 800-86, Guide to Integrating Forensic Techniques into Incident Response, for additional information on preserving evidence.  
証拠保全に関する追加情報については、NIST SP 800-86『Guide to Integrating Forensic Techniques into Incident Response』を参照してください。  