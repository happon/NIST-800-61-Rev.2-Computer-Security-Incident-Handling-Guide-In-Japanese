### Choosing a Containment Strategy 
### 封じ込め戦略の選択

Containment is important before an incident overwhelms resources or increases damage.  
インシデントがリソースを圧倒したり、被害が拡大したりする前に、封じ込めが重要です。  

Most incidents require containment, so that is an important consideration early in the course of handling each incident.  
ほとんどのインシデントでは封じ込めが必要であるため、各インシデントへの対応の初期段階では、封じ込めは重要な検討事項です。  

<br/>

Containment provides time for developing a tailored remediation strategy.  
封じ込めを行うことで、個別に対応した修復戦略を策定する時間を確保することができます。

An essential part of containment is decision-making (e.g., shut down a system, disconnect it from a network, disable certain functions).  
封じ込めの本質的な部分は、意思決定(システムをシャットダウンする、ネットワークから切断する、特定の機能を無効にするなど)です。 

Such decisions are much easier to make if there are predetermined strategies and procedures for containing the incident.  
インシデントを封じ込めるための事前の戦略と手順があれば、そのような決定ははるかに容易になります。 

Organizations should define acceptable risks in dealing with incidents and develop strategies accordingly.  
組織は、インシデントに対処する際の許容可能なリスクを定義し、それに応じて戦略を策定すべきです。 

Containment strategies vary based on the type of incident.  
封じ込め戦略は、インシデントの種類によって異なります。

For example, the strategy for containing an email-borne malware infection is quite different from that of a network-based DDoS attack.  
例えば、電子メールを媒介とするマルウェア感染を封じ込める戦略は、ネットワークベースの DDoS 攻撃とは大きく異なります。 

Organizations should create separate containment strategies for each major incident type, with criteria documented clearly to facilitate decision-making.  
組織は、主要なインシデントの種類ごとに個別の封じ込め戦略を作成し、意思決定を容易にするために基準を明確に文書化する必要があります。 

Criteria for determining the appropriate strategy include:  
適切な戦略を決定するための基準には、以下のようなものがあります。  

■ Potential damage to and theft of resources  
■ 資源への被害・盗難の可能性 

■ Need for evidence preservation  
■ 証拠保全の必要性

■ Service availability (e.g., network connectivity, services provided to external parties)  
■ サービスの可用性（ネットワーク接続性、外部に提供されるサービスなど 

■ Time and resources needed to implement the strategy 
■ 戦略を実行するために必要な時間とリソース 

■ Effectiveness of the strategy (e.g., partial containment, full containment)  
■ 戦略の有効性（例：部分的封じ込め、完全封じ込め

■ Duration of the solution (e.g., emergency workaround to be removed in four hours, temporary workaround to be removed in two weeks, permanent solution).  
■ 解決策の期間（例：緊急回避策は 4 時間以内に削除する、一時的な回避策は 2 週間以内に削除する、恒久的な解決策）。 

In certain cases, some organizations redirect the attacker to a sandbox (a form of containment) so that they can monitor the attacker’s activity, usually to gather additional evidence.  
場合によっては、攻撃者の活動を監視できるように、攻撃者をサンドボックス（封じ込めの一形態）にリダイレクトして、通常は追加の証拠を収集する組織もあります。 

The incident response team should discuss this strategy with its legal department to determine if it is feasible.  
インシデント対応チームは、この戦略が実行可能かどうかを判断するために、法務部門と話し合うべきです。

Ways of monitoring an attacker’s activity other than sandboxing should not be used;  
サンドボックス以外の攻撃者の活動を監視する方法は、使用すべきではありません。

if an organization knows that a system has been compromised and allows the compromise to continue, it may be liable if the attacker uses the compromised system to attack other systems.  
システムが侵害されたことを知っている組織が、侵害の継続を許した場合、攻撃者が侵害されたシステ ムを使って他のシステムを攻撃した場合、組織は責任を負うことになるかもしれません。 

The delayed containment strategy is dangerous because an attacker could escalate unauthorized access or compromise other systems.  
攻撃者が不正アクセスをエスカレートさせたり、他のシステムを侵害したりする可能性があるため、封じ込め戦略の遅延は危険です。 

<br/>

Another potential issue regarding containment is that some attacks may cause additional damage when they are contained.  
封じ込めに関するもう一つの潜在的な問題は、一部の攻撃が封じ込められた場合に追加の損害を引き起こす可能性があることです。 

For example, a compromised host may run a malicious process that pings another host periodically.  
例えば、侵害されたホストが悪意のあるプロセスを実行して、他のホストに定期的にpingを打つことがあります。 

When the incident handler attempts to contain the incident by disconnecting the compromised host from the network, the subsequent pings will fail.  
インシデントハンドラが侵害されたホストをネットワークから切断することでインシデントを封じ込めようとすると、その後のpingは失敗します。 

As a result of the failure, the malicious process may overwrite or encrypt all the data on the host’s hard drive.  
失敗の結果、悪意のあるプロセスがホストのハードドライブ上のすべてのデータを上書きしたり、暗号化したりする可能性があります。 

Handlers should not assume that just because a host has been disconnected from the network, further damage to the host has been prevented.  
ハンドラーは、ホストがネットワークから切断されたからといって、ホストへのさらなる被害が防止されたと思い込んではいけません。

