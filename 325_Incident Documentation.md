### 3.2.5 Incident Documentation
### 3.2.5 インシデントの文書  


An incident response team that suspects that an incident has occurred should immediately start recording all facts regarding the incident.※36  
インシデントが発生したと疑われるインシデント対応チームは、直ちにインシデントに関するすべての事実を記録しなければなりません。※36    

A logbook is an effective and simple medium for this,※37 but laptops,audio recorders, and digital cameras can also serve this purpose.※38  
ログブックはそのための効果的でシンプルな媒体※37ですが、ノートパソコン、オーディオレコーダー、デジタルカメラもこの目的を果たすことができます。※38  

Documenting system events, conversations, and observed changes in files can lead to a more efficient, more systematic, and less errorprone handling of the problem.  
システムイベント、会話、および観察されたファイルの変更を文書化することは、より効率的かつ体系的で、エラーの発生しにくい問題処理につながります。  

 
Every step taken from the time the incident was detected to its final resolution should be documented and timestamped.  
インシデントが検出されてから最終的な解決に至るまでのすべてのステップは、文書化され、タイムスタンプが付けられていなければなりません。

Every document regarding the incident should be dated and signed by the incident handler.  
またそれらの全ての文書には、日付が付けられ、インシデントハンドラによって署名されなければなりません。

Information of this nature can also be used as evidence in a court of law if legal prosecution is pursued.  
このような性質の情報は、法的起訴が追求された場合、法廷で証拠として使用することもできます。

Whenever possible, handlers should work in teams of at least two:  
可能な限り、ハンドラーは少なくとも2人のチームで作業すべきです。

one person can record and log events while the other person performs the technical tasks.  
一人がイベントを記録し、記録する一方で、もう一人が技術的な作業を行うことができます。

Section 3.3.2 presents more information about evidence.※39   
セクション 3.3.3.2 には、証拠についてのより詳しい情報が示されています。※39

The incident response team should maintain records about the status of incidents, along with other pertinent information.40  
インシデント対応チームは、その他の関連情報とともに、インシデントの状況に関する記録を保持すべきです。  
 
Using an application or a database, such as an issue tracking system, helps ensure that incidents are handled and resolved in a timely manner.  
問題追跡システムなどのアプリケーションやデータベースを使用することは、インシデントが適時に処理され、解決するのに役立ちます。
 
The issue tracking system should contain information on the following:
問題追跡システムには、以下の情報が含まれているべきです。

■ The current status of the incident (new, in progress, forwarded for investigation, resolved, etc.)  
■ インシデントの現在の状態（新規、進行中、調査のために転送された、解決されたなど）。

■ A summary of the incident  
■ インシデントの概要 

■ Indicators related to the incident  
■ インシデントに関連する兆候

■ Other incidents related to this incident  
■ このインシデントに関連するその他のインシデント  

■ Actions taken by all incident handlers on this incident  
■ このインシデントに関して、すべてのインシデント・ハンドラがとった行動  

■ Chain of custody, if applicable  
■ 書類受け渡し記録の管理（該当する場合

■ Impact assessments related to the incident  
■ インシデントに関連した影響評価

■ Contact information for other involved parties (e.g., system owners, system administrators)  
■ 他の関係者の連絡先情報（システム所有者、システム管理者など  

■ A list of evidence gathered during the incident investigation  
■ インシデント調査で集めた証拠の一覧表

■ Comments from incident handlers  
■ インシデントハンドラからのコメント 

■ Next steps to be taken (e.g., rebuild the host, upgrade an application).41  
■ 次の措置（例：ホストの再構築、アプリケーションのアップグレード）

The incident response team should safeguard incident data and restrict access to it because it often contains sensitive information  
インシデント対応チームは、インシデントデータを保護し、インシデントデータへのアクセスを制限する必要があります。 


—for example, data on exploited vulnerabilities, recent security breaches, and users that may have performed inappropriate actions.  
例えば、悪用された脆弱性に関するデータ、最近のセキュリティ侵害、不適切な行為を行った可能性のあるユーザーなどです。

For example, only authorized personnel should have access to the incident database.  
例えば、インシデントデータベースへのアクセスは、権限のある担当者のみが行うべきです。 

Incident communications (e.g., emails) and documents should be encrypted or otherwise protected so that only authorized personnel can read them.  
インシデント通信（電子メールなど）や文書は、権限を与えられた人員のみが読めるように、暗号化するか、その他の方法で保護されるべきです。

※36
Incident handlers should log only the facts regarding the incident, not personal opinions or conclusions. Subjective material should be presented in incident reports, not recorded as evidence.  
インシデントハンドラーは、個人的な意見や結論ではなく、インシデントに関する事実のみを記録すべきです。主観的な材料は、証拠として記録されないように、インシデント報告書で提示されるべきです。

※37
If a logbook is used, it is preferable that the logbook is bound and that the incident handlers number the pages, write in ink, and leave the logbook intact (i.e., do not rip out any pages).  
ログブックを使用する場合は、製本し、インシデント担当者がページ番号を付け、ペン書きし、そのままにしておくことが望ましい（ページを切り取らないこと）。 

※38
Consider the admissibility of evidence collected with a device before using it. For example, any devices that are potential sources of evidence should not themselves be used to record other evidence.    
装置を使用する前に、装置で収集した証拠の許容性を検討してください。例えば、証拠となる可能性のある機器は、それ自体が他の証拠を記録するために使用すべきではありません。 

※39
NIST SP 800-86, Guide to Integrating Forensic Techniques Into Incident Response, provides detailed information on establishing a forensic capability, including the development of policies and procedures.  
NIST SP 800-86「インシデント対応にフォレンジック技術を統合するためのガイド」では、ポリシーと手順の策定を含むフォレンジック能力の確立に関する詳細な情報を提供しています。

