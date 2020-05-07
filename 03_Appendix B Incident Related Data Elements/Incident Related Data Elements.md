# Appendex B Incident-Related Data Element
# 付録B　インシデント関連データ要素

Organizations should identify a standard set of incident-related data elements to be collected for each incident.  
組織は、各インシデントについて収集すべきインシデント関連のデータ要素の標準的なセットを特定すべきです。

This effort will not only facilitate more effective and consistent incident handling, but also assist the organization in meeting applicable incident reporting requirements.  
この取り組みは、より効果的で一貫性のあるインシデント処理を促進するだけでなく、適用されるインシデント報告の要件を満たすために組織を支援することにもなります。 

The organization should designate a set of basic elements (e.g., incident reporter’s name, phone number, and location) to be collected when the incident is reported and an additional set of elements to be collected by the incident handlers during their response.  
組織は、インシデントが報告されたときに収集される基本的な要素（例えば、インシデント報告者の名前、 電話番号、および場所）のセットと、インシデント対応者が対応中に収集する追加の要素のセットを指定すべきです。

The two sets of elements would be the basis for the incident reporting database, previously discussed in Section 3.2.5.  
2つの要素のセットは、前にセクション3.2.5で議論したインシデント報告データベースの基礎となります。

The lists below provide suggestions of what information to collect for incidents and are not intended to be comprehensive.  
以下のリストは、インシデントに対して収集すべき情報の提案であり、包括的なものではありません。

Each organization should create its own list of elements based on several factors, including its incident response team model and structure and its definition of the term “incident.”  
各組織は、そのインシデント対応チームのモデルと構造、および "インシデント "という用語の定義を含むいくつかの要因に基づいて、独自のデータ要素リストを作成するべきです。 

<br/>

### B.1 Basic Data Elements  
### B.1 基本データ要素

 Contact Information for the Incident Reporter and Handler  
■ インシデントレポーター・ハンドラーの連絡先  
 – Name  名前  
 – Role  役割  
 – Organizational unit (e.g., agency, department, division, team) and affiliation   
 － 組織単位（例：代理店、部署、部署、チーム）と所属  
 – Email address  メールアドレス  
 – Phone number  電話番号  
 – Location (e.g., mailing address, office room number)  所在地（住所、事務所の部屋番号など  

<br/>

 Incident Details  
■ インシデントの詳細  
 – Status change date/timestamps (including time zone): when the incident started, when the incident was discovered/detected, when the incident was reported, when the incident was resolved/ended, etc.  
 － 状態変化の日付/タイムスタンプ（タイムゾーンを含む）：インシデントが開始されたとき、インシデントが発見/検出されたとき、インシデントが報告されたとき、インシデントが解決/終了したとき、など  
 – Physical location of the incident (e.g., city, state)  
 － インシデントの物理的な場所（例：市、州  
 – Current status of the incident (e.g., ongoing attack)  
 － 事件の現在の状況（進行中の攻撃など  
 – Source/cause of the incident (if known), including hostnames and IP addresses  
 - ホスト名とIPアドレスを含む、インシデントの発生源/原因(既知の場合)  
 – Description of the incident (e.g., how it was detected, what occurred)  
  - インシデントの説明（例：どのようにして検出されたか、何が起こったか  
 – Description of affected resources (e.g., networks, hosts, applications, data), including systems’ hostnames, IP addresses, and function  
  - システムのホスト名、IP アドレス、機能を含む、影響を受けるリソース（ネットワーク、ホスト、アプリケーション、データなど）の説明   
 – If known, incident category, vectors of attack associated with the incident, and indicators related to the incident (traffic patterns, registry keys, etc.)   
  - 既知の場合は、インシデントのカテゴリー、インシデントに関連する攻撃のベクトル、およびインシデントに関連する指標（トラフィックパターン、レジストリキーなど  
 – Prioritization factors (functional impact, information impact, recoverability, etc.)  
  - 優先順位付けの要因（機能的な影響、情報への影響、復旧可能性など  
 – Mitigating factors (e.g., stolen laptop containing sensitive data was using full disk encryption)  
  - 緩和要因（例：機密データを含む盗まれたノートパソコンが完全なディスク暗号化を使用していたなど  
 – Response actions performed (e.g., shut off host, disconnected host from network)  
  - 実行されたレスポンスアクション（例：ホストのシャットオフ、ネットワークからのホストの切断 
 – Other organizations contacted (e.g., software vendor)  
  - 連絡を取った他の組織（例：ソフトウェアベンダー  
 
 General Comments  総評  


### B.2 Incident Handler Data Elements  
### B.2 インシデントハンドラのデータ要素 

 Current Status of the Incident Response  
■ インシデント対応の現状  

 Summary of the Incident  
■ 事件の概要  

 Incident Handling Actions  
■ インシデント対応アクション
 – Log of actions taken by all handlers  
 - すべてのハンドラーが実行したアクションのログ 
 – Contact information for all involved parties  
 - 関係者の連絡先
 – List of evidence gathered  
 - 集められた証拠の一覧 

 Incident Handler Comments  
■ インシデントハンドラのコメント  

 Cause of the Incident (e.g., misconfigured application, unpatched host)  
■ インシデントの原因（アプリケーションの設定ミス、パッチが適用されていないホストなど  

 Cost of the Incident  
■ インシデントの費用  

 Business Impact of the Incident※  
■ インシデントのビジネスへの影響※

※The business impact of the incident could either be a description of the incident’s effect (e.g., accounting department unable to perform tasks for two days) or an impact category based on the cost (e.g., a “major” incident has a cost of over $100,000).  
インシデントのビジネスへの影響は、インシデントの影響の説明（例えば、会計部門が2日間タスクを実行できないなど）か、コストに基づく影響のカテゴリー（例えば、「重大な」インシデントは10万ドル以上のコストがかかるなど）のいずれかである可能性があります。