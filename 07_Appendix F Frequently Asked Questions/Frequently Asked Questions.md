### Appnedix F Frequently Asked Questions
### 付録F　よくある質問

Users, system administrators, information security staff members, and others within organizations may have questions about incident response.  
組織内のユーザ、システム管理者、情報セキュリティ担当者などから、インシデント対応に関する質問を受けることがあります。 

The following are frequently asked questions (FAQ).  
以下は、よくある質問（FAQ）です。

Organizations are encouraged to customize this FAQ and make it available to their user community.  
組織は、この FAQ をカスタマイズしてユーザーコミュニティで利用できるようにすることをお勧めします。 

<br/>

**1. What is an incident? インシデントとは何ですか？** 

 In general, an incident is a violation of computer security policies, acceptable use policies, or standard computer security practices.  
 一般的に、インシデントとは、コンピュータセキュリティポリシー、許容される使用ポリシー、または標準的なコンピュータセキュリティ慣行の違反のことです。

 Examples of incidents are:  
 インシデントの例としては、以下のようなものがあります。  

 ■ An attacker commands a botnet to send high volumes of connection requests to one of an organization’s web servers, causing it to crash.  
 ■ 攻撃者がボットネットに命じて、組織の Web サーバーに大量の接続要求を送信し、クラッシュさせる。  

 ■ Users are tricked into opening a “quarterly report” sent via email that is actually malware;running the tool has infected their computers and established connections with an external host.  
 ■ ユーザが騙されて電子メールで送られてくる「四半期報告書」を開くと、実際にはマルウェアであり、ツールを実行することでコンピュータが感染し、外部ホストとの接続が確立されてしまう。 
 
 ■ A perpetrator obtains unauthorized access to sensitive data and threatens to release the details to the press if the organization does not pay a designated sum of money.  
 ■ 加害者が機密データへの不正アクセスを取得し、組織が指定された金額を支払わない場合は、詳細を報道機関に公開すると脅迫する。 
 
 ■ A user provides illegal copies of software to others through peer-to-peer file sharing services.  
 ■ ユーザーが、ピアツーピアのファイル共有サービスを通じて、ソフトウェアの違法コピーを他人に提供する。 
 
<br/>
 
**2. What is incident handling?  インシデントハンドリングとは？**  
 
 Incident handling is the process of detecting and analyzing incidents and limiting the incident’s effect.  
 インシデントハンドリングとは、インシデントを検知・分析し、インシデントの影響を限定するプロセスのことです。
 
 For example, if an attacker breaks into a system through the Internet, the incident handling process should detect the security breach.  
 例えば、攻撃者がインターネットを介してシステムに侵入した場合、インシデントハンドリングプロセスはセキュリティ侵害を検知する必要があります。 
 
 Incident handlers will then analyze the data and determine how serious the attack is.  
 その後、インシデントハンドラーはデータを分析し、攻撃がどの程度深刻なものかを判断します。
 
 The incident will be prioritized, and the incident handlers will take action to ensure that the progress of the incident is halted and that the affected systems return to normal operation as soon as possible.  
 インシデントハンドラーは、インシデントに優先順位をつけ、インシデントの進行を食い止め、影響を受けたシステムが一刻も早く通常の動作に戻るように行動します。 

<br/>

**3. What is incident response?  インシデント対応とは何ですか？**  

 The terms “incident handling” and “incident response” are synonymous in this document.※  
 「インシデントハンドリング」と「インシデントレスポンス」という用語は、本書では同義語です。  

 ※Definitions of “incident handling” and “incident response” vary widely. For example, CERT®/CC uses “incident handling” to refer to the overall process of incident detection, reporting, analysis, and response, whereas “incident response” refers specifically to incident containment, recovery, and notification of others. See http://www.cert.org/csirts/csirt_faq.html for more information. 
 「インシデントハンドリング」と「インシデントレスポンス」の定義は、大きく異なる。例えば、CERT®/CC は、「インシデントハンドリング」を、インシデントの検出、報告、分析、および対応の全体的なプロセスを指すために使用しているのに対し、「インシデントレスポンス」は、具体的にインシデントの封じ込め、回復、および他者への通知を指しています。詳細については、http://www.cert.org/csirts/csirt_faq.html を参照してください。  

<br/>

**4. What is an incident response team? インシデント対応チームとは何ですか？**  

 An incident response team (also known as a Computer Security Incident Response Team [CSIRT]) is responsible for providing incident response services to part or all of an organization.  
 インシデント対応チーム（Computer Security Incident Response Team [CSIRT]とも呼ばれる）は、組織の一部または全部にインシデント対応サービスを提供する役割を担っています。
 
 The team receives information on possible incidents, investigates them, and takes action to ensure that the damage caused by the incidents is minimized.  
 チームは、起こりうるインシデントに関する情報を受け取り、それを調査し、インシデントによる被害を最小限に抑えるための対策を講じます。

<br/>

**5. What services does the incident response team provide?  
 インシデント対応チームはどのようなサービスを提供しているのですか？**
 
 The particular services that incident response teams offer vary widely among organizations.  
 インシデント対応チームが提供する特定のサービスは、組織によって大きく異なります。
 
 Besides performing incident handling, most teams also assume responsibility for intrusion detection system monitoring and management.  
 ほとんどのチームは、インシデント対応を行うことに加えて、侵入検知システムの監視と管理の責任を負います。
 
 A team may also distribute advisories regarding new threats, and educate users and IT staff on their roles in incident prevention and handling.   
 また、チームは、新しい脅威に関するアドバイスを配布したり、インシデントの予防と処理における役割についてユーザーやITスタッフを教育したりすることもあります。

<br/>

**6. To whom should incidents be reported? インシデントは誰に報告すべきですか？**    
 
 Organizations should establish clear points of contact (POC) for reporting incidents internally.  
 組織は、内部的にインシデントを報告するための明確な接点（POC）を確立すべきです。
 
 Some organizations will structure their incident response capability so that all incidents are reported directly to the incident response team, whereas others will use existing support structures, such as the IT help desk, for an initial POC.  
 組織によっては、すべてのインシデントがインシデント対応チームに直接報告されるように、インシデント対応能力を構築する場合もあれば、IT ヘルプデスクなどの既存のサポート体制を初期のPOCに使用する場合もあります。 
 
 The organization should recognize that external parties, such as other incident response teams, would report some incidents.  
 組織は、他のインシデント対応チームなどの外部関係者が、一部のインシデントを報告することを認識すべきです。
 
 Federal agencies are required under the law to report all incidents to the United States Computer Emergency Readiness Team (US-CERT).  
 連邦政府機関は、法律に基づき、すべてのインシデントを米国コンピュータ緊急事態対応チーム（US-CERT）に報告することを義務付けられています。
 
 All organizations are encouraged to report incidents to their appropriate Computer Security Incident Response Teams (CSIRTs).  
 すべての組織は、適切なコンピュータ・セキュリティ・インシデント対応チーム（CSIRT）にインシデントを報告することが推奨されています。
 
 If an organization does not have its own CSIRT to contact, it can report incidents to other organizations, including Information Sharing and Analysis Centers (ISACs).  
 組織に連絡先となる CSIRT がない場合は、情報共有・分析センター（ISAC）などの他の組織にインシデントを報告することができます。

<br/>

**7. How are incidents reported? インシデントはどのように報告されますか？**  

 Most organizations have multiple methods for reporting an incident.  
 ほとんどの組織では、インシデントを報告するための複数の方法があります。
 
 Different reporting methods may be preferable as a result of variations in the skills of the person reporting the activity, the urgency of the incident, and the sensitivity of the incident.  
 活動を報告する人のスキル、インシデントの緊急性、およびインシデントの感度の違いにより、適切な報告方法が変わる場合があります。
 
 A phone number should be established to report emergencies.  
 緊急事態を報告するための電話番号を設けるべきです。
 
 An email address may be provided for informal incident reporting, whereas a web-based form may be useful in formal incident reporting.  
 電子メール・アドレスは、非公式のインシデント報告に使用される可能性ありますが、正式なインシデント報告にはウェブベースのフォームが適切な場合があります。 
 
 Sensitive information can be provided to the team by using a public key published by the team to encrypt the material.  
 機密情報は、チームが公開した公開鍵を使用して資料を暗号化することで、チームに提供することができます。

<br/>

**8. What information should be provided when reporting an incident?  
 インシデントを報告する際には、どのような情報を提供すべきでしょうか？** 

 The more precise the information is, the better.  
 情報は正確であればあるほど良いです。
 
 For example, if a workstation appears to have been infected by malware, the incident report should include as much of the following data as practical:  
 例えば、ワークステーションがマルウェアに感染しているように見える場合、インシデントレポートには、以下のデータをできるだけ多く含める必要があります。
 
 ■ The user’s name, user ID, and contact information (e.g., phone number, email address)  
 ■ ユーザーの名前、ユーザーID、および連絡先情報（電話番号、電子メール アドレスなど
 
 ■ The workstation’s location, model number, serial number, hostname, and IP address  
 ■ ワークステーションの場所、モデル番号、シリアル番号、ホスト名、および IP アドレス  
 
 ■ The date and time that the incident occurred  
 ■ インシデントが発生した日時
 
 ■ A step-by-step explanation of what happened, including what was done to the workstation after the infection was discovered.  
 ■ 感染が発見された後にワークステーションに何が行われたかなど、何が起こったのかを段階的に説明します。
 
 This explanation should be detailed, including the exact wording of messages, such as those displayed by the malware or by antivirus software alerts.  
 この説明は、マルウェアやウイルス対策ソフトの警告などのメッセージの正確な文言を含めて詳細に行う必要があります。

<br/>

**9. How quickly does the incident response team respond to an incident report?  
 インシデント対応チームは、インシデント報告にどのくらいの早さで対応しますか？**

 The response time depends on several factors, such as the type of incident, the criticality of the resources and data that are affected, the severity of the incident, existing Service Level Agreements (SLA) for affected resources, the time and day of the week, and other incidents that the team is handling.  
 応答時間は、インシデントの種類、影響を受けるリソースとデータの重要度、インシデントの深刻度、影響を受けるリソースに対する既存のサービスレベル契約（SLA）、時間と曜日、チームが処理している他のインシデントなど、いくつかの要因に依存します。

 Generally, the highest priority is handling incidents that are likely to cause the most damage to the organization or to other organizations.  
 一般的に、組織または他の組織に最も大きな被害をもたらす可能性の高いインシデントを処理することが最優先されます。

<br/>

**10. When should a person involved with an incident contact law enforcement?  
インシデントに関与している人は、いつ法執行機関に連絡すべきか？**

 Communications with law enforcement agencies should be initiated by the incident response team members, the chief information officer (CIO), or other designated official—users, system administrators, system owners, and other involved parties should not initiate contact.  
法執行機関との連絡は、インシデント対応チームのメンバー、最高情報責任者（CIO）、またはその他の指定された関係者によって開始されるべきであり、ユーザー、システム管理者、システム所有者、およびその他の関係者は、連絡を開始すべきではありません。

<br/>

**11. What should someone do who discovers that a system has been attacked?  
システムが攻撃されていることを知った人はどうすればいいですか？**

 The person should immediately stop using the system and contact the incident response team.  
 その人は、直ちにシステムの使用を停止し、インシデント対応チームに連絡しなければなりません。 

 The person may need to assist in the initial handling of the incident—for instance, physically monitoring the system until incident handlers arrive to protect evidence on the system.  
 その人は、インシデントの初期処理を支援する必要があるかもしれません。例えば、インシデント・ハンドラーが到着するまでの間、システム上の証拠を保護するためにシステムを物理的に監視するなどです。

<br/>

**12. What should someone do who is contacted by the media regarding an incident?  
インシデントに関してメディアから連絡を受けた人は、何をすべきですか？**

 A person may answer the media’s questions in accordance with the organization’s policy regarding incidents and outside parties.  
 ある人物は、インシデントと外部関係者に関する組織の方針に従って、メディアの質問に答えることができます。
 
 If the person is not qualified to represent the organization in terms of discussing the incident, the person should make no comment regarding the incident,other than to refer the caller to the organization’s public affairs office.  
 また、その人が組織を代表して事件を語る資格がない場合には、その人は事件に関するコメントをしてはならず、通報者を組織の広報室に紹介する以外は、事件に関するコメントをしてはなりません。
 
 This will allow the public affairs office to provide accurate and consistent information to the media and the public.  
 これにより、広報室はメディアや一般市民に正確で一貫性のある情報を提供することができます。