### 3.3.3 Identifying the Attacking Hosts
### 3.3.3 攻撃ホストの特定

During incident handling, system owners and others sometimes want to or need to identify the attacking host or hosts.  
インシデント処理の間、システム所有者やその他の人は、攻撃している（単数あるいは複数の）ホストを特定したい、または特定する必要があることがあります。 

Although this information can be important, incident handlers should generally stay focused on containment, eradication, and recovery.  
この情報は重要な場合もありますが、インシデント処理担当者は一般的に、封じ込め、根絶、回復に集中すべきです。 

Identifying an attacking host can be a time-consuming and futile process that can prevent a team from achieving its primary goal—minimizing the business impact.  
攻撃してくるホストを特定することは、時間のかかる無駄なプロセスであり、チームの主要な目標であるビジネスへの影響を最小化することを妨げる可能性があります。 

The following items describe the most commonly performed activities for attacking host identification:  
以下の項目では、攻撃ホストの特定のために最も一般的に行われる活動について説明します。 

■ **Validating the Attacking Host’s IP Address.**
■ **攻撃ホストのIPアドレスを検証する**  

 New incident handlers often focus on the attacking host’s IP address.  
 新しいインシデントハンドラーは、攻撃ホストのIPアドレスに焦点を当てることが多いです。 

 The handler may attempt to validate that the address was not spoofed by verifying connectivity to it;  
 ハンドラーは、そのアドレスへの接続性を検証することで、そのアドレスが偽装されていないことを検証しようとするかもしれません。  
 
 however, this simply indicates that a host at that address does or does not respond to the requests.  
 しかし、これは単にそのアドレスのホストがリクエストに応答するかしないかを示しているだけです。  
 
 A failure to respond does not mean the address is not real—for example, a host may be configured to ignore pings and traceroutes.  
 応答しないということは、そのアドレスが実在しないということを意味するわけではありません。  
 
 Also, the attacker may have received a dynamic address that has already been reassigned to someone else.  
 また、攻撃者が既に他の誰かに再割り当てされたダイナミックアドレスを受信している可能性もあります。 


■ **Researching the Attacking Host through Search Engines.**  
■ **検索エンジンを使って攻撃するホストを調査する**  

 Performing an Internet search using the apparent source IP address of an attack may lead to more information on the attack—for example, a mailing list message regarding a similar attack.  
 検索エンジンを利用した攻撃ホストの調査攻撃の発信元と思われる IP アドレスを使ってインターネット検索を行うと、攻撃に関するより多くの情報（例えば、類似の攻撃に関するメーリングリストのメッセージなど）が得られる可能性があります。


■ **Using Incident Databases.**  
■ **インシデントデータベースの利用**  

 Several groups collect and consolidate incident data from various organizations into incident databases.  
 インシデントデータベースの利用。複数のグループが、さまざまな組織からインシデントデータを収集し、整備しています。

 This information sharing may take place in many forms, such as trackers and real-time blacklists.  
 この情報共有は、トラッカーやリアルタイムのブラックリストなど、さまざまな形で行われます。  
 
 The organization can also check its own knowledge base or issue tracking system for related activity.  
 また、組織は、独自のナレッジベースや問題追跡システムをチェックして、関連する活動を確認することもできます。 


■ **Monitoring Possible Attacker Communication Channels.**  
■ **攻撃者の可能性のある通信チャネルの監視  
 
 Incident handlers can monitor communication channels that may be used by an attacking host.  
 インシデントハンドラーは、攻撃するホストが使用する可能性のある通信チャネルを監視することができます。

 For example, many bots use IRC as their primary means of communication.  
 例えば、多くのボットはIRCを主な通信手段として使用しています。

 Also, attackers may congregate on certain IRC channels to brag about their compromises and share information.  
 また、攻撃者は特定の IRC チャンネルに集まって、自分たちの危殆化した状況を自慢したり、情報を共有したりすることもあります。

 However, incident handlers should treat any such information that they acquire only as a potential lead, not as fact.  
 しかし、インシデントハンドラーは、そのような情報を入手しても、事実としてではなく、潜在的な手がかりとしてのみ扱うべきです。 