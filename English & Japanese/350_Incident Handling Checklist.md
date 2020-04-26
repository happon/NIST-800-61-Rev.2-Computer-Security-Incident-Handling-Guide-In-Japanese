### 3.5 Incident Handling Checklist 
### 3.5 インシデントハンドリングチェックリスト

The checklist in Table 3-5 provides the major steps to be performed in the handling of an incident.  
表 3-5 のチェックリストには、インシデントの処理において実行すべき主なステップが記載されています。

Note that the actual steps performed may vary based on the type of incident and the nature of individual incidents.  
実際に実行されるステップは、インシデントの種類や個々のインシデントの性質に基づいて異なる場合があることに注意してください。  

For example, if the handler knows exactly what has happened based on analysis of indicators (Step 1.1), there may be no need to perform Steps 1.2 or 1.3 to further research the activity.  
例えば、ハンドラが兆候の分析に基づいて何が起こったかを正確に知っている場合（ステップ 1.1）、活動をさらに調査するためにステップ 1.2 または 1.3 を実行する必要はないかもしれません。

The checklist provides guidelines to handlers on the major steps that should be performed; it does not dictate the exact sequence of steps that should always be followed.  
このチェックリストは、ハンドラーが実行すべき主なステップについてのガイドラインを提供するものであり、常に従わなければならないステップの正確な順序を指示するものではありません。

Table 3-5. Incident Handling Checklist 
図3-5 インシデントハンドリングチェックリスト  

| |Action 行動|check|
|-|-|-|
| |Detection and Analysis<br/>検知と解析|
|1.&emsp;&nbsp;|Determine whether an incident has occurred<br/>インシデントが発生したかどうかを判断する|
|&emsp;1.1|&emsp;&emsp;Analyze the precursors and indicators<br/>&emsp;&emsp;前兆と兆候を分析する|
|&emsp;1.2|&emsp;&emsp; Look for correlating information<br/>&emsp;&emsp;関連する情報を探す|
|&emsp;1.3|&emsp;&emsp;Perform research (e.g., search engines, knowledge base) <br/>&emsp;&emsp;調査の実施（検索エンジン、ナレッジデータベースなど）|
|&emsp;1.4|&emsp;&emsp;As soon as the handler believes an incident has occurred, begin documenting  the investigation and gathering evidence<br/>&emsp;&emsp;ハンドラーは、事件が発生したと確信したらすぐに調査の文書化と証拠の収集を開始|
|2.&emsp;&emsp;|Prioritize handling the incident based on the relevant factors (functional impact, information impact, recoverability effort, etc.) <br/>関連する要因（機能的影響、情報的影響、復旧努力など）に基づいて、インシデントへの対応に優先順位をつける。|
|3.&emsp;&emsp;|Report the incident to the appropriate internal personnel and external organizations<br/>社内の適切な担当者および外部組織に報告する。|
|| Containment, Eradication, and Recovery<br/>封じ込め、根絶、復旧|
|4.&emsp;&emsp;|Acquire, preserve, secure, and document evidence<br/>証拠の取得、保存、確保、文書化|
|5.&emsp;&emsp;|Contain the incident <br/>事件の封じ込め|
|6.&emsp;&emsp;|Eradicate the incident <br/>事件の根絶|
|&emsp;6.1|&emsp;&emsp; Identify and mitigate all vulnerabilities that were exploited <br/> &emsp;&emsp;悪用されたすべての脆弱性を特定し、軽減する|
|&emsp;6.2|&emsp;&emsp; Remove malware, inappropriate materials, and other components<br/>&emsp;&emsp;マルウェアや不適切な素材などを除去する|
|&emsp;6.3|&emsp;&emsp; If more affected hosts are discovered (e.g., new malware infections), repeat  the Detection and Analysis steps (1.1, 1.2) to identify all other affected hosts, then  contain (5) and eradicate (6) the incident for them<br/> &emsp;&emsp;より多くの影響を受けるホストが発見された場合(新しいマルウェア感染など)、検出と解析のステップ(1.1, 1.2)を繰り返して、他の影響を受けるすべてのホストを特定し、(5)のインシデントを封じ込め、(6)のインシデントを根絶してください。|
|7.&emsp;&emsp;|Recover from the incident<br/>インシデントからの復旧|
|&emsp;7.1|&emsp;&emsp;Return affected systems to an operationally ready state<br/>&emsp;&emsp;影響を受けたシステムを動作可能な状態に戻す |
|&emsp;7.2|&emsp;&emsp;Confirm that the affected systems are functioning normally <br/>&emsp;&emsp;影響を受けたシステムが正常に機能していることを確認する|
|&emsp;7.3|&emsp;&emsp;If necessary, implement additional monitoring to look for future related activity<br/> &emsp;&emsp;必要に応じて、将来の関連活動を探すために追加のモニタリングを実施する。|
||Post-Incident Activity<br/>インシデント後の活動 |
|8.|Create a follow-up report <br/>フォローアップレポートの作成|
|9.|Hold a lessons learned meeting (mandatory for major incidents, optional otherwise) <br/>教訓会議の開催（重大インシデントの場合は必須、それ以外の場合は任意 |  

