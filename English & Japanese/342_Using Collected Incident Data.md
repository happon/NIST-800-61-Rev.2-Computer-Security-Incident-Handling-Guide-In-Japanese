### 3.4.2 Using Collected Incident Data 
### 3.4.2 収集したインシデントデータの利用  

Lessons learned activities should produce a set of objective and subjective data regarding each incident.  
学んだ教訓は、各インシデントに関する客観的なデータと主観的なデータのセットを作成すべきです。  

Over time, the collected incident data should be useful in several capacities.  
時間の経過とともに、収集されたインシデントデータは、いくつかの点で有用なものとなるはずです。  

The data, particularly the total hours of involvement and the cost, may be used to justify additional funding of the incident response team.  
データ、特に関与した総時間とコストは、インシデント対応チームの追加資金を正当化するために使用できます。 

A study of incident characteristics may indicate systemic security weaknesses and threats, as well as changes in incident trends.  
インシデントの特性を調査することで、システム的なセキュリティの弱点や脅威、インシデントの傾向の変化を示すことができます。  

This data can be put back into the risk assessment process, ultimately leading to the selection and implementation of additional controls.  
このデータは、リスク評価プロセスに戻され、最終的には追加の対策の選択と実施につながります。 

Another good use of the data is measuring the success of the incident response team.  
データのもう一つの有効な利用法は、インシデント対応チームの成功度を測定することです。  

If incident data is collected and stored properly, it should provide several measures of the success (or at least the activities) of the incident response team.  
インシデントデータが適切に収集され、保存されていれば、インシデント対応チームの成功（または少なくとも活動）のいくつかの尺度が得られるはずです。  

Incident data can also be collected to determine if a change to incident response capabilities causes a corresponding change in the team’s performance (e.g., improvements in efficiency, reductions in costs).  
また、インシデントデータを収集して、インシデント対応能力の変更がチームのパフォーマンスに対応する変化をもたらすかどうかを判断することもできます（例：効率性の向上、コストの削減）。  

Furthermore, organizations that are required to report incident information will need to collect the necessary data to meet their requirements.  
さらに、インシデント情報の報告を要求される組織は、要求事項を満たすために必要なデータを収集する必要があります。  

See Section 4 for additional information on sharing incident data with other organizations.  
他の組織とのインシデントデータの共有に関する追加情報については、セクション4を参照してください。  

Organizations should focus on collecting data that is actionable, rather than collecting data simply because it is available.  
組織は、単にデータが入手可能だからといってデータを収集するのではなく、実行可能なデータを収集することに焦点を当てるべきです。  

For example, counting the number of precursor port scans that occur each week and producing a chart at the end of the year that shows port scans increased by eight percent is not very helpful and may be quite time-consuming.  
例えば、毎週発生する前兆となるポートスキャンの数を数え、年末にポートスキャンが8%増加したことを示すチャートを作成することは、あまり参考にならず、非常に時間のかかることになります。  

Absolute numbers are not informative—understanding how they represent threats to the business processes of the organization is what matters.  
絶対的な数字だけでは、組織のビジネスプロセスに対する脅威をどのように表しているかを理解することが重要です。  

Organizations should decide what incident data to collect based on reporting requirements and on the expected return on investment from the data (e.g., identifying a new threat and mitigating the related vulnerabilities before they can be exploited.)  
組織は、報告要件とデータから期待される投資収益率（例えば、新しい脅威を特定し、それらが悪用される前に関連する脆弱性を緩和すること）に基づいて、どのようなインシデントデータを収集するかを決定する必要があります。  

Possible metrics for incident-related data include:  
インシデント関連データの測定基準としては、以下のようなものが考えられます。   

■ Number of Incidents Handled.46  
■ 対応したインシデントの数  

 Handling more incidents is not necessarily better—for example, the number of incidents handled may decrease because of better network and host security controls, not because of negligence by the incident response team.  
 例えば、対応したインシデント数は、インシデント対応チームの過失ではなく、ネットワークやホストのセキュリ ティ管理が改善されたために減少する場合があります。  
 
 The number of incidents handled is best taken as a measure of the relative amount of work that the incident response team had to perform, not as a measure of the quality of the team, unless it is considered in the context of other measures that collectively give an indication of work quality.  
 処理されたインシデント数は、インシデント対応チームが実行しなければならなかった作業の相対的な量を測るものであって、チームの品質を測るものではないと考えるのが最善です。  
 
 It is more effective to produce separate incident counts for each incident category.  
 各インシデントカテゴリごとに別々のインシデントカウントを作成する方がより効果的です。  
 
 Subcategories also can be used to provide more information.  
 また、より多くの情報を提供するためにサブカテゴリーを使用することもできます。
 
 For example, a growing number of incidents performed by insiders could prompt stronger policy provisions concerning background investigations for personnel and misuse of computing resources and stronger security controls on internal networks (e.g., deploying intrusion detection software to more internal networks and hosts).   
 例えば、インサイダーによって実行されるインシデントの数が増加していることから、人員の身元調査やコンピューティングリソースの不正使用に関するポリシーの規定を強化したり、内部ネットワークのセキュリティ管理を強化したりすることができます（例えば、より多くの内部ネットワークやホストに侵入検知ソフトウェアを配備するなど）。  

■ Time Per Incident.  
■ インシデントあたりの時間
 
 For each incident, time can be measured in several ways:  
 各インシデントについて、時間はいくつかの方法で測定することができます。  
 
 - Total amount of labor spent working on the incident  
 - インシデントの作業に費やされた労働力の総量  
 
 - Elapsed time from the beginning of the incident to incident discovery, to the initial impact assessment, and to each stage of the incident handling process (e.g., containment, recovery)  
 - インシデントの開始からインシデントの発見、最初の影響評価、およびインシデント処理プロセスの各段階（封じ込め、回復など）までの経過時間  

 - How long it took the incident response team to respond to the initial report of the incident  
 - インシデント対応チームがインシデントの初動報告に対応するまでに要した時間  
 
 - How long it took to report the incident to management and, if necessary, appropriate external entities (e.g., US-CERT).  
 - 管理者への報告、および必要に応じて適切な外部団体（US-CERT など）への報告にどのくらいの期間を要したか。  

■ Objective Assessment of Each Incident.  
■ 各インシデントの客観的な評価  

 The response to an incident that has been resolved can be analyzed to determine how effective it was.  
 解決したインシデントへの対応を分析することで、それがどれだけ効果的であったかを判断することができます。  

 The following are examples of performing an objective assessment of an incident:  
 以下は、インシデントの客観的な評価を行う例です。  

 - Reviewing logs, forms, reports, and other incident documentation for adherence to established incident response policies and procedures  
 - 確立されたインシデント対応方針および手順に準拠しているかどうか、ログ、記録用紙、報告書、およびその他のインシデント文書をレビューする。  
 
 - Identifying which precursors and indicators of the incident were recorded to determine how effectively the incident was logged and identified  
 - インシデントのどの前兆と兆候が記録されたかを特定し、インシデントがどれだけ効果的に記録され、特定されたかを判断する。  
 
 - Determining if the incident caused damage before it was detected  
 - インシデントが発覚する前に被害が発生したかどうかの判断  
 
 - Determining if the actual cause of the incident was identified, and identifying the vector of attack, the vulnerabilities exploited, and the characteristics of the targeted or victimized systems, networks, and applications  
 - インシデントの実際の原因が特定されたかどうかを判断し、攻撃の方向性、悪用された脆弱性、標的または被害を受けたシステム、ネットワーク、およびアプリケーションの特徴を特定する。  
 
 - Determining if the incident is a recurrence of a previous incident  
 - インシデントが以前のインシデントの再発であるかどうかの判断  
 
 - Calculating the estimated monetary damage from the incident (e.g., information and critical business processes negatively affected by the incident)  
 - インシデントによる推定金銭的損害の計算（インシデントによって悪影響を受けた情報や重要なビジネスプロセスなど）  

 - Measuring the difference between the initial impact assessment and the final impact assessment (see Section 3.2.6)  
 - 最初の影響評価と最終的な影響評価との差の測定（3.2.6項参照
 
 - Identifying which measures, if any, could have prevented the incident.  
 - どのような対策があれば、事故を防ぐことができたかを特定すること。  


■ Subjective Assessment of Each Incident.  
■ 各インシデントの主観的評価  

 Incident response team members may be asked to assess their own performance, as well as that of other team members and of the entire team.  
 インシデント対応チームのメンバーは、自分のパフォーマンスだけでなく、他のチームメンバーやチーム全体のパフォーマンスの評価を求められることがあります。  
 
 Another valuable source of input is the owner of a resource that was attacked, in order to determine if the owner thinks the incident was handled efficiently and if the outcome was satisfactory.  
 もう一つの貴重な情報源は、攻撃を受けたリソースの所有者であり、その所有者がインシデントが効率的に処理されたと考えているかどうか、またその結果が満足のいくものであったかどうかを判断するためである。  

<br/>

Besides using these metrics to measure the team’s success, organizations may also find it useful to periodically audit their incident response programs.  
チームの成功を測定するためにこれらの測定基準を使用するだけでなく、組織は定期的にインシデント対応プログラムを監査することも有用であると考えられます。  

Audits will identify problems and deficiencies that can then be corrected.  
監査は、問題や欠陥を特定し、それを修正することができます。  

At a minimum, an incident response audit should evaluate the following items against applicable regulations, policies, and generally accepted practices:  
最低限、インシデント対応監査では、以下の項目を適用される規則、方針、および一般に認められた慣行に照らして評価する必要があります。  


■ Incident response policies, plans, and procedures  
■ インシデント対応の方針、計画、および手順

■ Tools and resources  
■ ツールとリソース

■ Team model and structure  
■ チームモデルと構造

■ Incident handler training and education  
■ インシデントハンドラーの訓練と教育

■ Incident documentation and reports  
■ インシデント文書と報告書

■ The measures of success discussed earlier in this section.  
■ このセクションで先に説明した成功の尺度