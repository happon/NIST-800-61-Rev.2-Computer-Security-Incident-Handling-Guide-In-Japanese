### 4.3.2 Technical Information
### 4.3.2 技術情報

There are many different types of technical indicators signifying the occurrence of an incident within an organization.  
組織内でのインシデントの発生を示す技術的な兆候には、さまざまな種類があります。 

These indicators originate from the variety of technical information associated with incidents, such as the hostnames and IP addresses of attacking hosts, samples of malware, precursors and indicators of similar incidents, and types of vulnerabilities exploited in an incident.  
これらの兆候は、攻撃するホストのホスト名や IP アドレス、マルウェアのサンプル、類似のインシデントの前兆や兆候、インシデントで悪用された脆弱性の種類など、インシデントに関連するさまざまな技術情報に由来しています。 

Section 3.2.2 provides an overview of how organizations should collect and utilize these indicators to help identify an incident that is in progress.  
セクション 3.2.2 では、進行中のインシデントを特定するために、組織がこれらの兆候をどのように収集し、活用すべきかの概要を説明しています。

In addition, Section 3.2.3 provides a listing of common sources of incident indicator data.  
さらに、セクション 3.2.3 では、インシデント兆候データの一般的な情報源のリストを提供します。 

<br/>

While organizations gain value from collecting their own internal indicators, they may gain additional value from analyzing indicators received from partner organizations and sharing internal indicators for external analysis and use.  
組織は、独自の内部兆候を収集することで価値を得ますが、パートナー組織から受け取った兆候を分析したり、外部の分析・利用のために内部兆候を共有したりすることで、さらなる価値を得ることができます。

If the organization receives external indicator data pertaining to an incident they have not seen, they can use that indicator data to identify the incident as it begins to occur.  
組織が見ていないインシデントに関連する外部兆候データを受け取った場合、その兆候データを使用して、インシデントが発生し始めた時点でそのインシデントを特定することができます。 

Similarly, an organization may use external indicator data to detect an ongoing incident that it was not aware of due to the lack of internal resources to capture the specific indicator data.  
同様に、組織は、特定の兆候データを取得するための内部リソースが不足しているために気づかなかった進行中のインシデントを検出するために、外部兆候データを使用することができます。 

Organizations may also benefit from sharing their internal indicator data with external organizations.  
組織は、内部兆候データを外部組織と共有することでも利益を得られます。 

For example, if they share technical information pertaining to an incident they are experiencing, a partner organization may respond with a suggested remediation strategy for handling that incident.  
例えば、組織が経験しているインシデントに関連する技術情報を共有した場合、パートナー組織は、そのインシデントに対処するための改善策を提案して対応することができます。 

<br/>
 
Organizations should share as much of this information as possible;  
組織は、このような情報を可能な限り共有すべきです。

however, there may be both security and liability reasons why an organization would not want to reveal the details of an exploited vulnerability.  
しかし、組織が悪用された脆弱性の詳細を明らかにしたくない理由には、セキュリティ上の理由と 責任上の理由があるかもしれません。

External indicators, such as the general characteristics of attacks and the identity of attacking hosts, are usually safe to share with others.  
攻撃の一般的な特徴や攻撃するホストの身元などの外部指標は、通常、他の人と共有しても安全です。

Organizations should consider which types of technical information should or should not be shared with various parties, and then endeavor to share as much of the appropriate information as possible with other organizations. 
組織は、どのような種類の技術情報を様々な関係者と共有すべきか、あるいは共有すべきでないかを検討し、適切な情報を可能な限り他の組織と共有するように努めなければならりません。

<br/>

Technical indicator data is useful when it allows an organization to identify an actual incident.  
技術的兆候データは、組織が実際のインシデントを特定できる場合に役立ちます。 

However, not all indicator data received from external sources will pertain to the organization receiving it.  
しかし、外部ソースから受け取ったすべての兆候データが、それを受け取った組織に関係するわけではありません。

In some cases, this external data will generate false positives within the receiving organization's network and may cause resources to be spent on nonexistent problems.  
場合によっては、この外部データは、受信した組織のネットワーク内で誤検知を発生させ、存在しない問題にリソースが費やされる可能性があります。 

<br/>

Organizations participating in incident information sharing should have staff skilled in taking technical indicator information from sharing communities and disseminating that information throughout the enterprise, preferably in an automated way.  
インシデント情報の共有に参加している組織は、共有コミュニティから技術的兆候情報を取得し、その情報を企業全体に、できれば自動化された方法で発信することに長けたスタッフを持つべきです。 

Organizations should also attempt to ensure that they only share an indicator for which they have a relatively high level of confidence that it signifies an actual incident. 
また、組織は、実際のインシデントを意味すると比較的高いレベルで確信できる兆候のみを共有するように努めるべきです。