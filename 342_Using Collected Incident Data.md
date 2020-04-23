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

 Number of Incidents Handled.46  


 Handling more incidents is not necessarily better—for example, the number of incidents handled may decrease because of better network and host security controls, not because of negligence by the incident response team.  
 
 
 The number of incidents handled is best taken as a measure of the relative amount of work that the incident response team had to perform, not as a measure of the quality of the team, unless it is considered in the context of other measures that collectively give an indication of work quality.  
 
 
 It is more effective to produce separate incident counts for each incident category.  
 
 
 Subcategories also can be used to provide more information.  
 
 
 For example, a growing number of incidents performed by insiders could prompt stronger policy provisions concerning background investigations for personnel and misuse of computing resources and stronger security controls on internal networks (e.g., deploying intrusion detection software to more internal networks and hosts).   


 Time Per Incident.  
 
 
 For each incident, time can be measured in several ways:  
 
 
 – Total amount of labor spent working on the incident  
 
 
 – Elapsed time from the beginning of the incident to incident discovery, to the initial impact assessment, and to each stage of the incident handling process (e.g., containment, recovery)  


 – How long it took the incident response team to respond to the initial report of the incident  
 
 
 – How long it took to report the incident to management and, if necessary, appropriate external entities (e.g., US-CERT).  


 Objective Assessment of Each Incident.  


 The response to an incident that has been resolved can be analyzed to determine how effective it was.  


 The following are examples of performing an objective assessment of an incident:  


 – Reviewing logs, forms, reports, and other incident documentation for adherence to established incident response policies and procedures  
 
 
 – Identifying which precursors and indicators of the incident were recorded to determine how effectively the incident was logged and identified  
 
 
 – Determining if the incident caused damage before it was detected  
 
 
 – Determining if the actual cause of the incident was identified, and identifying the vector of attack, the vulnerabilities exploited, and the characteristics of the targeted or victimized systems, networks, and applications  
 
 
 – Determining if the incident is a recurrence of a previous incident  
 
 
 – Calculating the estimated monetary damage from the incident (e.g., information and critical business processes negatively affected by the incident)  


 – Measuring the difference between the initial impact assessment and the final impact assessment (see Section 3.2.6)  
 
 
 – Identifying which measures, if any, could have prevented the incident.  


 Subjective Assessment of Each Incident.  


 Incident response team members may be asked to assess their own performance, as well as that of other team members and of the entire team.  
 
 
 Another valuable source of input is the owner of a resource that was attacked, in order to determine if the owner thinks the incident was handled efficiently and if the outcome was satisfactory.  


Besides using these metrics to measure the team’s success, organizations may also find it useful to periodically audit their incident response programs.  


Audits will identify problems and deficiencies that can then be corrected. At a minimum, an incident response audit should evaluate the following items against applicable regulations, policies, and generally accepted practices:  



 Incident response policies, plans, and procedures  


 Tools and resources  


 Team model and structure  


 Incident handler training and education  


 Incident documentation and reports  


 The measures of success discussed earlier in this section.  
