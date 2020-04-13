### 2.1 Events and Incidents 「イベントとインシデント」  

An event is any observable occurrence in a system or network.  
イベントとは、システムやネットワークで発生する観察可能な事象のことです。  

Events include a user connecting to a file share, a server receiving a request for a web page, a user sending email, and a firewall blocking a connection attempt.  
イベントには、ユーザーがファイル共有に接続した場合、サーバーがウェブページの要求を受信した場合、ユーザーが電子メールを送信した場合、ファイアウォールが接続の試みをブロックした場合などがあります。  

Adverse events are events with a negative consequence, such as system crashes, packet floods, unauthorized use of system privileges, unauthorized access to sensitive data, and execution of malware that destroys data.  
有害事象とは、システムのクラッシュ、パケットの洪水、システム特権の不正使用、機密データへの不正アクセス、データを破壊するマルウェアの実行など、負の結果をもたらす事象のことです。  

This guide addresses only adverse events that are computer securityrelated, not those caused by natural disasters, power failures, etc.  
このガイドでは、自然災害や停電などによって引き起こされた事象ではなく、コンピュータセキュリティに関連した有害事象のみを扱います。  

A computer security incident is a violation or imminent threat of violation※1 of computer security policies, acceptable use policies, or standard security practices.  
コンピュータセキュリティインシデントとは、コンピュータセキュリティポリシー、許容される使用ポリシー、または標準的なセキュリティプラクティスに対する違反または違反の差し迫った脅威のことです。  

Examples of incidents※2 are:  
インシデントの例  

■ An attacker commands a botnet to send high volumes of connection requests to a web server, causing it to crash.  
攻撃者がボットネットに命令して、大量の接続要求をウェブサーバに送信し、クラッシュさせる。  

■ Users are tricked into opening a “quarterly report” sent via email that is actually malware; running the tool has infected their computers and established connections with an external host.  
ユーザが騙されて電子メールで送られてくる「四半期報告書」を開くと、実際にはマルウェアであり、ツールを実行することでコンピュータが感染し、外部ホストとの接続が確立されてしまう。  

■ An attacker obtains sensitive data and threatens that the details will be released publicly if the organization does not pay a designated sum of money.  
攻撃者が機密データを入手し、組織が指定された金額を支払わなければ詳細が公開されると脅す。  

■ A user provides or exposes sensitive information to others through peer-to-peer file sharing services.  
ユーザーが、ピアツーピアのファイル共有サービスを通じて、機密情報を提供したり、他人に公開したりする。 

<br/>

※1 An “imminent threat of violation” refers to a situation in which the organization has a factual basis for believing that a specific incident is about to occur.  
「違反の差し迫った脅威」とは、組織が特定のインシデントが発生しようとしていると信じる事実上の根拠を持っている状況を指す。  

For example, the antivirus software maintainers may receive a bulletin from the software vendor, warning them of new malware that is rapidly spreading across the Internet.  
例えば、ウイルス対策ソフトウェアのメンテナが、インターネット上で急速に広がっている新しいマルウェアの警告をソフトウェアベンダから通知を受け取ることがあります。  

<br/>

※2 For the remainder of this document, the terms “incident” and “computer security incident” are interchangeable.  
本書の残りの部分では、「インシデント」と「コンピュータセキュリティインシデント」という用語は互換性があります。  
