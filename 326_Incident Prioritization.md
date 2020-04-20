### 3.2.6 Incident Prioritization 
### 3.2.6 インシデントの優先順位付け 

Prioritizing the handling of the incident is perhaps the most critical decision point in the incident handling process.  
インシデントの処理に優先順位をつけることは、おそらくインシデントハンドリングプロセスの中で最も重要な決定ポイントです。

Incidents should not be handled on a first-come, first-served basis as a result of resource limitations.  
インシデントは、リソースの制限の結果、先着順で処理されるべきではありません。 

Instead, handling should be prioritized based on the relevant factors, such as the following:  
その代わり、以下のような関連する要因に基づいて優先的に処理を行うべきです。

■ Functional Impact of the Incident.  
■ インシデントの機能的影響

Incidents targeting IT systems typically impact the business functionality that those systems provide, resulting in some type of negative impact to the users of those systems.  
IT システムを標的としたインシデントは、通常、それらのシステムが提供するビジネス機能に影響を与え、その結果、それらのシステムのユーザに何らかのネガティブな影響を与えます。 

Incident handlers should consider how the incident will impact the existing functionality of the affected systems.  
インシデント・ハンドラは、インシデントが影響を受けるシステムの既存の機能にどのような影響を与えるかを考慮する必要があります。

Incident handlers should consider not only the current functional impact of the incident, but also the likely future functional impact of the incident if it is not immediately contained.  
インシデント・ハンドラは、インシデントの現在の機能的な影響だけでなく、インシデントがすぐに収束しない場合には、インシデントの将来的な機能的な影響も考慮する必要があります。 

■ Information Impact of the Incident.  
■ インシデントによる情報への影響

Incidents may affect the confidentiality, integrity, and availability of the organization’s information.  
インシデントは、組織の情報の機密性、完全性、および可用性に影響を与える可能性があります。 

For example, a malicious agent may exfiltrate sensitive information.  
例えば、悪意のあるエージェントが機密情報を流出させることがあります。 

Incident handlers should consider how this information exfiltration will impact the organization’s overall mission.  
インシデント担当者は、この情報流出が組織の全体的なミッションにどのような影響を与えるかを考慮する必要があります。 

An incident that results in the exfiltration of sensitive information may also affect other organizations if any of the data pertained to a partner organization.  
機密情報の流出につながるインシデントは、データのいずれかがパートナー組織に関係している場合、他の組織にも影響を及ぼす可能性があります。 

■ Recoverability from the Incident.  
■ インシデントからの復旧性

The size of the incident and the type of resources it affects will determine the amount of time and resources that must be spent on recovering from that incident.  
インシデントの規模と影響を受けるリソースの種類によって、インシデントからの復旧に費やさなければならない時間とリソースの量が決まります。

In some instances it is not possible to recover from an incident (e.g., if the confidentiality of sensitive information has been compromised) and it would not make sense to spend limited resources on an elongated incident handling cycle, unless that effort was directed at ensuring that a similar incident did not occur in the future.  
インシデントからの復旧が不可能な場合もあり（例えば、機密情報の機密性が損なわれた場合など）、将来的に同様のインシデントが発生しないようにするための努力をしない限り、インシデント処理サイクルの長期化に限られたリソースを費やすことは意味がありません。 

In other cases, an incident may require far more resources to handle than what an organization has available.  
他のケースでは、インシデントを処理するために、組織が利用できるリソースをはるかに上回るリソースを必要とする場合もあります。

Incident handlers should consider the effort necessary to actually recover from an incident and carefully weigh that against the value the recovery effort will create and any requirements related to incident handling.  
インシデント担当者は、インシデントから実際に回復するために必要な努力を検討し、回復努力が生み出す価値やインシデント処理に関連する要件と比較して慎重に検討すべきです。

<br/>

Combining the functional impact to the organization’s systems and the impact to the organization’s information determines the business impact of the incident  
組織のシステムへの機能的な影響と組織の情報への影響を組み合わせることで、インシデントのビジネスへの影響を決定します。

—for example, a distributed denial of service attack against a public web server may temporarily reduce the functionality for users attempting to access the server, whereas unauthorized root-level access to a public web server may result in the exfiltration of personally identifiable information (PII), which could have a long-lasting impact on the organization’s reputation.  
-例えば、公開 Web サーバーに対するDDoS攻撃は、サーバーにアクセスしようとするユーザーの機能を一時的に低下させる可能性があり、公開 Web サーバーへの不正なルートレベルのアクセスは、個人を特定できる情報（PII）を流出させる結果となり、組織の評判に長期的な影響を与える可能性があります。 

<br/>

The recoverability from the incident determines the possible responses that the team may take when handling the incident.  
インシデントからの回復の可能性は、インシデントに対処する際にチームが取り得る対応を決定します。

An incident with a high functional impact and low effort to recover from is an ideal candidate for immediate action from the team.  
機能的な影響が大きく、復旧にかかる労力が少ないインシデントは、チームが即座に対応するための理想的な候補となります。 

However, some incidents may not have smooth recovery paths and may need to be queued for a more strategic-level response
しかし、インシデントの中には、スムーズな回復経路を持たないものもあり、より戦略的レベルの対応が必要な場合もあります。

—for example, an incident that results in an attacker exfiltrating and publicly posting gigabytes of sensitive data has no easy recovery path since the data is already exposed;  
-例えば、攻撃者がギガバイトの機密データを流出させて公開するようなインシデントが発生した場合、データはすでに公開されているため、簡単に復旧することはできません。 

in this case the team may transfer part of the responsibility for handling the data exfiltration incident to a more strategic-level team that develops strategy for preventing future breaches and creates an outreach plan for alerting those individuals or organizations whose data was exfiltrated.  
この場合、チームは、データ流出事件への対応の責任の一部をより戦略的レベルのチームに移すことができます。 

The team should prioritize the response to each incident based on its estimate of the business impact caused by the incident and the estimated efforts required to recover from the incident.  
チームは、インシデントによって引き起こされたビジネスへの影響の推定値と、インシデントからの復旧に必要な推定努力に基づいて、各インシデントへの対応に優先順位をつけるべきです。 

<br/>

An organization can best quantify the effect of its own incidents because of its situational awareness.  
組織は、状況を認識しているため、自らのインシデントの影響を最もよく定量化することができます。 

Table 3-2 provides examples of functional impact categories that an organization might use for rating its own incidents.  
表 3-2 は、組織が自社のインシデントの評価に使用することができる機能的影響のカテゴリーの例を示しています。 

Rating incidents can be helpful in prioritizing limited resources.  
インシデントを評価することは、限られたリソースに優先順位をつけるのに役立ちます。 

Table 3-2. Functional Impact Categories  
表３－２　機能的影響カテゴリー  
|category<br/>カテゴリー|Definition 定義|
|-|-|
|None<br/>なし|No effect to the organization’s ability to provide all services to all users <br/>すべての利用者、サービス等組織の能力に影響を与えない |
|Low<br/>低|Minimal effect; the organization can still provide all critical services to all users but has lost efficiency<br/>最小限の影響; 組織はまだすべてのユーザーにすべての重要なサービスを提供することができますが、効率性を失っています|
|Medium<br/>中|Organization has lost the ability to provide a critical service to a subset of system users<br/>組織はシステムユーザーに重要なサービスを提供する能力を失っている |
|High<br/>高|Organization is no longer able to provide some critical services to any users <br/>組織が利用者に重要なサービスを提供できなくなっている |

<br/>

Table 3-3 provides examples of possible information impact categories that describe the extent of information compromise that occurred during the incident.  
表 3-3 は、インシデント中に発生した情報漏洩の程度を表す情報影響カテゴリの例を示しています。 

In this table, with the exception of the ‘None’ value, the categories are not mutually exclusive and the organization could choose more than one.  
この表では、「なし」の値を除いて、カテゴリは相互に排他的ではなく、組織は複数のカテゴリを選択することができます。

Table 3-3. Information Impact Categories  
表３－３　情報的影響カテゴリー  
|category<br/>カテゴリー|Definition 定義|
|-|-|
|None<br/>なし|No information was exfiltrated, changed, deleted, or otherwise compromised<br/>情報が流出、変更、削除されていないか、または他の方法で危険にさらされていない。|
|PrivacyBreach<br/>プライバシー侵害|Sensitive personally identifiable information (PII) of taxpayers, employees, beneficiaries, etc. was accessed or exfiltrated<br/>納税者、従業員、受益者等の機密性の高い個人情報（PII）へのアクセスや流出|
|Proprietary Breach<br/>専有情報の流出|Unclassified proprietary information, such as protected critical infrastructure information (PCII), was accessed or exfiltrated<br/>保護された重要インフラ情報(PCII)などの未分類の専有情報へのアクセスまたは流出|
|Integrity Loss<br/>完全流出|Sensitive or proprietary information was changed or deleted<br/>機密情報や専有情報が変更または削除された|  

<br/>

Table 3-4 shows examples of recoverability effort categories that reflect the level of and type of resources required to recover from the incident.  
表 3-4 は、インシデントからの復旧に必要なリソースのレベルと種類を反映した復旧可能性の努力カテゴリの例を示しています。  

Table 3-4. Recoverability Effort Categories  
復旧可能性の努力カテゴリ
|category<br/>カテゴリー|Definition 定義|
|-|-|
