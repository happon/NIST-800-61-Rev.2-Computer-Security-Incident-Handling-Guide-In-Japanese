### 3.2.2 Signs of an Incident
### 3.2.2 インシデントの兆候

For many organizations, the most challenging part of the incident response process is accurately detecting and assessing possible incidents—determining whether an incident has occurred and, if so, the type, extent, and magnitude of the problem.  
多くの組織にとって、インシデント対応プロセスの中で最も困難な部分は、インシデントの可能性を正確に検出して評価することであり、インシデントが発生したかどうか、発生した場合には問題の種類、程度、および大きさを判断することです。 

What makes this so challenging is a combination of three factors:
これを困難にしているのは、3つの要因が重なっているからです。  

■ Incidents may be detected through many different means, with varying levels of detail and fidelity.  
■ インシデントは、詳細さと正確性が異なるさまざまな方法で検出される可能性があります。 

Automated detection capabilities include network-based and host-based IDPSs, antivirus software, and log analyzers.  
自動検出機能には、ネットワークベースおよびホストベースの IDPS、ウイルス対策ソフト、ログアナライザなどがあります。

Incidents may also be detected through manual means, such as problems reported by users.  
インシデントは、ユーザーから報告された問題などの手動の手段によっても検出されることがあります。 

Some incidents have overt signs that can be easily detected, whereas others are almost impossible to detect.  
インシデントの中には、簡単に検出できる明白な兆候があるものもあれば、ほとんど検出できないものもあります。 

■ The volume of potential signs of incidents is typically high—for example, it is not uncommon for an organization to receive thousands or even millions of intrusion detection sensor alerts per day. (See Section 3.2.4 for information on analyzing such alerts.)   

■ インシデントの潜在的な兆候の量は一般的に多く、例えば、組織が一日に何千、何百万もの侵入検知センサーのアラートを受信することも珍しくありません。（このようなアラートの分析に関する情報については、セクション 3.2.4 を参照）  

■ Deep, specialized technical knowledge and extensive experience are necessary for proper and efficient analysis of incident-related data.  
■ インシデント関連データを適切かつ効率的に分析するためには、深く専門的な技術知識と豊富な経験が必要です。

Signs of an incident fall into one of two categories: precursors and indicators.  
インシデントの兆候は、「前兆」と「兆候」という2つのカテゴリーのどちらかに分類されます。 

A precursor is a sign that an incident may occur in the future.  
前兆とは、インシデントが将来発生する可能性があることを示すサインです。

An indicator is a sign that an incident may have occurred or may be occurring now.  
兆候とは、インシデントが発生した可能性がある、または現在発生している可能性があることを示すサインです。 

Most attacks do not have any identifiable or detectable precursors from the target’s perspective.  
ほとんどの攻撃は、ターゲットから見れば、識別可能な前兆や検出可能な前兆を持っていません。 

If precursors are detected, the organization may have an opportunity to prevent the incident by altering its security posture to save a target from attack.  
前兆が検出された場合、組織は、攻撃からターゲットを救うためにセキュリティ姿勢を変更することで、インシデントを防止する機会があるかもしれません。 

At a minimum, the organization could monitor activity involving the target more closely.  
最低限、組織はターゲットが関与する活動をより綿密に監視することができます。 

Examples of precursors are:  
前兆の例としては、以下のようなものがあります。

■ Web server log entries that show the usage of a vulnerability scanner  
■ 脆弱性スキャナの使用状況を示すウェブサーバのログエントリ

■ An announcement of a new exploit that targets a vulnerability of the organization’s mail server  
■ 組織のメールサーバの脆弱性を標的とした新たなエクスプロイトの発表  

■ A threat from a group stating that the group will attack the organization.  
■ 組織を攻撃すると表明した集団からの脅迫

<br/>

While precursors are relatively rare, indicators are all too common.  
前兆は比較的まれですが、兆候はとてもありふれています。 

Too many types of indicators exist to exhaustively list them, but some examples are listed below:  
兆候の種類が多すぎてリストアップしきれませんが、以下にいくつかの例を挙げます。 

■ A network intrusion detection sensor alerts when a buffer overflow attempt occurs against a database server.  
■ ネットワーク侵入検知センサによるデータベースサーバに対してバッファオーバーフロー発生の警告 

■ Antivirus software alerts when it detects that a host is infected with malware.  
■ アンチウイルスソフトによるホストのマルウェア感染検出の警告

■ A system administrator sees a filename with unusual characters.  
■ システム管理者によるファイル名に異常な文字が含まれていることへの警告 

■ A host records an auditing configuration change in its log.  
■ ホストのログに、監査設定の変更が記録される。  
   

■ An application logs multiple failed login attempts from an unfamiliar remote system.  
■ アプリケーションによる見慣れないリモートシステムからの複数ログイン失敗をログに記録される。

■ An email administrator sees a large number of bounced emails with suspicious content.  
■ 電子メール管理者が、不審な内容の電子メールが大量の配信エラー（バウンスメール）を見つける。 

■ A network administrator notices an unusual deviation from typical network traffic flows.  
■ ネットワーク管理者が、典型的なネットワークトラフィックフローからの異常な逸脱に気づく。 